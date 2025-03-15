# Arms and Ammunitions PDF Viewer

A web-based PDF viewer application designed for viewing and managing PDF files related to arms and ammunitions. The application fetches PDF files from a GitHub repository and displays them in a user-friendly interface.

## Features

- **PDF Listing**: Displays a list of PDF files from the GitHub repository
- **PDF Viewing**: View PDFs directly in the browser without downloading
- **Zoom Controls**: Adjust the zoom level of the PDF for better readability
- **Dark Theme**: Eye-friendly dark theme optimized for reading and studying
- **Responsive Design**: Works on various screen sizes
- **Real-time Updates**: Shows the last refresh time

## Setup Instructions

1. Clone this repository to your local machine
2. Add a background image file named `bg.jpg` to the `Assets` directory
3. Open `index.html` in a web browser to view the application

## GitHub Repository Integration

The application is configured to fetch PDF files from the following GitHub repository:
- Repository: [file-share103/Meta-Data](https://github.com/file-share103/Meta-Data)
- Path: `/rifiles`

## File Structure

- `index.html` - Main HTML file
- `styles.css` - CSS styles for the application
- `script.js` - JavaScript functionality
- `Assets/` - Directory for storing assets like background images

## Customization

- To add more folders, add new folder elements in the HTML with appropriate data-folder attributes
- To change the external links, modify the URLs in the script.js file
- To adjust the theme colors, modify the CSS variables in the styles.css file