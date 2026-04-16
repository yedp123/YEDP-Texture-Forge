# TextureForge 3.4 🛠️

<img width="1920" height="919" alt="image" src="https://github.com/user-attachments/assets/14160f61-5474-4e79-885c-eaaf5e41223d" />


**⚠️ Status: Experimental**

TextureForge is a lightweight, single-file HTML/React application for generating, editing, and previewing PBR materials directly in the browser. It's built for rapid, frictionless technical art workflows—no installations, no heavy backend, just drop in an image and start tinkering.

## Features

* **Zero-Dependency Core:** Runs entirely client-side using React, Three.js, and raw Canvas API manipulation.
* **Full PBR Suite Generation:** Automatically derive Normal, Roughness, Ambient Occlusion, Height, Metallic, and Opacity maps from a single base color image.
* **Smart Tiling & Cloning:** Make textures seamless on the fly, or use the manual clone stamp tool to fix specific artifacts.
* **Direct Normal Painting:** Manually raise, lower, or smooth specific areas of your normal map directly in the 2D view.
* **Real-time 3D Preview:** Instantly see your material changes on a plane, cube, or sphere with different HDRI lighting environments.
* **One-Click Export:** Packages all your generated maps into a neat `.zip` file.

## AI Integration & API Keys

TextureForge includes a small "AI Workshop" module for quick ideation:
* **Generate Texture:** Uses [Pollinations.ai](https://pollinations.ai/) to generate base textures from text. **(Free, no API key required).**
* **Smart Settings:** Uses Google's Gemini API to read your prompt and automatically adjust the sliders (Normal Strength, Roughness Contrast, etc.) to match the material type. **(Requires your own Gemini API key).** *Note: The tool is fully functional as a standard PBR generator without ever touching the AI features or inputting an API key.*

## Usage

Since everything is bundled into a single file, usage is as simple as it gets:

1. Download the `TextureForge.html` file.
2. Double-click it to open it in any modern web browser.
3. Import an image (or generate one) and start adjusting your maps.

## Tech Stack

* **UI:** React 18 (via CDN), Tailwind CSS
* **3D:** Three.js (r128)
* **Icons:** Lucide
* **Export:** JSZip

## License

Feel free to fork, modify, and use this in your own pipelines.

