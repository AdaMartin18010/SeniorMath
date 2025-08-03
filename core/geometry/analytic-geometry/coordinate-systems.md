# Coordinate Systems

## 坐标系

### Overview | 概述

Coordinate systems provide a framework for representing geometric objects and relationships using numerical coordinates. They are fundamental to analytic geometry, calculus, and many applications in science and engineering.

坐标系为使用数值坐标表示几何对象和关系提供了框架。它们是解析几何、微积分以及科学和工程中许多应用的基础。

### Cartesian Coordinate System | 笛卡尔坐标系

#### 1. Two-Dimensional Cartesian Coordinates | 二维笛卡尔坐标

**Definition**: A coordinate system in which each point is identified by an ordered pair of real numbers $(x, y)$.

**定义**：每个点由有序实数对 $(x, y)$ 标识的坐标系。

**Components**:

- **Origin**: The point $(0, 0)$ where the axes intersect
- **X-axis**: The horizontal axis
- **Y-axis**: The vertical axis
- **Quadrants**: Four regions divided by the axes

**组成部分**：

- **原点**：坐标轴相交的点 $(0, 0)$
- **X轴**：水平轴
- **Y轴**：垂直轴
- **象限**：坐标轴分割的四个区域

**Quadrants**:

- **First Quadrant**: $x > 0, y > 0$
- **Second Quadrant**: $x < 0, y > 0$
- **Third Quadrant**: $x < 0, y < 0$
- **Fourth Quadrant**: $x > 0, y < 0$

#### 2. Three-Dimensional Cartesian Coordinates | 三维笛卡尔坐标

**Definition**: A coordinate system in which each point is identified by an ordered triple of real numbers $(x, y, z)$.

**定义**：每个点由有序实数三元组 $(x, y, z)$ 标识的坐标系。

**Components**:

- **Origin**: The point $(0, 0, 0)$
- **X-axis**: The horizontal axis
- **Y-axis**: The vertical axis
- **Z-axis**: The depth axis
- **Octants**: Eight regions divided by the coordinate planes

### Polar Coordinate System | 极坐标系

#### 1. Two-Dimensional Polar Coordinates | 二维极坐标

**Definition**: A coordinate system in which each point is identified by $(r, \theta)$, where $r$ is the distance from the origin and $\theta$ is the angle from the positive x-axis.

**定义**：每个点由 $(r, \theta)$ 标识的坐标系，其中 $r$ 是到原点的距离，$\theta$ 是与正x轴的夹角。

**Components**:

- **r**: Radial distance from origin
- **θ**: Angular coordinate (usually in radians)
- **Pole**: The origin $(0, 0)$
- **Polar Axis**: The positive x-axis

**Conversion Formulas**:

- Cartesian to Polar: $r = \sqrt{x^2 + y^2}$, $\theta = \tan^{-1}(\frac{y}{x})$
- Polar to Cartesian: $x = r\cos\theta$, $y = r\sin\theta$

#### 2. Three-Dimensional Polar Coordinates | 三维极坐标

**Spherical Coordinates**: $(r, \theta, \phi)$

- **r**: Distance from origin
- **θ**: Azimuthal angle (longitude)
- **φ**: Polar angle (colatitude)

**Cylindrical Coordinates**: $(r, \theta, z)$

- **r**: Distance from z-axis
- **θ**: Azimuthal angle
- **z**: Height above xy-plane

### Distance and Midpoint | 距离和中点

#### 1. Distance Formula | 距离公式

**Two Dimensions**:
$d = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}$

**Three Dimensions**:
$d = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2 + (z_2 - z_1)^2}$

#### 2. Midpoint Formula | 中点公式

**Two Dimensions**:
$M = (\frac{x_1 + x_2}{2}, \frac{y_1 + y_2}{2})$

**Three Dimensions**:
$M = (\frac{x_1 + x_2}{2}, \frac{y_1 + y_2}{2}, \frac{z_1 + z_2}{2})$

