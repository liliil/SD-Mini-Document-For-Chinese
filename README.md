# Substance Designer  Mini Document  For Chinese 
对Susbstance Designer 文档进行简单摘抄翻译。

Substance 常见元素:
- Package ( 包 )： “*.sbs” 工程文件
- Substance( 材质 ): ".sbsar" 最终文件，可被其他软件直接使用。
- Graphs ( 图 )： 用来构建材质的工作区
- Atomic nodes( 原子节点 ): 材质的基本组成节点，用来合成材质
- Graph instance ( 图实例 ): 一张图的实例，可被其他图使用。
- Helpers: 组织文件结构用。


## Node ( 节点 )

在SD中，节点可以被大致分为两类。虽然它们看起来非常相似， 图实由原子节点组成可被重复使用， 原子节点则是“硬编码”的基本节点。
- Atomic Nodes (原子节点)
- Graph Instance ( 图实例)


### Atomic Nodes ( 原子节点 )

- Bitmap( 位图 )
- Blend( 混合 )`
- Blur( 模糊 )
- Channel Shuffle( 通道混合 )
- Curve( 曲线 )
- Directional Blur ( 定向模糊 )
- Directional Warp ( 定向弯曲 )
- Distance ( 距离 )
- Emboss ( 浮雕 )
- FX-Map ( 效果图 )
- Dynamic Gradient  ( 动态梯度 )
- Gradient Map ( 梯度图 )
- Grayscale conversion ( 灰度转换 )
- HSL (色调，饱和， 明度)
- Levels 
- Normal ( 转换normal )
- Pixel Processor ( 像素处理 )
- Sharpen ( 锐化 )
- SVG 
- Text ( 文本 )
- Transform 2D ( 2D 变换 )
- Uniform Color ( 统一颜色 )
- Warp ( 弯曲 ) 
- Input and Output ( 输入输出)


## Filters
文档没写，找了半天没找到，惊了。 
- Adjustments (  调整 )
- blending ( 混合 )
- Blurs ( 模糊 )
- Channels ( 通道 )
- Effects ( 效果 )
- Normal Map ( 法线贴图 )
- Tiling ( 砖类 )
- Transforms ( 变换 )

## Mesh Adaptive
同上
- Mask Generators ( 网格生成 )
- Weathering ( 风化 )
- Utilities ( 工具类 )

## Function

函数构成:
- Constant 定义常量
- Vector  定义矢量
- Variables 定义变量
- Samplers 转换灰度/颜色
- Cast 转换用
- Operator 计算用
- Logical 处理且或否
- Comparison 处理Boolean
- Function 常用Function
- Random 随机用
- Control 流程控制



## Baker ( 烘焙 )

常用贴图：
- Ambient Occlusion 环境光遮蔽
- Amibent Occlusion Map For Mesh 网格环境光遮蔽
- Bent Normal Map from Mehs 网格弯曲法线图
- Color Map from Mesh 网格彩色图
- Convert UV to SVG UV转SVG图
- Curvature ( Cavity Map ) 曲率图
- Curvature Map from Mesh 网格曲率图
- Height Map From Mesh 网格高度图
- Normal Map From Mesh 网格法线贴图
- Opacity Mask from Mesh 不透明遮罩图
- Position 位置图
- Position Map from Mesh 网格位置图
- Thickness Map from Mesh 网格厚度图
- Transferred Texture form Mesh 网格传输纹理图
- World Space Direction 空间方向图
- World Space Normals 空间法线图


## DML (Material Definition Language)

由Nvidia提出, 用来描述基于物理的材料性质，以及如何表现。
