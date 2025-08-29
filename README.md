# Magganas Expense Upload System

A secure web-based expense tracking system for property management with photo receipt uploads.

## Features

- **Secure Authentication**: Token-based access control
- **Photo Uploads**: Automatic receipt storage in Google Drive
- **Real-time Validation**: Client-side form validation
- **Mobile Friendly**: Responsive Bootstrap design
- **Automated Storage**: Direct integration with Google Sheets

## Files

- `index.html` - Main form for GitHub Pages deployment
- `google-apps-script.js` - Backend processing script
- `CLAUDE.md` - Technical documentation for Claude Code

## Setup

1. Deploy `google-apps-script.js` as a Google Apps Script Web App
2. Update the `WEB_APP_URL` in the HTML file
3. Host `index.html` on GitHub Pages

## Security

- Access token required for all submissions
- Private Google Sheets/Drive storage
- HTTPS-only access via GitHub Pages

## Usage

Access the form at the GitHub Pages URL and submit expenses with receipts. All data is automatically organized in Google Sheets with receipts stored in Google Drive.