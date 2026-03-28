[![GitHub followers](https://img.shields.io/github/followers/wxzen?style=social)](https://github.com/wxzen)

✨ Fullstack Web Developer | Open Source Enthusiast | Building Practical Tools

---

## 🛠️ Tech Stack

**Frontend**  
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Vue](https://img.shields.io/badge/-Vue.js-4FC08D?style=flat-square&logo=vue.js&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Cesium](https://img.shields.io/badge/-Cesium-6CB4EE?style=flat-square&logo=cesium&logoColor=white)
![Three.js](https://img.shields.io/badge/-Three.js-000000?style=flat-square&logo=three.js&logoColor=white)

**Backend**  
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=java&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)

**Database & Tools**  
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

## 📂 Featured Projects

---
### 1. 🔗 Orthogonal Edge Routing Algorithm for Topology Editor

![Topology Connection](assets/images/topo-connetion.gif)

**Description**  
Inspired by editors like DrawIO, this project tackles orthogonal edge routing and automatic obstacle avoidance. It generates discrete points using a grid-based approach, computes shortest paths with A* and Dijkstra, and uses algorithm visualization to debug geometric errors. The result is a reusable orthogonal edge routing module that enhances interactive graph editing.

**Tech Stack**  
![SVG](https://img.shields.io/badge/-SVG-FFB13B?style=flat-square&logo=svg&logoColor=black)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Graph Theory](https://img.shields.io/badge/-Graph%20Theory-2C8EBB?style=flat-square)

**📝 [Technical Notes](https://blog.csdn.net/xwstudysoft/article/details/157542583)**

---

### 2. 🌍 Mars Terrain Quadtree Visualization System

![Terrain Quadtree Plane](assets/images/terrain_quadtree.gif)
![Terrain Quadtree Sphere](assets/images/terrain_sphere.gif)

**Description**  
Processes Mars elevation data (Mars_HRSC_MOLA_BlendDEM) with GDAL, builds a LOD pyramid and tile structure, and renders global terrain in the browser using Three.js + quadtree. Features include orthographic/perspective projection switching, custom shading, concurrent tile loading (PriorityQueue + Web Worker), pole hole correction, and geospatial annotations. This project provides comprehensive experience for large‑scale GIS visualization applications.

**Tech Stack**  
![Three.js](https://img.shields.io/badge/-Three.js-000000?style=flat-square&logo=three.js&logoColor=white)
![Vue.js](https://img.shields.io/badge/-Vue.js-4FC08D?style=flat-square&logo=vue.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![GDAL](https://img.shields.io/badge/-GDAL-5CAE58?style=flat-square)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)

**📝 [Development Notes](https://blog.csdn.net/xwstudysoft/article/details/157645035)**
**📽️ [Video Demo](https://www.bilibili.com/video/BV1YXAqzpEEN/?spm_id_from=333.1387.list.card_archive.click&vd_source=3434557e40e288ad9d728f42946fbf4b)**

---
### 3. 🖼️ High‑Resolution Image Rendering with Quadtree + LOD

![Quadtree LOD Demo](assets/images/quatree_lod_demo.gif)

**Description**  
To address performance issues with Canvas rendering 4K+ images in a company project, this solution implements dynamic resolution using a quadtree + LOD approach. It enables smooth rendering of images larger than 8K in a Canvas viewport, effectively solving a real‑world business bottleneck while deepening understanding of spatial indexing and GPU sampling optimization.

**Tech Stack**  
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![Quadtree](https://img.shields.io/badge/-Quadtree-4B8BBE?style=flat-square)

---

### 4. 📊 HelloVulkan — Vulkan Learning & Wrapper

![HelloVulkan](assets/images/hello-vulkan.png)

**Description**  
Systematically studied the official Vulkan tutorial and wrapped a glb/obj model renderer, gaining control over presentation and multiple pipelines. As a frontend developer, this project expanded my knowledge of low‑level graphics, laying a foundation for future high‑performance graphics applications.

**Tech Stack**  
![Vulkan](https://img.shields.io/badge/-Vulkan-AC4E2E?style=flat-square&logo=vulkan&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)

**🔗 [GitHub Repository](https://github.com/wxzen/HelloVulkan.git)**

---

### 5. 🚀 CesiumNative + OpenGL 3DTiles Renderer

![3DTiles Rendering](assets/images/cesium-opengl-3dtiles.png)
![TMS Tiles Ellipsoid](assets/images/cesium-opengl-ellipsoid.png)

**Description**  
Integrated `cesium-native` with OpenGL 3.3 and ImGui in two weeks, implementing 3DTiles and ellipsoid rendering. This project filled a gap from previous work and provided deep insight into the OpenGL pipeline and underlying graphics technologies.

**Tech Stack**  
![OpenGL](https://img.shields.io/badge/-OpenGL-5586A4?style=flat-square&logo=opengl&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Cesium](https://img.shields.io/badge/-Cesium-6CB4EE?style=flat-square&logo=cesium&logoColor=white)

**🔗 [Live Demo](https://www.bilibili.com/video/BV1hURqYTEQy/)**

---

### 6. 🎮 godot-3dtiles — Godot Engine 3DTiles Plugin

![godot-3dtiles](godot-3dtiles.png)

**Description**  
Integrates Cesium Native into the Godot engine, enabling loading and rendering of 3DTiles data. Using GDExtension, the plugin wraps the underlying C++ interfaces to provide high‑precision 3D geospatial data visualization within Godot.

**Tech Stack**  
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![CMake](https://img.shields.io/badge/-CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![Godot](https://img.shields.io/badge/-Godot-478CBF?style=flat-square&logo=godotengine&logoColor=white)

**🔗 [GitHub Repository](https://github.com/wxzen/godot-3dtiles)**

---

### 7. 🚦 3D Traffic Intersection Simulation

![Intersection Simulation](traffic_simulation.gif)

**Description**  
A dynamic simulation system for urban traffic intersections built on real GIS data. Implements vehicle path planning, traffic light control logic, and multi‑view navigation, suitable for traffic scenario analysis and smart city presentations.

**Tech Stack**  
![Vue.js](https://img.shields.io/badge/-Vue.js-4FC08D?style=flat-square&logo=vue.js&logoColor=white)
![Three.js](https://img.shields.io/badge/-Three.js-000000?style=flat-square&logo=three.js&logoColor=white)
![Tween.js](https://img.shields.io/badge/-Tween.js-FF6C37?style=flat-square)
![Turf.js](https://img.shields.io/badge/-Turf.js-3AAE6B?style=flat-square)
![Mapbox GL](https://img.shields.io/badge/-Mapbox%20GL-000000?style=flat-square&logo=mapbox&logoColor=white)
![GeoServer](https://img.shields.io/badge/-GeoServer-2C8EBB?style=flat-square)

---

## 📬 Contact Me

- Email: [xuwzen@outlook.com](mailto:xuwzen@outlook.com)