# Complex Number System

## 复数系统

### Overview | 概述

Complex numbers extend the real number system to include solutions to equations that have no real solutions, such as $x^2 + 1 = 0$. They form a complete algebraically closed field and are fundamental in many areas of mathematics and physics.

复数扩展了实数系统，包含那些没有实数解的方程的解，如 $x^2 + 1 = 0$。它们形成一个完整的代数闭域，在数学和物理的许多领域都是基础。

### Definition | 定义

**Complex Number**: A number of the form $a + bi$, where $a$ and $b$ are real numbers and $i$ is the imaginary unit satisfying $i^2 = -1$.

**复数**：形如 $a + bi$ 的数，其中 $a$ 和 $b$ 是实数，$i$ 是满足 $i^2 = -1$ 的虚数单位。

**Notation**: $\mathbb{C}$

**Standard Form**: $z = a + bi$

- $a$ is the real part (实部)
- $b$ is the imaginary part (虚部)
- $i$ is the imaginary unit (虚数单位)

### Properties | 性质

#### 1. Field Properties | 域性质

Complex numbers form a field with the following properties:

复数形成一个域，具有以下性质：

**Addition**: $(a + bi) + (c + di) = (a + c) + (b + d)i$

**Multiplication**: $(a + bi)(c + di) = (ac - bd) + (ad + bc)i$

**Commutative Laws | 交换律**:

- $z_1 + z_2 = z_2 + z_1$
- $z_1 \cdot z_2 = z_2 \cdot z_1$

**Associative Laws | 结合律**:

- $(z_1 + z_2) + z_3 = z_1 + (z_2 + z_3)$
- $(z_1 \cdot z_2) \cdot z_3 = z_1 \cdot (z_2 \cdot z_3)$

**Distributive Law | 分配律**:

- $z_1 \cdot (z_2 + z_3) = z_1 \cdot z_2 + z_1 \cdot z_3$

#### 2. Algebraic Closure | 代数闭性

**Fundamental Theorem of Algebra**: Every non-constant polynomial with complex coefficients has at least one complex root.

**代数基本定理**：每个非常数的复系数多项式至少有一个复根。

### Geometric Representation | 几何表示

#### 1. Complex Plane | 复平面

Complex numbers can be represented as points in the complex plane:

复数可以表示为复平面中的点：

```text
Imaginary axis (虚轴)
    ↑
    |     z = a + bi
    |        •
    |        |
    |        | b
    |        |
----+--------+----→ Real axis (实轴)
    |        a
    |
```

#### 2. Polar Form | 极坐标形式

**Polar Form**: $z = r(\cos \theta + i\sin \theta) = re^{i\theta}$

Where:

- $r = |z| = \sqrt{a^2 + b^2}$ (modulus)
- $\theta = \arg(z) = \tan^{-1}(\frac{b}{a})$ (argument)

### Operations | 运算

#### 1. Addition | 加法

$(a + bi) + (c + di) = (a + c) + (b + d)i$

#### 2. Subtraction | 减法

$(a + bi) - (c + di) = (a - c) + (b - d)i$

#### 3. Multiplication | 乘法

$(a + bi)(c + di) = (ac - bd) + (ad + bc)i$

#### 4. Division | 除法

$\frac{a + bi}{c + di} = \frac{(ac + bd) + (bc - ad)i}{c^2 + d^2}$

#### 5. Conjugate | 共轭

$\overline{z} = a - bi$ if $z = a + bi$

#### 6. Modulus | 模

$|z| = \sqrt{a^2 + b^2}$

### Special Values | 特殊值

#### 1. Imaginary Unit | 虚数单位

$i = \sqrt{-1}$
$i^2 = -1$
$i^3 = -i$
$i^4 = 1$

#### 2. Powers of i | i的幂

$i^n = \begin{cases} 1 & \text{if } n \equiv 0 \pmod{4} \\ i & \text{if } n \equiv 1 \pmod{4} \\ -1 & \text{if } n \equiv 2 \pmod{4} \\ -i & \text{if } n \equiv 3 \pmod{4} \end{cases}$

### De Moivre's Theorem | 德摩根定理

**De Moivre's Theorem**: For any complex number $z = r(\cos \theta + i\sin \theta)$ and integer $n$:

**德摩根定理**：对于任意复数 $z = r(\cos \theta + i\sin \theta)$ 和整数 $n$：

$z^n = r^n(\cos(n\theta) + i\sin(n\theta))$

### Roots of Unity | 单位根

The $n$-th roots of unity are the solutions to $z^n = 1$:

$n$次单位根是方程 $z^n = 1$ 的解：

$z_k = e^{2\pi i k/n} = \cos(\frac{2\pi k}{n}) + i\sin(\frac{2\pi k}{n})$

for $k = 0, 1, 2, \ldots, n-1$

### Applications | 应用

#### 1. Electrical Engineering | 电气工程

- AC circuit analysis
- Impedance calculations
- Signal processing

#### 2. Physics | 物理学

- Quantum mechanics
- Wave functions
- Electromagnetic theory

#### 3. Mathematics | 数学

- Complex analysis
- Number theory
- Algebraic geometry

#### 4. Computer Science | 计算机科学

- Digital signal processing
- Fourier transforms
- Image processing

### International Standards Alignment | 国际标准对齐

#### Common Core State Standards (CCSS)

- **HS.N-CN**: Perform arithmetic operations with complex numbers
- **HS.N-CN.1**: Know there is a complex number $i$ such that $i^2 = -1$

#### UK National Curriculum

- **A-Level**: Understand and use complex numbers
- **Further Mathematics**: De Moivre's theorem and roots of unity

#### Singapore Mathematics Framework

- **Mathematical Reasoning**: Understand the structure of complex numbers
- **Mathematical Communication**: Use complex number notation and operations

### Exercises | 习题

#### Basic Level | 基础水平

1. Calculate $(3 + 4i)(2 - i)$
2. Find the modulus and argument of $1 + i$
3. Solve the equation $z^2 + 1 = 0$

#### Advanced Level | 高级水平

1. Prove De Moivre's theorem by mathematical induction
2. Find all fifth roots of unity
3. Show that the complex numbers form a field

### References | 参考文献

1. Ahlfors, L. V. (1979). *Complex Analysis*. McGraw-Hill.
2. Conway, J. B. (1978). *Functions of One Complex Variable*. Springer.
3. Common Core State Standards Initiative. (2010). *Common Core State Standards for Mathematics*.
4. Department for Education. (2017). *Mathematics AS and A level content*.
5. Ministry of Education, Singapore. (2013). *Mathematics Syllabus Secondary*.