### Transformations | 变换

#### 1. Translation | 平移

Moving all points by a constant vector:

将所有点按常向量移动：

$(x, y) \rightarrow (x + a, y + b)$

#### 2. Scaling | 缩放

Multiplying coordinates by constants:

将坐标乘以常数：

$(x, y) \rightarrow (ax, by)$

#### 3. Rotation | 旋转

Rotating points around the origin by angle $\theta$:

将点绕原点旋转角度 $\theta$：

$(x, y) \rightarrow (x\cos\theta - y\sin\theta, x\sin\theta + y\cos\theta)$

#### 4. Reflection | 反射

Reflecting across axes or lines:

关于轴或线的反射：

- Across x-axis: $(x, y) \rightarrow (x, -y)$
- Across y-axis: $(x, y) \rightarrow (-x, y)$
- Across line $y = x$: $(x, y) \rightarrow (y, x)$

### Applications | 应用

#### 1. Geometry | 几何学

- Plotting points and curves
- Finding distances and areas
- Analyzing geometric shapes

#### 2. Physics | 物理学

- Motion in space
- Force vectors
- Wave propagation

#### 3. Engineering | 工程学

- Computer graphics
- Robotics
- Navigation systems

#### 4. Computer Science | 计算机科学

- Image processing
- Game development
- Geographic information systems

### Special Coordinate Systems | 特殊坐标系

#### 1. Homogeneous Coordinates | 齐次坐标

**Definition**: Representing n-dimensional coordinates with n+1 coordinates.

**定义**：用n+1个坐标表示n维坐标。

**Use**: Computer graphics, projective geometry

**用途**：计算机图形学、射影几何

#### 2. Barycentric Coordinates | 重心坐标

**Definition**: Coordinates based on the vertices of a simplex.

**定义**：基于单纯形顶点的坐标。

**Use**: Computer graphics, finite element analysis

**用途**：计算机图形学、有限元分析

#### 3. Curvilinear Coordinates | 曲线坐标

**Definition**: Coordinate systems where the coordinate lines are curved.

**定义**：坐标线为曲线的坐标系。

**Examples**: Spherical, cylindrical, elliptical coordinates

**例子**：球坐标、柱坐标、椭圆坐标

### International Standards Alignment | 国际标准对齐

#### Common Core State Standards (CCSS)

- **HS.G-GPE**: Use coordinates to prove simple geometric theorems algebraically
- **HS.G-GPE.1**: Derive the equation of a circle of given center and radius

#### UK National Curriculum

- **Key Stage 4**: Use coordinate geometry to solve problems
- **A-Level**: Understand and use coordinate geometry in three dimensions

#### Singapore Mathematics Framework

- **Mathematical Reasoning**: Understand coordinate systems and transformations
- **Mathematical Communication**: Use coordinate notation and geometric language

### Exercises | 习题

#### Basic Level | 基础水平

1. Find the distance between points $(2, 3)$ and $(5, 7)$
2. Find the midpoint of the line segment from $(1, 2)$ to $(7, 8)$
3. Convert $(3, 4)$ from Cartesian to polar coordinates

#### Advanced Level | 高级水平

1. Find the equation of the circle with center $(2, -1)$ and radius 5
2. Rotate the point $(3, 4)$ by $45°$ about the origin
3. Find the distance between points $(1, 2, 3)$ and $(4, 5, 6)$ in 3D

### References | 参考文献

1. Coxeter, H. S. M. (1969). *Introduction to Geometry*. Wiley.
2. Anton, H. (2010). *Elementary Linear Algebra*. Wiley.
3. Common Core State Standards Initiative. (2010). *Common Core State Standards for Mathematics*.
4. Department for Education. (2014). *Mathematics programmes of study: key stage 4*.
5. Ministry of Education, Singapore. (2013). *Mathematics Syllabus Secondary*.
