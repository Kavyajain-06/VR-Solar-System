# VR-Solar-System
# 🌌 VR Solar System with A-Frame

An interactive **3D Solar System experience built for the web using A-Frame**. This project explores how browser-based virtual reality can be created using HTML and A-Frame's entity-component system.

The project was built as part of a **Codédex project** to learn the fundamentals of creating immersive 3D experiences for the web.

## ✨ Features

* 🌞 3D Sun and all **8 planets**
* 🪐 Textured celestial bodies
* 🌌 Space/galaxy environment
* 🔄 Animated planetary motion
* 🕶️ Browser-based VR experience
* 🖱️ Desktop interaction and navigation
* 🌐 Runs directly in the browser
* 📱 Designed with WebXR-compatible experiences in mind

## 🛠️ Tech Stack

* **HTML5**
* **A-Frame**
* **JavaScript**
* **WebXR**
* **3D Assets / Planet Textures**

A-Frame allows 3D and VR scenes to be created directly within HTML using elements such as `<a-scene>`, making it possible to build interactive VR experiences without setting up a complex development environment.

## 📂 Project Structure

```text
VR-Solar-System/
│
├── index.html
├── images/
│   ├── sun.*
│   ├── mercury.*
│   ├── venus.*
│   ├── earth.*
│   ├── mars.*
│   ├── jupiter.*
│   ├── saturn.*
│   ├── uranus.*
│   ├── neptune.*
│   └── ...
│
└── README.md
```

## 🎮 How to Run

### 1. Clone the repository

```bash
git clone <your-repository-link>
```

### 2. Open the project

Navigate into the project folder:

```bash
cd VR-Solar-System
```

### 3. Run the project

Since this is a browser-based A-Frame project, you can open the HTML file using a local development server.

For example, using **VS Code Live Server**:

1. Open the project in VS Code.
2. Install the **Live Server** extension.
3. Right-click `index.html`.
4. Select **Open with Live Server**.
5. Open the provided localhost URL in your browser.

## 🧠 What I Learned

Through this project, I learned the basics of:

* Creating 3D scenes in the browser
* Working with **A-Frame**
* Understanding A-Frame's entity-component architecture
* Positioning and transforming 3D objects
* Applying textures to 3D objects
* Creating animations in a 3D environment
* Working with browser-based VR and WebXR concepts
* Building an interactive experience using HTML

## 🔍 Key Concepts

### A-Frame Scene

The `<a-scene>` acts as the container for the 3D world. A-Frame takes care of much of the underlying 3D and WebXR setup.

### Entities and Components

Objects in the scene are represented using entities and components. This makes it possible to compose objects by attaching properties such as position, rotation, geometry, material, and animation.

### WebXR

A-Frame provides support for WebXR-enabled experiences, allowing the same project to be explored through compatible browsers and VR devices.

## 📚 Reference

This project was created while following the **Codédex – Create a VR Solar System with A-Frame** project.

🔗 [Codédex Project](https://www.codedex.io/projects/create-a-vr-solar-system-with-a-frame)

Additional reference:

* [A-Frame Documentation](https://aframe.io/docs/)

## 🌱 Future Improvements

Some improvements I could add in the future:

* Add information panels for each planet
* Add interactive planet selection
* Add realistic relative planet sizes and distances
* Add more detailed planetary animations
* Add sound effects or background audio
* Improve VR controller interactions
* Add additional celestial objects such as moons and asteroids

---

**Built with 🌌 A-Frame + HTML**
