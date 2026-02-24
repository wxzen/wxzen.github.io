# 👋 Hi, 我是 David

[![GitHub followers](https://img.shields.io/github/followers/wxzen?style=social)](https://github.com/wxzen)


✨ Fullstack Web Developer | 热爱开源 | 构建实用的工具

---

## 🛠️ 职业技能

**前端**
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vue](https://img.shields.io/badge/-Vue.js-4FC08D?style=flat-square&logo=vue.js&logoColor=white)

**后端**
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=java&logoColor=white)

**数据库 & 工具**
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

## 📂 2025-03~2026-03 空窗期我做了哪些事？

### 1. 🚀 CesiumNative+OpenGL 3DTiles渲染器
![3DTiles渲染](assets\images\cesium-opengl-3dtiles.png) 
![TMS瓦片椭球体](assets\images\cesium-opengl-ellipsoid.png)

**简介**： 我花了约两周时间完成cesium-native+OpenGL3.3+imgui的集成，实现了3DTiles和椭球体的渲染效果，工作期间未完成的自研项目，失业后完成了，也熟悉了OpenGL渲染管线和图形渲染开发相关底层技术原理。 
**技术栈**：OpenGL、cesium-native、Dear ImGUI  
**🔗 [在线演示](https://www.bilibili.com/video/BV1hURqYTEQy/?vd_source=3434557e40e288ad9d728f42946fbf4b) 

---

### 2. 📊 HelloVulkan
![项目截图](assets\images\hello-vulkan.png)  
**简介**：vulkan toturial学习笔记及案例演示。Vulkan很复杂，花了好几个月学习官网教程，封装了glb、obj模型渲染器，了解显示控制和多管线配置。做Web前端开发用WebGL更多些，这个更多是拓展知识面。如果后续要自研高性能桌面端图形渲染应用，可能会继续深耕Vulkan/Direct12 API。 
**技术栈**：Vulkan、Dear ImGUI 
**🔗 [GitHub 仓库](https://github.com/wxzen/HelloVulkan.git)**

---

### 3. 📱 程序员数据结构和算法功底训练
**简介**：个人工作更多是从事业务应用开发，数据结构和算法这块用得不多，只熟悉基础链表、哈希表、递归、树的递归遍历等算法实现，完全满足不了现在某些IT企业技术面试手撕算法题的水平要求，利用失业期间时间重新巩固复习了基础算法，刷了百余道OD机试题和Leetcode题目、牛客华为机试题，写了几百篇算法题笔记，建立基本的BFS/DFS思路、图论、二分、动态规划等思路，通过了OD的算法机试，总算入门了，这对个人代码能力是一个提升。在后续的一些较为复杂的项目开发中也用上了一些算法！后续长期根据笔记进行巩固复习，确保代码能力保持上升趋势。
**技术栈**：JavaScript、算法于数据结构  
**🔗 [OD机试题75道汇总笔记](https://blog.csdn.net/xwstudysoft/article/details/148288599) 
**🔗 [Leetcode热题100道汇总笔记](https://blog.csdn.net/xwstudysoft/article/details/150487826) 

---

### 4. 🧰 阅读《虚拟地球三维引擎设计》及配套C#源码、C++重构代码案例
**简介**：由于工作中参与了很多GIS项目开发，有二维地图，也有三维地图，对地理数据可视化也比较感兴趣，所以利用空档期学习了虚拟地球引擎设计，本书篇幅很长，重点学习了渲染器封装架构设计、椭球体网格技术、浮点误差问题方案，地形渲染技术。由于桌面端图形渲染应用开发广泛使用性能更好的C++语言，所以也花了不少时间用C++重构案例的C#代码，顺便复习C++20标准、协程模型、智能指针、多线程并发。
**技术栈**：C++、C#、OpenGL  
**🔗 [相关笔记](https://blog.csdn.net/xwstudysoft/category_12982183.html?spm=1001.2014.3001.5482)**

---

### 5. 🧰 四叉树+LOD渲染高分辨图片
![alt text](assets\images\quatree_lod_demo.gif)
**简介**：这个项目也源自实际的公司项目需求，在公司开发的机器人地图编辑器是用canvas负责渲染的，对于4k以上分辨率图片渲染出现卡顿现象，为了快速响应业务需求对图片分辨率降低为2k了，这个并没有从技术手段彻底解决这个问题。通过后续的研究发现canvas渲染原理和svg、div区别很大，4k左右分辨率图片一般直接通过img节点+transform css样式可实现动态GPU纹理采样，解决卡顿问题，如果分辨率达到8k以上还需要其它技术方案。canvas作为视口一般分辨率不能超过4k，否则很卡顿，有很多canvas作为单视口的图形编辑器头做了限制，这是局限性，但是可用通过动态分辨率技术实现在4k以下视口中配合缩放交互操作渲染8k以上的高分辨率图片，这就是空间索引算法四叉树+LOD（细节层次）技术了，这个项目完成了这个效果，解决了以前公司项目中的实际业务需求。
**技术栈**：JavaScript、HTML Canvas、Quadtree 
**🔗 [GitHub 仓库](https://github.com/你的用户名/项目名)**

---

### 6. 🧰 拓扑图编辑器正交连线技术研究
![拓扑图连线](assets\images\topo-connetion.gif)  
**简介**：类似 DrawIO、ProcessOn 这类拓扑图编辑器的拓扑结点连线交互功能。在公司开发机器人地图编辑器曾实现了绘制拓扑图功能，但正交连线功能有些复杂，实现效果一般，不好用，所以公司还是用在线的编辑器绘制复杂的拓扑图导出数据再导入到机器人地图上。所以这个功能是对曾经做过的项目功能进行技术升级改造和优化。通过研究drawio编辑器底层源码和查阅技术资料，确定了可用图论算法解决正交连线和自动避障问题。我运用路口路由算法计算离散点生成正交线段集合+A*训练启发式算法+Dijkstra算法（兜底最短路径）实现了较通用的正交连接代码功能，通过算法可视化进行辅助调试，解决繁杂的浮点误差和几何判断问题，最终实现了可用效果，后续可根据业务需要优化实时航向预判等锦上添花功能。
**技术栈**：HTML、CSS、SVG、图论和几何算法
**🔗 [相关笔记](https://blog.csdn.net/xwstudysoft/article/details/157542583)**

---

### 7. 🧰 地形四叉树案例
![地形四叉树](assets\images\terrain_quadtree.gif)  
**简介**：在项目5的基础上为了深入探讨四叉树数据结构的强大之处，尝试扩展到三维应用，从ugsg官网下载火星全球数字高程数据文件Mars_HRSC_MOLA_BlendDEM_Global_200mp_v2.tif，尝试制作一个火星全球地形可视化系统。首先尝试过用QGIS可视化高程，结果三维高程无法显示，只能看到二维的平面灰度图。为了深入了解高程数据格式和渲染技术，我决定用空间库gdal分析tif文件，然后了解坐标系，添加LOD金字塔，定义切片架构，然后用ThreeJS+四叉树完成tif数据在web端的渲染。后续还添加了等距投影和正射投影的切换功能，多种着色方案，四叉树网格分裂过程可视化，使用优先级队列控制并发加载瓦片数，通过webworker优化瓦片加载速度，防止阻塞主线程，实现类似3DTiles的瓦片替换策略实现无缝加载。通过分析切片数据，重采样tif图片生成均匀切片解决球体投影出现的极地空洞和东西半球接缝问题。获取火星地理命名数据集，实现地理标注功能。
>这个项目有什么用？
通过这个项目我熟悉了四叉树无缝加载超大分辨率图片技术及各种无缝优化技术，熟悉地理坐标系投影转换技术，地理坐标配准，熟悉 gdal 空间库的基本使用。完全可以胜任一些大型GIS项目的开发工作，GIS和图形渲染是Web前端开发的垂直领域，是技术能力和综合能力的拓展。后续我可以基于此项目经验开发火星模拟器等类似复杂应用或游戏。

**技术栈**：QGIS、gdal、Python、ThreeJS、Vue3、TypeScrpt、Quadtree、PriorityQueue
**🔗 [相关笔记](https://blog.csdn.net/xwstudysoft/article/details/157645035)**

---

## 📬 联系我
- 个人网站：[https://你的网站.com](https://你的网站.com)
- 邮箱：[xuwzen@outlook.com](xuwzen@outlook.com)


---

