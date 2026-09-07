# Attendance Management System & To-Do List

A collection of useful web applications built with HTML, CSS, and JavaScript with local storage functionality.

## Applications Included

### 1. Student Attendance Management System
A web-based attendance tracker for St Joseph's First Grade College, Hunsur - 2nd BCA.

**Features:**
- Mark students as Present or Absent
- Real-time attendance percentage calculation
- Search students by name
- Date selection
- Summary statistics (Total, Present, Absent, Attendance %)
- Responsive design

**How to use:**
1. Open `index.html` in your web browser
2. Select the date
3. Click "Present" or "Absent" buttons for each student
4. Click "Save Attendance" to save the session

### 2. To-Do List Application
A fully-featured to-do list with local storage persistence.

**Features:**
- ✅ Add, delete, and complete tasks
- 💾 Automatic local storage persistence
- 🔍 Filter tasks (All, Active, Completed)
- 📊 Statistics (Total, Completed, Pending tasks)
- 🎨 Beautiful gradient UI with smooth animations
- 📱 Fully responsive design
- 🗑️ Clear all completed tasks option
- ✏️ Add tasks with Enter key or button click

**How to use:**
1. Open `todo.html` in your web browser
2. Type your task in the input field
3. Press Enter or click "Add" button
4. Click the checkbox to mark tasks as complete
5. Use filter buttons to view All, Active, or Completed tasks
6. Click "Delete" to remove individual tasks
7. Click "Clear All Completed" to remove all completed tasks

**Data Persistence:**
- All tasks are automatically saved to browser's local storage
- Your tasks will persist even after closing and reopening the browser
- Data is stored locally on your device (not on any server)

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with gradients and animations
- **JavaScript (ES6+)** - Application logic
- **Local Storage API** - Data persistence

## Browser Compatibility

Both applications work on all modern browsers:
- Chrome/Edge (recommended)
- Firefox
- Safari
- Opera

## Installation

No installation required! Simply download the files and open them in your web browser.

```bash
# Clone the repository
git clone https://github.com/naveeng-ul/attendance-management-system.git

# Navigate to the directory
cd attendance-management-system

# Open in browser
# Double-click index.html or todo.html
```

## File Structure

```
attendance-management-system/
├── index.html          # Student Attendance Management System
├── todo.html           # To-Do List Application
└── README.md           # This file
```

## Features in Detail

### Attendance System
- **Real-time Statistics**: Updates as you mark attendance
- **Search Functionality**: Filter students by name
- **Date Tracking**: Track attendance by date
- **Clean UI**: Easy-to-use interface
- **Persistent UI**: Current session state (without localStorage for attendance)

### To-Do List
- **Task Management**: Add, edit, delete tasks
- **Local Storage**: Automatic persistence
- **Smart Filtering**: View by status
- **Statistics Dashboard**: Track progress
- **Beautiful Design**: Gradient backgrounds and smooth transitions
- **Empty State**: Helpful message when no tasks exist

## Future Enhancements

- Export attendance data to PDF/Excel
- Add student information (email, phone)
- Task priority levels
- Task categories/tags
- Due date reminders
- Multi-user support
- Cloud synchronization

## Contributing

Feel free to fork this repository and submit pull requests with improvements!

## License

This project is open source and available under the MIT License.

## Author

Created by Naveen G

## Support

For issues or questions, please create an issue on the GitHub repository.

---

**Last Updated**: September 2026