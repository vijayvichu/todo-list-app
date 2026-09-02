# 📝 To-Do List Application

A modern, feature-rich to-do list application with local storage functionality. Built with vanilla HTML, CSS, and JavaScript.

## 🌟 Features

### Core Functionality
- ✅ **Add Tasks** - Easily add new tasks with a clean interface
- 🗑️ **Delete Tasks** - Remove individual tasks with one click
- ☑️ **Mark Complete** - Toggle task completion status
- 💾 **Local Storage** - All tasks are automatically saved to browser storage
- 📊 **Statistics** - View total, active, and completed task counts

### Filtering
- 🔍 **All Tasks** - View all tasks
- 🔄 **Active Tasks** - Show only incomplete tasks
- ✔️ **Completed Tasks** - Show only completed tasks

### Advanced Features
- 🏷️ **Priority Levels** - Tasks have priority indicators (High, Medium, Low)
- 📥 **Export** - Download all tasks as a JSON file
- 🧹 **Clear Completed** - Remove all completed tasks at once
- ⚠️ **Clear All** - Remove all tasks (with confirmation)
- ⏰ **Timestamps** - Each task records when it was created

### User Experience
- 🎨 **Modern Design** - Beautiful gradient UI with smooth animations
- 📱 **Responsive** - Works perfectly on desktop, tablet, and mobile
- ⌨️ **Keyboard Support** - Press Enter to add a new task
- 🎯 **Intuitive Interface** - Clean and easy-to-use layout

## 🚀 Quick Start

### Option 1: Open Directly
1. Clone or download this repository
2. Open `index.html` in your web browser
3. Start adding tasks!

### Option 2: Local Server (Recommended)
```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (with http-server)
npx http-server
```
Then visit `http://localhost:8000` in your browser.

## 💾 Data Storage

All tasks are automatically saved to your browser's **Local Storage**. This means:
- Tasks persist even after closing the browser
- No server or database required
- Data is stored locally on your device
- Storage limit is typically 5-10MB per domain

## 📁 Project Structure

```
todo-list-app/
├── index.html      # HTML structure
├── styles.css      # Styling and animations
├── app.js          # Application logic
└── README.md       # Documentation
```

## 🎨 Color Scheme

- **Primary Gradient**: Purple (#667eea) to Deep Purple (#764ba2)
- **Completed Tasks**: Gray (#999)
- **High Priority**: Red (#c00)
- **Medium Priority**: Orange (#990)
- **Low Priority**: Green (#060)

## 🔧 How to Use

### Adding a Task
1. Type your task in the input field
2. Click "Add" or press Enter
3. Task appears at the top of the list

### Completing a Task
- Click the checkbox next to a task to mark it as complete
- Completed tasks appear grayed out with strikethrough text

### Deleting a Task
- Click the "Delete" button next to any task
- Task is immediately removed

### Filtering Tasks
- Click "All" to see all tasks
- Click "Active" to see only incomplete tasks
- Click "Completed" to see only finished tasks

### Exporting Tasks
- Click "Export" to download all tasks as a JSON file
- Useful for backup or sharing

### Clearing Tasks
- **Clear Completed**: Removes all finished tasks
- **Clear All**: Removes all tasks (confirmation required)

## 🌐 Browser Compatibility

- ✅ Chrome/Chromium (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Android)

## 💡 Tips & Tricks

1. **Keyboard Navigation**: Use Enter key to quickly add tasks
2. **Export Backups**: Regularly export your tasks for backup
3. **Clear Cache**: If you want to reset, use "Clear All"
4. **Mobile Friendly**: Works great on phones and tablets

## 📝 Technical Details

### LocalStorage API
The app uses the browser's `localStorage` API to persist data:
```javascript
// Save: localStorage.setItem('todoList', JSON.stringify(todos))
// Load: JSON.parse(localStorage.getItem('todoList'))
```

### Class-Based Architecture
The app uses an ES6 class (`TodoApp`) for clean, organized code:
- Initialization and setup
- Event handling
- DOM manipulation
- Data persistence
- Filtering and rendering

## 🔒 Privacy

- ✅ No data sent to any server
- ✅ All data stored locally on your device
- ✅ No tracking or analytics
- ✅ Completely private and secure

## 📄 License

Free to use and modify for personal or commercial projects.

## 🤝 Contributing

Feel free to fork, modify, and improve this project!

## 🎯 Future Enhancements

Potential features for future versions:
- Due dates for tasks
- Recurring tasks
- Task categories/tags
- Dark mode
- Cloud sync option
- Drag and drop reordering
- Task notes/descriptions

---

Made with ❤️ for productivity lovers!
