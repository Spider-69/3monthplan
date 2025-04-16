# 3-Month Plan Tracker

## Description

The 3-Month Plan Tracker is a responsive web application designed to help users track their progress through a structured 3-month learning or skill development plan. This interactive tracker allows users to organize tasks by day and week, mark completed items, add personal notes, and visualize their overall progress.

## Key Features

- **Visual Progress Tracking**: Dynamic progress bar shows completion percentage at a glance
- **Weekly Organization**: Tasks are grouped by week for easier management and focus
- **Task Completion Tracking**: Simple checkbox system to mark tasks as complete
- **Detailed Notes**: Modal popup system for adding notes to each task
- **Data Persistence**: All progress and notes are saved to local storage
- **Import/Export Functionality**: Download and load progress data as JSON files
- **Mobile Responsive**: Optimized for both desktop and mobile devices
- **Modern UI/UX**: Clean, animated interface with a pleasant color scheme

## Technical Details

- Built with vanilla HTML, CSS, and JavaScript (no frameworks required)
- Uses local storage for data persistence
- Incorporates Font Awesome for icons and visual elements
- Implements Poppins font from Google Fonts for a modern look
- Features CSS animations for an engaging user experience

## How to Use

1. **Track Daily Progress**: 
   - Check off each task as you complete it
   - Your progress percentage updates automatically

2. **Manage Tasks by Week**:
   - Click on week headers to expand/collapse weekly tasks
   - Focus on one week at a time or view the entire plan

3. **Add Personal Notes**:
   - Click "Add Notes" to open a popup card
   - Write detailed notes about your experience or learnings
   - Save to keep track of your journey

4. **Save Your Progress**:
   - Progress and notes are automatically saved to your browser
   - Use the Download button to export your data as a backup
   - Use the Load button to restore progress from a downloaded file

## Customization

The task list can be easily customized by modifying the `tasks` array in the JavaScript code. Each task can include:
- Task description
- Optional link to learning resources

## Implementation Notes

This application uses:
- CSS Flexbox for responsive layout
- CSS Grid for table structure
- Local Storage API for data persistence
- Modal popups for a better mobile experience
- Custom animations for visual feedback

## Browser Compatibility

The 3-Month Plan Tracker works on all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

## Installation

Simply host the HTML file on any web server or open it directly in a browser. No server-side processing is required as all data is stored in the browser's local storage.
