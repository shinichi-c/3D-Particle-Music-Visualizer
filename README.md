
<img width="1080" height="2261" alt="Screenshot_20251005-195832_Google" src="https://github.com/user-attachments/assets/86c24cb1-3636-4eb6-86c3-01f0fd081bfa" />
<img width="1080" height="2261" alt="Screenshot_20251005-195836_Google" src="https://github.com/user-attachments/assets/19c588c0-1323-4ef0-926e-c995ae31c2c4" />
<img width="1080" height="2261" alt="Screenshot_20251005-195841_Google" src="https://github.com/user-attachments/assets/0212f8a0-95d6-4ac7-9d2e-751a400c2b1d" />
<img width="1080" height="2261" alt="Screenshot_20251005-195844_Google" src="https://github.com/user-attachments/assets/980a46c7-207b-44cc-8726-a2fdf2bc40c2" />
<img width="1080" height="2261" alt="Screenshot_20251005-195858_Google" src="https://github.com/user-attachments/assets/78043578-fcf0-4faf-993e-ce409f953c33" />
<img width="1080" height="2261" alt="Screenshot_20251005-195903_Google" src="https://github.com/user-attachments/assets/46bf9fc8-52de-43dc-ac0a-8bfd155803d0" />
<img width="1080" height="2261" alt="Screenshot_20251005-195908_Google" src="https://github.com/user-attachments/assets/04bda016-f2ad-442c-932d-5725ad9f7a0c" />

# 3D-Particle-Music-Visualizer

A responsive, single-file web application that visualizes audio data in real-time using a dynamic 3D particle system built with Three.js and Tone.js. The application includes a clean, mobile-optimized control panel and a modern status bar.

# 🚀 Features

Dynamic 3D Environment: A large-scale particle system (10,000 particles) reacts intelligently to music analysis, creating complex motion and color shifts.

Audio Reactivity: Particles are influenced by three audio bands:

Bass: Triggers outward "explosions" and increased repulsion.

Mid-Range: Creates general turbulence and jitter.

High-Frequency: Controls particle speed and color pulsing for high-energy effects.

Mobile-Optimized Controls: A modern, collapsible control panel for adjusting visualization settings, volume, and particle size.

Flexible Audio Input: Start a synthetic, internal beat or upload your own audio file (MP3, WAV, etc.) for visualization.

Intuitive Camera: Control the 3D scene camera using mouse drag/swipe for rotation and mouse wheel/pinch-to-zoom for distance.

Smart Status Bar (NEW):

Displays current FPS and Time.

Battery Status Sync: The color of the FPS and Time display dynamically matches the color of the battery percentage (e.g., Red when battery is low, Green when charging).

# 🛠️ Technology Stack

This project is contained entirely within a single index.html file, leveraging browser capabilities and lightweight external libraries:

HTML5 / CSS3: Base structure and custom styling.

Tailwind CSS (via CDN): Used for fast, responsive, and aesthetic UI components.

Three.js (r128): Used for 3D scene rendering and particle system management.

Tone.js (v14): Used for high-performance audio processing, FFT analysis, and synthetic sound generation.

Vanilla JavaScript: Core application logic and DOM manipulation.

# 💻 How to Run

Since this is a single, self-contained HTML file (visualizer.html), no build steps or dependencies are required.

Clone the repository or download the visualizer.html file.

Open visualizer.html directly in any modern web browser (e.g., Chrome, Firefox, Safari).

Usage

Controls: The control panel appears in the center by default. Use the toggle button at the bottom center of the screen to show/hide the panel.

Start/Upload: Press "Start Synthetic Beat" to begin the visualization with an internal rhythm, or "Tap to Upload Music" to load your own track.

Interact: Once visualization begins, use touch or mouse:

Drag/Swipe: Rotate the camera around the particle system.

Scroll/Pinch: Zoom in and out.

Adjust: Use the quick toggles and sliders to modify the visualization effects, color themes, and particle behavior in real-time.
