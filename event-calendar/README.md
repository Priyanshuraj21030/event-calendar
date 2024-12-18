# Event Calendar Application

A modern, interactive event calendar built with React, TypeScript, and Tailwind CSS. This application allows users to manage events with features like drag-and-drop, event filtering, and data export capabilities.

## Features

- 📅 Interactive calendar interface
- ✨ Drag and drop events
- 🎨 Color-coded event types (Work, Personal, Meeting, Other)
- 🔍 Search and filter events
- 📊 Event statistics and visualization
- 💾 Data persistence with localStorage and IndexedDB
- 📤 Export events to JSON and CSV formats
- ↩️ Undo/Redo functionality
- 📱 Responsive design
- 🎯 Multi-day event support

## Tech Stack

- React JS
- TypeScript
- Tailwind CSS
- Framer Motion (animations)
- react-beautiful-dnd (drag and drop)
- IndexedDB (data persistence)

## Prerequisites

- Node.js (v14 or higher)
- npm or yarn

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/event-calendar.git
cd event-calendar
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Start the development server:
```bash
npm run dev
# or
yarn dev
```

4. Open [http://localhost:5173](http://localhost:5173) in your browser.

## Usage Instructions

### Basic Navigation
- Use the Previous/Next buttons to navigate between months
- Current day is highlighted with a blue circle
- Weekends are distinguished with a light red background

### Managing Events
1. **Creating Events:**
   - Click on any day to open the event creation modal
   - Fill in event details (title, time, type, description)
   - Click Save to create the event

2. **Editing Events:**
   - Click on an existing event to view details
   - Click Edit to modify event details
   - Use drag-and-drop to reschedule events
   - Use resize handles to adjust event duration

3. **Deleting Events:**
   - Open an event's details
   - Click the Delete button
   - Confirm deletion in the prompt

### Advanced Features
- **Search:** Use the search bar to filter events by title or description
- **Type Filtering:** Use the type filters to show/hide specific event types
- **Undo/Redo:** 
  - Use Ctrl+Z to undo
  - Use Ctrl+Shift+Z to redo
  - Or use the undo/redo buttons in the interface

### Mobile Usage
- Touch and drag events to reschedule
- Use the resize handles to adjust event duration
- All features are optimized for touch interactions

## Project Structure

```
event-calendar/
├── src/
│   ├── components/
│   │   └── calendar/
│   │       ├── CalendarView.tsx
│   │       ├── EventModal.tsx
│   │       ├── TimeInput.tsx
│   │       └── TypeFilter.tsx
│   ├── types/
│   │   └── Event.ts
│   ├── utils/
│   │   ├── dateTime.ts
│   │   └── typography.ts
│   └── styles/
│       └── index.css
├── public/
└── package.json
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Built with React, TypeScript, and Tailwind CSS
- Uses react-beautiful-dnd for drag-and-drop functionality
- Framer Motion for animations
- Inspired by modern calendar applications
#   E v e n t - c a l e n d a r  
 #   e v e n t _ c a l e n d a r  
 #   e v e n t - c a l e n d a r  
 