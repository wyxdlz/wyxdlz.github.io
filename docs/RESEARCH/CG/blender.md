# Blender Notes

Blender是一个开源软件（开源yyds），主要用来做3D模型建模；但实际上它可以做太多事情了。

- [YouTube | Blender Beginner Donut Tutorial](https://www.youtube.com/playlist?list=PLjEaoINr3zgFX8ZsChQVQsuDSjEqdWMAD)
    - 通过教你在Blender里面做甜甜圈来入门Blender
    - 老师非常和蔼

## 1

- 下方是有快捷键提示的
- 渲染：Render > Render Image (F12)
- 旋转画面：触控板滑动
- 平移画面：⇧触控板滑动
- 缩放画面：触控板捏合
- 移动物体：左键选中物体后按 G (grab) + XYZ/⇧XYZ。左键放置，右键取消。
- 旋转物体：R (rotate)
- 缩放物体：S (scale)
- 聚焦一个物体：View > Frame Selected
- 聚焦所有物体：View > Frame All
- 切换视角：View > Viewpoint > Camera / Top / Front / Right
- 切换投影和正交：View > Perspective/Orthographic
- 删除物体：X / fn⌫
- 重命名：双击右上角的名字

## 2 Editing

- sft A 添加物体
    - 刚添加完左下角可以调整参数
    - 不小心点掉了可以 F9（没成功）
- N 打开属性
- ctrl A scale 应用缩放，使得物体的 scale 均为 1。什么都没有改变，但这很重要。
- 让 flat 变为 smooth：右键 Shade Smooth
- 进一步细分曲面：使用 modifier：右下角 span
    - 添加 Subdivision 使得侧面的锯齿消失
    - Levels 在建模的时候自己看选 0 或者 1，渲染的时候只要时间不太长可以调高一些
    - 相当于在不添加 mesh 的情况下让物体看起来好一些
- 左上角可以从 Object Mode 切换为 Edit Mode
    - Tab 可以在两种模式中切换
- 选中一个顶点按 G 可以修改位置
    - sft 可以选中多个点
- O: proportional editing objects
    - 按 O 开启这个模式
    - 选中一个点
    - 按 G 准备拖拽这个点
    - 触控板上下滑动调整圆圈的大小
    - 拖拽这个点，同时会影响到其他的点
- opt S
    - 沿表面的法向方向移动
- 在编辑模式中可以随机选择顶点
- 在 O 的旁边可以选择凸起/凹陷的样式

## 3 Modofiers

- 在正交视图下选中上一半的顶点
    - Toggle X-ray - opt Z 可以直接穿过去选
- sft D 复制
- 上半层是 Icing、其他的是 Donut
- 使用 Wireframe mode 去查看（默认是 Solid mode）
- 右下角 span 添加一个 modifier 叫做 Solidify，相当于把表面沿着法向拉伸成一个固体。在 modifier 的选项中有 offset 表示向法向内或者外，Thickness 表示拉伸的宽度。
    - 调整数值的时候，按住 sft 小幅度调整、按住 ctrl 大幅度调整

## 4 Modeling

TODO https://www.youtube.com/watch?v=R1isb0x4zYw&list=PLjEaoINr3zgFX8ZsChQVQsuDSjEqdWMAD&index=4