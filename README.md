# Digital Attendance System - README

## Overview
This Digital Attendance System is a web-based application designed for educational institutions to manage student attendance records. It features:
- Teacher interface for marking attendance
- Student portal to view attendance records
- Support for 200 students across 5 computer science courses
- Responsive design with educational-themed animations

## Features

### Teacher Features
- View class lists (40 students per class)
- Mark attendance by date
- Submit attendance records
- Intuitive checkbox interface

### Student Features
- View personal attendance records
- Filter attendance by date
- See overall attendance percentage
- Access records across all enrolled classes

## Technical Specifications
- **Frontend**: HTML5, CSS3, JavaScript
- **Storage**: Browser localStorage (persists data between sessions)
- **Dependencies**: Font Awesome icons, Google Fonts
- **Responsive**: Works on desktop and mobile devices

## Installation

### Option 1: Local Usage
1. Copy the entire HTML code
2. Paste into a text editor (Notepad, VS Code, etc.)
3. Save as `attendance.html`
4. Open the file in any modern web browser

### Option 2: Netlify Deployment
1. Create a new repository with the HTML file
2. Sign up for a free Netlify account
3. Connect your GitHub/GitLab repository
4. Deploy the site with default settings

## Usage Instructions

### For Teachers
1. Click "I'm a Teacher"
2. Select a class from the dropdown
3. Click "Load Class"
4. Mark attendance by checking present students
5. Click "Submit Attendance"

### For Students
1. Click "I'm a Student"
2. Select your name from the dropdown
3. Click "View Attendance"
4. Review your attendance records

## Data Management
- The system automatically generates 200 sample students
- Students are distributed across 5 computer science courses
- Attendance data persists in browser localStorage

## System Requirements
- Modern web browser (Chrome, Firefox, Edge recommended)
- Internet connection (for loading fonts and icons)
- JavaScript enabled

## Known Limitations
- Data is browser-specific (won't sync across devices)
- No multi-user authentication in this version
- Attendance data clears if browser cache is cleared

## Customization Options
To modify the system:
1. Edit student names in the JavaScript section
2. Change course names in the `classes` object
3. Adjust colors in the CSS `:root` variables
4. Modify animation timings in the CSS `@keyframes` rules

## Support
For assistance, please ensure:
1. You're using a supported browser
2. JavaScript is enabled
3. You've cleared browser cache if experiencing issues

This system provides a complete, self-contained attendance solution that requires no server infrastructure or database setup.
