# 26思政科研项目：生物启发的无人机具身智能控制与自主导航
## 项目概述

本课题面向具身智能与仿生机器人研究，学生将结合仿真平台与真实无人机系统，探索具身智能、强化学习、自主导航与脑机接口等前沿方向。

目标是基于Crazyflie平台，拆分避障、导航、归巢、编队、任务执行等能力，构建实时低资源智能系统。

## 主要方向

1. 生物启发感知与自主导航
2. 智能控制与群体协同
3. 脑机接口与数字孪生

## 方向一：生物启发感知与自主导航
围绕昆虫、鸟类等生物的感知与导航机制，研究无人机在复杂环境中的自主飞行能力，包括：

- 生物启发避障导航（Optic Flow、Looming、LGMD等）

- 视觉语言导航（Vision-Language Navigation）

## 方向二：智能控制与群体协同

围绕学习驱动的控制与多机协同决策，研究无人机自主学习与群体智能，包括：

- 强化学习自主飞行与穿门竞速

- 多无人机群体智能与协同控制

## 方向三：脑机接口与数字孪生

围绕人机协同与智能体训练，研究脑信号控制和虚实融合系统，包括：

- 脑机接口（BCI）控制无人机

- Crazyflie数字孪生与Sim2Real迁移

## 需要学习的基础知识

- 仿真：Mujoco平台
- 真机：Crazyflie
- 嵌入式：控制器、通信、烧录、底层接口等
- 运控算法：闭环调节、强化学习

## 学习资料

### 相关论文（不分先后，凭兴趣阅读）

> Zhang, J., Yu, X., & Lin, Y. (2026). Rethinking Occlusion Modeling for UAV Tracking. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (pp. 13563-13573).

> Patil, A., Singh, M., Maradana, U. G., & Sanket, N. J. (2026). MinNav: Minimalist Navigation Using Optical Flow For Active Tiny Aerial Robots. arXiv preprint arXiv:2606.07813.

> Zheng, H., Chen, Z., Fu, Y., Yang, M., & Qin, T. (2026). SCAN-Planner: Spatial Collision-Aware Local Planning for Route-Guided Long-Range Quadruped Navigation. arXiv preprint arXiv:2606.19555.

>R. J. Bouwmeester, F. Paredes-Vallés and G. C. H. E. de Croon, "NanoFlowNet: Real-time Dense Optical Flow on a Nano Quadcopter," 2023 IEEE International Conference on Robotics and Automation (ICRA), London, United Kingdom, 2023, pp. 1996-2003, doi: 10.1109/ICRA48891.2023.10161258. keywords: {Semantic segmentation;Microprocessors;Machine learning;Rendering (computer graphics);Real-time systems;Hardware;Optical flow},

>Klapoetke, N., Nern, A., Peek, M. et al. Ultra-selective looming detection from radial motion opponency. Nature 551, 237–241 (2017). https://doi.org/10.1038/nature24626

>R. Zou, M. Cannici and D. Scaramuzza, "Event-Aided Sharp Radiance Field Reconstruction for Fast-Flying Drones," in IEEE Transactions on Robotics, vol. 42, pp. 1591-1606, 2026, doi: 10.1109/TRO.2026.3672537.keywords: {Image reconstruction;Three-dimensional displays;Cameras;Robots;Trajectory;Neural radiance field;Drones;Deblurring;Accuracy;Robot sensing systems;3-D reconstruction;event cameras;high-speed aerial robotics;motion deblurring;neural radiance fields (NeRFs)},

>NanoBench: A Multi-Task Benchmark Dataset for Nano-Quadrotor System Identification, Control, and State Estimation. https://doi.org/10.48550/arXiv.2603.09908

>Mapless Collision-Free Flight via MPC using Dual KD-Trees in Cluttered Environments. https://doi.org/10.48550/arXiv.2503.10141

>MonoNav: MAV Navigation via Monocular Depth Estimation and Reconstruction. https://doi.org/10.48550/arXiv.2311.14100

>OppLoD: the Opponency based Looming Detector, Model Extension of Looming Sensitivity from LGMD to LPLC2. https://doi.org/10.48550/arXiv.2302.10284

### 仿真软件学习

- 可参考B站视频，例如：<https://www.bilibili.com/video/BV1YnLP6uEeZ/>

### 强化学习运动控制算法学习

- <https://github.com/google-deepmind/mujoco_playground>
- <https://www.bilibili.com/video/BV1znLy6hEGR/>

### Crazyflie官方文档

- <https://www.bitcraze.io/>

### 嵌入式硬件

- 参考`./hardware`，自行结合视频、实物学习

## 仓库文件

- `./bitcraze_crazyflie_2`：Crazyflie仿真模型与场景，可导入Mujoco运行
- `./hardware`：硬件学习资料，包括焊接、PCB、stm32、无人机等

## 学习情况记录表

【腾讯文档】仿生无人机项目学习进度表
- https://docs.qq.com/sheet/DZHdnaVhaVFVCcXNs