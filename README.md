# Basic-NodeJS-File-Server
# Node.js Static File Server

A basic Node.js application that serves static files (HTML, CSS, JavaScript, images) using the HTTP module. This project is designed to help beginners understand how to build a simple static file server.

## Features
- Serves HTML, CSS, JavaScript, and image files.
- Handles MIME types to ensure correct file rendering in the browser.
- Displays a 404 error page for missing files.

## Getting Started

### Prerequisites
- Node.js installed on your system.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Basic-NodeJS-File-Server.git
   	2.	Navigate to the project folder:
    cd Basic-NodeJS-File-Server
    	3.	Ensure your static files (like index.html, styles.css, etc.) are placed in the project directory.

Usage
	1.	Start the server:
    node file-server.js
    	2.	Open your browser and navigate to:
        http://localhost:3002
        	3.	To access specific files:
            http://localhost:3002/<filename>
            Project Structure
            Static-File-Server/
│
├── index.html           # Homepage
├── about.html           # About page
├── contact.html         # Contact page
├── server.js            # Node.js server script
└── README.md            # Project documentation