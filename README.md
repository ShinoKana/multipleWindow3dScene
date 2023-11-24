## 3d scene spanning multiple windows using three.js and localStorage

A simple example showing how to setup a 3d scene across windows on the same origin using three.js and localStorage. 

This is based on https://github.com/bgstaal/multipleWindow3dScene
---

## Features

- **Multi-Window Synchronization**: Using `localStorage`, the 3D scene's state is synchronized across multiple browser windows.
- **three.js Integration**: Leveraging the power of `three.js` to render 3D graphics.
- **Responsive Design**: The 3D scene adjusts to different window sizes, maintaining its visual consistency.

## Setup

To get started with this project, follow these steps:

### Installation

1. **Clone the Repository:**

   ```bash
   git clone [Your Repository URL]
   cd [Your Project Folder]
   ```

2. **Install http-server:**

   If you don't have `http-server` installed globally, run:

   ```bash
   npm install -g http-server
   ```

### Running the Project

1. **Start the Server:**

   In the project directory, start the server by running:

   ```bash
   http-server
   ```

2. **Open the Application:**

   Open your web browser and navigate to `http://127.0.0.1:8080` or the URL provided in the command line output.

3. **Open Multiple Windows:**

   To fully experience the multi-window setup, open multiple instances of the URL in different windows or tabs.
