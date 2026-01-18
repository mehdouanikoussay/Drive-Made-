# Drive Mad - Web Game

## Overview

This project is a web game titled "Drive Mad," a browser-based game where the player drives a vehicle through tracks filled with obstacles and physics-based challenges. The entire project is compiled into a single `index.html` file, making it directly runnable in any modern web browser.

## Technologies Used

The game relies on a set of advanced technologies to run efficiently in the browser:

*   **WebAssembly (WASM):** The core game logic was built using a high-performance language like C++ or Rust, then compiled to WebAssembly to run at near-native speed.
*   **WebGL:** The game uses WebGL to render 3D graphics directly in the browser.
*   **Emscripten:** It's clear that the Emscripten toolchain was used to port the native codebase (most likely C++) to the web.
*   **HTML/CSS/JavaScript:** These technologies are used to create the user interface, the loading screen, and to glue all the game components together.

## How to Run

1.  **Via a Local Web Server (Recommended):**
    *   Since the game loads its assets (`index.data`) via network requests, the best way to run it is through a local web server to avoid browser security issues (CORS).
    *   Open a terminal in the project folder and run one of the following commands:
        *   **If you have Python 3:** `python -m http.server`
        *   **If you have Node.js:** `npx serve`
    *   Then, open your browser and navigate to `http://localhost:8000` (or the port displayed by the server).

2.  **Direct File Open (May Not Work):**
    *   You can try opening the `index.html` file directly in your browser, but some features might fail due to security restrictions.

## Authors

*   **Original Game Developer:** Martin Magni.
*   **Current Version Owner:** `koussay mehdouani`.
*   
