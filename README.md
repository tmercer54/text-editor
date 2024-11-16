## Description

This Progressive Web Application (PWA) Text Editor is a feature-rich, offline-capable text editor designed to demonstrate advanced front-end concepts like data persistence, modular JavaScript bundling with Webpack, and the use of Service Workers.

The project emphasizes a seamless user experience with multiple layers of data redundancy through IndexedDB, local storage, and browser caching to ensure functionality both online and offline. The app is bundled using Webpack, which generates an HTML file, a manifest, and a Service Worker that caches static assets and pages.

This project aligns with best practices in modern web development, highlighting the power of PWAs and progressive enhancement techniques that ensure the application runs smoothly across various devices and browsers, even in limited connectivity environments.

## Usage

Follow these steps to run the application locally:

1.  Install Dependencies

        npm install

2.  Start the Application

    From the root directory, start the development server:

        npm run start

    This will start both the backend server and client-side application. The server will serve the bundled files from Webpack.

3.  Open in Browser

    Visit `http://localhost:3000` in your browser to access the text editor.
