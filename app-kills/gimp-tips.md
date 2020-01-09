# 克隆工具

关键词：克隆 去水印

快捷工具栏中克隆工具图标 或 菜单`工具->绘画工具->克隆`

1. 选择克隆工具

   可在右侧工具栏选项卡的工具选项中调整克隆工具各项参数。

2. 在图片上选择要克隆的区域，按下<kbd>Ctrl</kbd>，并鼠标点击。

   被选择的克隆区域将以虚线标出

3. 在目标区域上按住鼠标左键涂抹，将克隆的图像涂抹到该目标区域。

# 图像缩放

关键词：缩放

菜单中`图像->缩放图像`

- 图像大小

  - 点击锁链图标，切换宽度和高度的关联性（分辨率同理）

    宽度高度不关联时，调整其中一个值，不会使另一个值等比例改变。

- 质量插值

  缩放图像会重新计算像素，不同的计算手段需要不同的时间和图像质量。不同插值选项：

  - None(无)：没有新的计算，只是简单的放大像素。
  - Linear(线性)：简单低质量的计算，计算过程很快，对于大图像比较适用。
  - Cubic(立方)：从相邻的属性和颜色计算产生新的像素，质量较好。
  - NoHalo/LoHalo：Halo是通过插值产生伪阴影。
    - LoHalo使用场景：缩小图像，图像包含文本或文本类对象；重要区域只有少数不同的颜色。
    - NoHalo使用场景：放大、旋转、透视等。

  参看gimp手册中**Transform Tools**部分。

# 旋转图片

`工具->变换工具->旋转`

# 测量工具

ctrl竖值

alt水平

角度测量：按住shift不放，使用光标画角

按住alt不放 可以拖动画出的角

# 色阶

调整图像的阴影、中间调和高光的强度级别，校正图像的色调范围和色彩平衡。

菜单中`颜色->色阶`

色阶中的`曲线`（或在菜单中选择`颜色->曲线`）显示了图像色彩亮度值的分布

# 闭合路径选择区域

1. 点击路径最后一段的终点，按住<kbd>Ctrl</kbd>不松开，点击路径第一段的起点，整个路径形成闭合区域。
2. <kbd>Shift</kbd> <kbd>v</kbd> 选择该闭合区域。