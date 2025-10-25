# Project Dashboard - Monday Clone

A beautiful, interactive project management dashboard inspired by Monday.com, built with React and styled with Tailwind CSS. Features drag-and-drop functionality, persistent storage, and a clean, modern interface.

![Project Dashboard](https://img.shields.io/badge/React-18-blue) ![Tailwind](https://img.shields.io/badge/Tailwind-CSS-38B2AC) ![License](https://img.shields.io/badge/license-MIT-green)

## ✨ Features

- **📋 Task Management**: Create, edit, and delete tasks with ease
- **👥 Group Organization**: Organize tasks into collapsible groups
- **🎨 Visual Status**: Color-coded status and priority indicators
- **🔄 Drag & Drop**: Reorder tasks and columns with intuitive drag-and-drop
- **💾 Persistent Storage**: All changes automatically saved to browser localStorage
- **📅 Date Tracking**: Request dates, due dates, and timeline management
- **✏️ Inline Editing**: Click to edit any field directly
- **🗑️ Safe Deletion**: Confirmation modal before deleting tasks
- **📱 Responsive Design**: Works on desktop and mobile devices

## 🚀 Quick Start

### Option 1: Run Locally

1. Clone this repository:
```bash
git clone https://github.com/yourusername/monday-clone.git
cd monday-clone
```

2. Open `index.html` in your browser:
   - Double-click the file, or
   - Right-click and select "Open with" → Your browser
   - Or use a local server (recommended):
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js
   npx serve
   ```

3. Visit `http://localhost:8000` in your browser

### Option 2: GitHub Pages

1. Fork this repository
2. Go to Settings → Pages
3. Select "Deploy from a branch"
4. Choose `main` branch and `/root` folder
5. Click Save
6. Your app will be live at `https://yourusername.github.io/monday-clone/`

## 🎮 How to Use

### Managing Tasks
- **Add Task**: Click "Add new item" at the bottom of any group
- **Edit Task**: Click any field to edit it inline
- **Delete Task**: Click the trash icon and confirm deletion
- **Reorder Tasks**: Drag tasks by the grip icon to reorder

### Organizing Work
- **Collapse/Expand Groups**: Click the chevron icon next to group names
- **Change Status**: Click status badges to update (Working on it, Done, Stuck, Not started)
- **Set Priority**: Click priority badges to toggle between High and Standard
- **Update Dates**: Use date pickers for request and due dates

### Customizing Columns
- **Reorder Columns**: Drag column headers to rearrange (except Actions column)
- **Column order is saved**: Your preferences persist across sessions

## 💾 Data Persistence

All your data is automatically saved to your browser's localStorage:
- Tasks and their details
- Group expansion states
- Column order preferences

**Note**: Data is stored locally in your browser. Clearing browser data will reset the app.

## 🛠️ Technical Details

### Built With
- **React 18**: UI framework
- **Tailwind CSS**: Styling
- **Lucide Icons**: Beautiful SVG icons
- **localStorage API**: Data persistence

### Browser Compatibility
- ✅ Chrome/Edge (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Opera

Requires a modern browser with ES6+ support and localStorage.

## 📁 Project Structure

```
monday-clone/
├── index.html          # Main application file (single-file app)
├── README.md           # This file
├── LICENSE            # MIT License
└── screenshot.png     # App screenshot (optional)
```

## 🎨 Customization

You can easily customize the app by editing `index.html`:

### Change Colors
```javascript
const statusColors = {
  'Working on it': '#81b6e3',  // Light blue
  'Done': '#53df98',           // Green
  'Stuck': '#e4732f',          // Orange
  'Not started': '#9ca3af'     // Gray
};

const priorityColors = {
  'High': '#a6e42f',           // Lime
  'Standard': '#81b6e3'        // Light blue
};
```

### Add New Status Options
```javascript
const options = ['Working on it', 'Done', 'Stuck', 'Not started', 'On Hold'];
```

### Modify Groups
```javascript
const groups = {
  group1: { title: 'Sprint Planning', color: 'blue' },
  group2: { title: 'In Progress', color: 'purple' },
  group3: { title: 'Testing', color: 'green' }
};
```

## 🤝 Contributing

Contributions are welcome! Feel free to:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by [Monday.com](https://monday.com)
- Icons by [Lucide](https://lucide.dev)
- Styling by [Tailwind CSS](https://tailwindcss.com)

## 🐛 Known Issues & Future Enhancements

### Coming Soon
- [ ] Add new groups dynamically
- [ ] Export/Import data (JSON)
- [ ] Dark mode
- [ ] Team member avatars with images
- [ ] Task comments and attachments
- [ ] Search and filter functionality
- [ ] Keyboard shortcuts

### Known Issues
- None reported yet! Found a bug? Please [open an issue](https://github.com/yourusername/monday-clone/issues)

## 📧 Contact

Your Name - [@yourtwitter](https://twitter.com/yourtwitter)

Project Link: [https://github.com/yourusername/monday-clone](https://github.com/yourusername/monday-clone)

---

⭐ Star this repo if you find it helpful!
