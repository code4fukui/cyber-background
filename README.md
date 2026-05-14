# cyber-background

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A sample project demonstrating a cyber-themed particle effect using WebGL 2.0's transform feedback feature. This project is a fork of the [170706_webgl2_feature/transform_feedback](https://github.com/ics-creative/170706_webgl2_feature) repository from ICS MEDIA.

## Preview

This project renders a dynamic system of 100,000 particles. The particles flow in a fluid, vortex-like motion driven by curl and Perlin noise, creating an ever-shifting visual. The colors cycle through a vibrant, neon-hued palette, giving the effect a distinct cyberpunk aesthetic. The camera is interactive, allowing you to orbit around the particle cloud with mouse or touch controls.


![Cyber Background Demo](https://raw.githubusercontent.com/ics-creative/170706_webgl2_feature/master/article/img/screenshot.gif)


## Features

- **WebGL 2.0 Transform Feedback:** Efficiently simulates and updates particle physics entirely on the GPU.
- **Dynamic Particle System:** Manages 100,000 particles, calculating position and velocity each frame.
- **Advanced Noise Algorithms:** Uses Perlin and Curl noise to generate complex, organic fluid motion.
- **Vibrant Shading:** Implements an HSV-to-RGB shader for smooth, cycling neon colors.
- **Interactive 3D Camera:** An orbit controller allows for easy scene navigation via mouse, touch, or keyboard.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) (included with Node.js)

### Installation & Running

1.  Clone the repository:
    ```bash
    git clone https://github.com/your-username/cyber-background.git
    cd cyber-background
    ```

2.  Install dependencies:
    ```bash
    npm install
    ```

3.  Start the development server:
    ```bash
    npm run start
    ```
    This will open the demo in your default browser.

## Technology Stack

- **Rendering:** WebGL 2.0
- **Language:** TypeScript
- **Math Library:** gl-matrix
- **Build Tools:** Gulp, Webpack, and BrowserSync

## Reference

- [Understanding WebGL 2.0 with Samples - The Advantages of WebGL 2.0 Supported by Chrome and Firefox - ICS MEDIA](https://ics.media/entry/16060/)
- [Techniques to Implement Neon Light Effects on Text, Buttons, and Borders Using CSS | COLISS](https://coliss.com/articles/build-websites/operation/css/css-neon-sign-effects.html)

## License

MIT License — see [LICENSE](LICENSE).