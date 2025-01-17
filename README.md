# 📝 Python To-Do List Application

A beautiful and functional To-Do List application built with Python Tkinter and SQLite database integration. Keep track of your tasks with persistent storage and an intuitive user interface.



## ✨ Features

- 📊 Clean and modern user interface
- 💾 SQLite database for persistent storage
- ➕ Add new tasks easily
- 🗑️ Remove single or all tasks
- 🎨 Beautiful color scheme
- ⚡ Error handling and validation
- 🔄 Real-time list updates
- 📱 Responsive design

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/python-todo-list.git
cd python-todo-list
```

2. Ensure you have Python installed (Python 3.6 or higher recommended)

3. Install required dependencies:
```bash
# No additional dependencies required - uses built-in libraries
```

4. Run the application:
```bash
python todo_app.py
```

## 💻 Requirements

- Python 3.6+
- Tkinter (included with Python)
- SQLite3 (included with Python)

## 🎯 Usage

### Adding Tasks
1. Enter your task in the input field
2. Click "Add" or press Enter
3. Task will appear in the list below

### Managing Tasks
- **Remove**: Select a task and click "Remove"
- **Delete All**: Click "Delete All" to clear all tasks
- **Exit**: Click "Exit / Close" to save and close the application

## 🎨 Color Scheme

The application features a carefully designed color palette:
- Main Background: `#B5E5CF` (Soft Mint)
- Functions Frame: `#8EE5EE` (Light Blue)
- Buttons: `#D4AC0D` (Golden)
- Selected Task: `#FF8C00` (Dark Orange)
- Text Colors:
  - Title: `#FF6103` (Orange)
  - Tasks: Black
  - Selected Text: Black

## 📁 Project Structure

```
python-todo-list/
├── todo_app.py         # Main application file
├── listOfTasks.db      # SQLite database file
├── README.md           # This file
└── images/            # Screenshots and images
    └── preview.png    # Application preview image
```

## 🔧 Technical Details

### Database Schema
```sql
CREATE TABLE tasks (
    title text
);
```

### Key Functions
- `add_task()`: Adds new task to database and list
- `delete_task()`: Removes selected task
- `delete_all_tasks()`: Clears all tasks
- `retrieve_database()`: Loads tasks from database
- `list_update()`: Updates the GUI list

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 Planned Features

- [ ] Task categories/labels
- [ ] Due dates and reminders
- [ ] Task priority levels
- [ ] Search functionality
- [ ] Dark/Light theme toggle
- [ ] Export tasks to file
- [ ] Task completion status
- [ ] Multiple task lists
- [ ] Task notes/descriptions

## ❗ Error Handling

The application includes comprehensive error handling:
- Empty task validation
- Task selection validation
- Database operation error handling
- Confirmation dialogs for critical actions



## 👏 Acknowledgments

- Built with Python's Tkinter library
- Database management with SQLite3
- Inspired by modern task management applications
- Color scheme inspired by nature and productivity

## 📫 Contact

Your Name - HEDAYAT

Project Link: [(python-todo-list)](https://github.com/Hedayat-design/To_do_list)

---
Made with ❤️ by HEDAYAT(https://github.com/yourusername)
