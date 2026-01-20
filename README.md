# CG_Real_time_fluid_simulation

## 框架：

我们使用了NKU的Fluid Simulation System

[Fan-DH/NKU_CG_FluidSim: 计算机图形学](https://github.com/Fan-DH/NKU_CG_FluidSim)

## 实现：2DEulerian&3DEulerian

### 2DEulerian：

stable fluids： advection + Forces + projection

我们使用了Advection-Reflection来加强细节，但纯CPU的运行下帧率太低，成本太大导致最终效果仅有一帧

### 3DEulerian：

在GPU上实现stable fluids实现了BFECC增强细节

详细细节见[report](report\team16_report.pdf)

### **Result：**

[demo](report\demo_eulerian_3d.mkv)

## Author：

[liquan2003 (李泉)](https://github.com/liquan2003)

[JerryChen1125 (Jerry Chen)](https://github.com/JerryChen1125)
