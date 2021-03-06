﻿AlbertRender
============

特点：
* 方便的场景编辑、材质编辑功能
* 支持过程式纹理、层级组合式纹理
* 类似Unity中的基于组件的构架
* 支持 .fbx .obj .3ds .dae .ase 等常见的3D模型格式，支持 .vox .vol 两种体素文件格式
* 可以基于输入的函数表达式创建模型及体积区域
* 支持蒙皮骨骼动画
* 实时预览&编辑状态：
  使用D3D11 + 延迟渲染 + 基于物理的shader + ShadowMap + 环境光照明/基于图像的照明(IBL) + SSR + SSAO + HDR + FXAA
* 离线渲染：
  目前支持环境遮挡渲染、光线追踪渲染、路径追踪渲染，支持各种不同的BSDF 及其组合，支持法线贴图、景深、面光源/软阴影、KD-Tree加速以及体积区域渲染
* BSDF重要性采样、多重重要性采样
* 支持64位

进行中:
* 多层材质及相应的编辑器
* 次表面散射

计划：
* 双向路径追踪
* MLT
* 光子映射
* 分布式渲染
* 移植到GPU上

![github](https://raw.githubusercontent.com/wmesci/AlbertRender/master/image.png "实时预览")
![github](https://raw.githubusercontent.com/wmesci/AlbertRender/master/image0.png "实时预览")
![github](https://raw.githubusercontent.com/wmesci/AlbertRender/master/image1.png "")
![github](https://raw.githubusercontent.com/wmesci/AlbertRender/master/image2.png "")
![github](https://raw.githubusercontent.com/wmesci/AlbertRender/master/image3.png "")
![github](https://raw.githubusercontent.com/wmesci/AlbertRender/master/image4.png "")
![github](https://raw.githubusercontent.com/wmesci/AlbertRender/master/image5.png "")
![github](https://raw.githubusercontent.com/wmesci/AlbertRender/master/image6.png "")

