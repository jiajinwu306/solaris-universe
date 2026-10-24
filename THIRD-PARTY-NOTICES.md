# SOLARIS v1.0.0 第三方资源与许可

本文件记录部署目录中第三方代码与纹理的来源及许可信息。

## Three.js

本项目内联使用 Three.js r186 / npm 包 `three` 0.186.x。

**The MIT License**

Copyright © 2010-2026 three.js authors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

来源：<https://github.com/mrdoob/three.js>

## Solar System Scope 纹理

以下纹理由 Solar System Scope 提供，基于 NASA 影像，按 **CC BY 4.0** 使用：

- 太阳：`2k_sun.jpg`
- 水星：`2k_mercury.jpg`
- 金星：`2k_venus_surface.jpg`
- 地球白昼：`2k_earth_daymap.jpg`
- 火星：`2k_mars.jpg`
- 木星：`2k_jupiter.jpg`
- 土星：`2k_saturn.jpg`
- 土星环：`2k_saturn_ring_alpha.png`
- 天王星：`2k_uranus.jpg`
- 海王星：`2k_neptune.jpg`
- 月球：`2k_moon.jpg`
- 银河背景：`2k_stars_milky_way.jpg`

- 原始发布页：<https://www.solarsystemscope.com/textures/>
- CC BY 4.0 许可：<https://creativecommons.org/licenses/by/4.0/>
- 本项目使用的 2K 镜像说明：<https://github.com/thaisc98/solar-system-3d-threejs>

本部署版本将这些纹理转换为内联 data URL，并作为单文件页面的一部分分发。纹理内容未改变其原始来源归属。

## Three.js 示例纹理 / NASA 公有领域影像

以下地球纹理来自 three.js 示例纹理，原始影像来自 NASA / Visible Earth，属于 NASA 公有领域：

- `earth_lights_2048.png`
- `earth_clouds_1024.png`
- `earth_normal_2048.jpg`
- `earth_specular_2048.jpg`

来源：<https://github.com/mrdoob/three.js/tree/dev/examples/textures/planets>

## 程序化内容

以下内容由项目代码实时生成，不依赖额外图片或模型：

- 银河系、宇宙网、宇宙演化史；
- 双星系碰撞、星系团碰撞；
- 黑洞、吸积盘、引力透镜；
- 星云、恒星诞生、行星形成、超新星；
- 月球局部地形、岩石、月壤纹理；
- 飞船、任务终端、轨迹、HUD；
- 各实验室中的粒子、气体、尘埃和视觉特效。

## 项目代码许可

本发布目录**没有添加项目级开源许可证**。

项目代码的版权与再分发许可需要由项目作者/权利人确认。第三方组件的许可不自动构成对项目代码的授权。

## 未确认事项

- `thaisc98/solar-system-3d-threejs` 是项目文档记录的 2K 纹理镜像；其 README 声明来源于 Solar System Scope 并按 CC BY 4.0 分发。建议在正式公开发布前再次核对该镜像当前许可说明。
- NASA 影像通常属于公有领域，但不构成对 NASA 名称、标识或背书的授权。
- 本文件不构成法律意见。
