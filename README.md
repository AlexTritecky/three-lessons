# Three-Lessons

This project is a part of a series of lessons on using the `three.js` library to create and control 3D graphics in the web browser. In addition to `three.js`, the project utilizes `gsap` for animations, `lil-gui` for a minimal GUI to control your animations, and `vite` as the build tool for a modern development experience.

## Description

`three-lessons` is designed to provide hands-on experience with `three.js`, showcasing how to set up a basic 3D scene, create a red cube, and render it using WebGL. This lesson is a foundation for understanding more complex 3D graphics concepts and animations with `three.js`.

## Project Structure

- `index.html`: The HTML file that hosts the canvas for rendering the 3D scene.
- `style.css`: Contains styles for the webpage.
- `script.js`: The main JavaScript file where the `three.js` scene, camera, and objects are defined and rendered.
- `vite.config.js`: Configuration file for Vite, specifying the root, public directory, server options, build output directory, and other build options.

## Setup

To get started with `three-lessons`, you need to have Node.js installed on your computer. After cloning the project, follow these steps:

1. **Install dependencies**:

```bash
npm install
```

This will install all necessary dependencies, including three, gsap, lil-gui, and vite.

2. **Running the project in development mode:**:

```bash
npm run dev
```

3. **Building the project**

```bash
npm run build
```

## Dependencies
This project leverages several key libraries and tools to facilitate 3D web development and streamline the build process:

`three`: A JavaScript 3D library that simplifies the use of WebGL, enabling the creation of intricate 3D graphics and visualizations directly in the web browser without relying on complex WebGL commands.

`gsap`: The GreenSock Animation Platform (GSAP) is a robust JavaScript library designed for crafting high-performance animations. It provides the power to animate any property of any object, offering unparalleled flexibility and performance in web animations.

`lil-gui`: A minimal, yet powerful graphical user interface (GUI) library that allows for real-time manipulation and control of variables. It's particularly useful for tweaking parameters on the fly, enhancing the development and testing process of animations and visual effects.

`vite`: A modern build tool that significantly improves the frontend development experience. Vite leverages advanced build optimizations to offer instant server start, lightning-fast hot module replacement (HMR), and efficient production builds, making it an excellent choice for modern web projects.

## Configuration
The project is configured to optimize both the development experience and the build process, facilitated by vite.config.js. The configuration is carefully crafted to meet the project's specific needs:

`Root Directory`: The application is served from src/{{`lesson-folder`}}/, establishing this folder as the root directory for development and builds. This setup supports a structured project layout, separating source files from public assets and build artifacts.

`Public Directory`: The static/ folder is designated as the public directory. This adjustment ensures that static assets are correctly served relative to the project's root, facilitating better organization and access to public resources.

`Server Configuration`: The development server is configured to be accessible on the local network, making it easier to test the project across multiple devices. This approach is invaluable for cross-device testing and presentations.

`Build Output`: The output directory for production builds is set to ./dist within the project's root. This choice simplifies deployment processes and ensures a clean separation between source files and deployable assets. Additionally, sourcemaps are enabled for builds, enhancing debugging capabilities by providing a direct link back to the original source code.

These configurations ensure that the project is both developer-friendly and optimized for performance, facilitating an efficient development workflow and a smooth deployment process.
