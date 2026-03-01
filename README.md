[![GitHub followers](https://img.shields.io/github/followers/wxzen?style=social)](https://github.com/wxzen)

✨ Fullstack Web Developer | 热爱开源 | 构建实用的工具

---

## 🛠️ 职业技能

**前端**  
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Vue](https://img.shields.io/badge/-Vue.js-4FC08D?style=flat-square&logo=vue.js&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Cesium](https://img.shields.io/badge/-Cesium-6CB4EE?style=flat-square&logo=cesium&logoColor=white)
![Three.js](https://img.shields.io/badge/-Three.js-000000?style=flat-square&logo=three.js&logoColor=white)

**后端**  
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=java&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)

**数据库 & 工具**  
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

## 📂 空窗期项目与实践（2025.03 - 2026.03）

> 利用这段集中时间，深入底层图形渲染、算法与GIS技术，完成了多个自研项目与技术攻关。

---

### 1. 🚀 CesiumNative + OpenGL 3DTiles 渲染器

![3DTiles渲染](assets/images/cesium-opengl-3dtiles.png)
![TMS瓦片椭球体](assets/images/cesium-opengl-ellipsoid.png)

**简介**  
两周内完成 `cesium-native` + OpenGL 3.3 + ImGui 集成，实现 3DTiles 和椭球体渲染。弥补了工作期间未完成的自研项目，并深入掌握了 OpenGL 渲染管线及图形底层技术。

**技术栈**  
![OpenGL](https://img.shields.io/badge/-OpenGL-5586A4?style=flat-square&logo=opengl&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Cesium](https://img.shields.io/badge/-Cesium-6CB4EE?style=flat-square&logo=cesium&logoColor=white)

**🔗 [在线演示](https://www.bilibili.com/video/BV1hURqYTEQy/)**

---

### 2. 📊 HelloVulkan —— Vulkan 学习与封装

![HelloVulkan](assets/images/hello-vulkan.png)

**简介**  
系统学习 Vulkan 官方教程，封装 glb/obj 模型渲染器，掌握显示控制与多管线配置。作为 Web 前端开发者，借此拓展底层图形知识，为后续高性能图形应用打下基础。

**技术栈**  
![Vulkan](https://img.shields.io/badge/-Vulkan-AC4E2E?style=flat-square&logo=vulkan&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)

**🔗 [GitHub 仓库](https://github.com/wxzen/HelloVulkan.git)**

---

### 3. 🧠 算法功底强化：刷题与笔记

**简介**  
针对业务开发中算法短板，集中巩固基础数据结构与算法，刷题百余道（OD机试、LeetCode 热题100、牛客华为题），产出数百篇笔记。建立 BFS/DFS、图论、二分、动态规划等解题思路，顺利通过 OD 算法机试，显著提升了代码能力。

**技术栈**  
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![算法](https://img.shields.io/badge/-算法-007ACC?style=flat-square&logo=leetcode&logoColor=white)

**📝 [OD机试75题笔记](https://blog.csdn.net/xwstudysoft/article/details/148288599)  
📝 [LeetCode热题100笔记](https://blog.csdn.net/xwstudysoft/article/details/150487826)**

---

### 4. 📖 虚拟地球引擎设计（C++重构）

**简介**  
精读《虚拟地球三维引擎设计》，用 C++20 重构书中 C# 案例，重点研究渲染器架构、椭球体网格、浮点误差与地形渲染技术。同时复习了协程、智能指针、多线程并发等现代 C++ 特性。

**技术栈**  
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![OpenGL](https://img.shields.io/badge/-OpenGL-5586A4?style=flat-square&logo=opengl&logoColor=white)

**📝 [学习笔记专栏](https://blog.csdn.net/xwstudysoft/category_12982183.html)**

---

### 5. 🖼️ 四叉树+LOD 高分辨率图片渲染

![四叉树LOD演示](assets/images/quatree_lod_demo.gif)

**简介**  
针对公司项目中 Canvas 渲染 4K+ 图片卡顿的问题，研究并实现基于四叉树 + LOD 的动态分辨率技术，使 Canvas 视口可流畅渲染 8K 以上图片。解决了实际业务痛点，并深入理解空间索引与 GPU 采样优化。

**技术栈**  
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![四叉树](https://img.shields.io/badge/-四叉树-4B8BBE?style=flat-square)


---

### 6. 🔗 拓扑图编辑器正交连线算法

![拓扑连线](assets/images/topo-connetion.gif)

**简介**  
借鉴 DrawIO 等编辑器，攻克拓扑图正交连线与自动避障难题。采用路口路由算法生成离散点，结合 A* 与 Dijkstra 算法计算最短路径，并通过算法可视化调试解决几何误差。实现了可复用的正交连线模块，提升了图编辑交互体验。

**技术栈**  
![SVG](https://img.shields.io/badge/-SVG-FFB13B?style=flat-square&logo=svg&logoColor=black)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![图论](https://img.shields.io/badge/-图论-2C8EBB?style=flat-square)

**📝 [技术笔记](https://blog.csdn.net/xwstudysoft/article/details/157542583)**

---

### 7. 🌍 火星地形四叉树可视化系统

![地形四叉树](assets/images/terrain_quadtree.gif)

**简介**  
基于 `gdal` 处理火星高程数据（Mars_HRSC_MOLA_BlendDEM），构建 LOD 金字塔与切片架构，使用 Three.js + 四叉树实现 Web 端全球地形渲染。实现了等距/正射投影切换、着色方案、瓦片并发加载（PriorityQueue + Web Worker）、极地空洞修正及地理标注。该项目为大型 GIS 可视化应用积累了完整经验。

**技术栈**  
![Three.js](https://img.shields.io/badge/-Three.js-000000?style=flat-square&logo=three.js&logoColor=white)
![Vue.js](https://img.shields.io/badge/-Vue.js-4FC08D?style=flat-square&logo=vue.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![GDAL](https://img.shields.io/badge/-GDAL-5CAE58?style=flat-square)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)

**📝 [开发笔记](https://blog.csdn.net/xwstudysoft/article/details/157645035)**

---

## 📬 联系我

- 邮箱：[xuwzen@outlook.com](mailto:xuwzen@outlook.com)

---

⭐️ 如果我的项目对你有帮助，欢迎点个 star！