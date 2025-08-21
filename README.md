# taskflow-app
# TaskFlow - Team Task Management Platform

## 🚀 Overview

TaskFlow is a modern, streamlined team task management platform designed to help teams organize, track, and manage their projects efficiently. Built with vanilla HTML, CSS, and JavaScript, it offers a clean, intuitive interface with powerful functionality for task creation, assignment, and progress tracking.

## ✨ Features

### 🎯 Core Functionality
- **Task Creation & Management** - Create, edit, and delete tasks with detailed information
- **Team Assignment** - Assign tasks to specific team members
- **Priority Levels** - Set task priorities (High, Medium, Low) with visual indicators
- **Status Tracking** - Track tasks through Pending → In Progress → Completed workflow
- **Due Date Management** - Set and monitor task deadlines with overdue notifications

### 📊 Dashboard & Analytics
- **Real-time Statistics** - Live dashboard showing total tasks, progress, and team metrics
- **Visual Progress Bars** - Track completion percentage for each task
- **Smart Filtering** - Filter tasks by status, priority, assignee, or combination
- **Responsive Design** - Fully optimized for desktop, tablet, and mobile devices

### 🎨 User Experience
- **Modern UI/UX** - Clean, professional design with smooth animations
- **Glassmorphism Effects** - Modern backdrop blur effects and transparency
- **Interactive Elements** - Hover effects, transitions, and visual feedback
- **Form Validation** - Real-time validation with helpful error messages
- **Notification System** - Success/error notifications for user actions

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Custom CSS with CSS Grid, Flexbox, and CSS Variables
- **Storage**: In-memory data storage (no backend required)
- **Deployment**: Static hosting compatible (GitHub Pages, Netlify, Vercel)

## 🎮 Live Demo

**[View Live Demo →](https://hruthikaanerao472.github.io/taskflow-app)**

*Replace with your actual GitHub Pages URL*

## 📱 Screenshots

### Desktop View
![Desktop Dashboard](https://via.placeholder.com/800x500/667eea/ffffff?text=TaskFlow+Desktop+Dashboard)

### Mobile View
![Mobile Interface](https://via.placeholder.com/400x600/764ba2/ffffff?text=TaskFlow+Mobile+View)

## 🚀 Quick Start

### Option 1: Direct Download
1. Download the `index.html` file from this repository
2. Open it in any modern web browser
3. Start managing your tasks immediately!

### Option 2: GitHub Pages Deployment
1. Fork this repository
2. Go to Settings → Pages
3. Select "Deploy from branch" → main branch
4. Your app will be live at `https://yourusername.github.io/repository-name`

### Option 3: Local Development
```bash
# Clone the repository
git clone https://github.com/yourusername/taskflow-app.git

# Navigate to the project directory
cd taskflow-app

# Open in your browser
open index.html
# or
python -m http.server 8000  # For Python 3
# Then visit http://localhost:8000
```

## 📋 Usage Guide

### Creating Tasks
1. Fill out the **Create New Task** form in the sidebar
2. Enter task title (required), description, assignee, priority, and due date
3. Click **"Create Task"** to add it to your board
4. Tasks appear immediately with real-time statistics updates

### Managing Tasks
- **Start Task**: Change status from Pending to In Progress
- **Complete Task**: Mark tasks as completed with 100% progress
- **Reopen Task**: Move completed tasks back to pending if needed
- **Delete Task**: Remove tasks permanently (with confirmation)

### Filtering & Organization
- Use the filter dropdowns to view specific task subsets
- Filter by status, priority, or assigned team member
- Combine multiple filters for precise task views
- All filters update the view in real-time

## 👥 Team Members (Sample Data)
The application comes with 5 sample team members:
- Alice Johnson
- Bob Smith  
- Carol Davis
- David Wilson
- Emma Brown

*You can modify the team member list in the JavaScript code.*

## 🎨 Customization

### Color Themes
The app uses CSS custom properties for easy theme customization:

```css
:root {
  --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  --success-color: #27ae60;
  --warning-color: #f39c12;
  --danger-color: #e74c3c;
}
```

### Adding Team Members
Edit the `teamMembers` array in the JavaScript:

```javascript
this.teamMembers = [
  'Your Name',
  'Team Member 2',
  'Team Member 3',
  // Add more team members
];
```

## 🌟 Features in Detail

### Smart Due Date Handling
- **Today**: Highlighted as "Today"
- **Tomorrow**: Marked as "Tomorrow" 
- **Overdue**: Red-colored with "(Overdue)" label
- **Upcoming**: Clean date format for future tasks

### Progress Visualization
- Visual progress bars with gradient fills
- Percentage indicators for precise tracking
- Automatic progress updates based on status changes
- Color-coded progress states

### Responsive Design Breakpoints
- **Desktop**: Full two-column layout with sidebar
- **Tablet**: Responsive grid adjustments
- **Mobile**: Single-column stack with optimized touch targets

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

### Contribution Ideas
- Add data persistence (localStorage/backend integration)
- Implement task categories/tags
- Add task comments/activity log
- Create printable reports
- Add dark mode theme
- Implement drag-and-drop task reordering

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🐛 Bug Reports & Feature Requests

Found a bug or have a feature idea? Please [open an issue](https://github.com//hruthikaanerao472/taskflow-app/issues) with:
- Clear description of the issue/feature
- Steps to reproduce (for bugs)
- Expected vs actual behavior
- Screenshots if applicable

## 🎉 Acknowledgments

- **Design Inspiration**: Modern task management tools and glassmorphism design trends
- **Icons**: Lucide React icon system concepts
- **Color Palette**: Carefully selected gradients for modern appeal
- **Typography**: Segoe UI system font stack for optimal readability

## 📊 Project Stats

![GitHub repo size](https://img.shields.io/github/repo-size/hruthikaanerao472/taskflow-app)
![GitHub last commit](https://img.shields.io/github/last-commit//hruthikaanerao472/taskflow-app)
![GitHub issues](https://img.shields.io/github/issues//hruthikaanerao472/taskflow-app)
![GitHub stars](https://img.shields.io/github/stars//hruthikaanerao472/taskflow-app)

---

<div align="center">

**[⭐ Star this repo](https://github.com//hruthikaanerao472/taskflow-app)** if you find it helpful!

Made with ❤️ for better team productivity

[Demo](https://hruthikaanerao472.github.io/taskflow-app) • [Issues](https://github.com//hruthikaanerao472/taskflow-app/issues) • [Contribute](https://github.com//hruthikaanerao472/taskflow-app/pulls)

</div>
