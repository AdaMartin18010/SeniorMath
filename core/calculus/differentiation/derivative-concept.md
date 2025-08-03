# Derivative Concept
## 导数概念

### Overview | 概述

The derivative is a fundamental concept in calculus that measures how a function changes as its input changes. It provides a precise way to describe rates of change, slopes of tangent lines, and instantaneous velocity.

导数是微积分中的基本概念，它测量函数随输入变化而变化的程度。它提供了一种精确的方式来描述变化率、切线斜率和瞬时速度。

### Definition | 定义

#### 1. Limit Definition | 极限定义

**Derivative**: The derivative of a function $f(x)$ at a point $x = a$ is defined as:

**导数**：函数 $f(x)$ 在点 $x = a$ 处的导数定义为：

$f'(a) = \lim_{h \to 0} \frac{f(a + h) - f(a)}{h}$

if this limit exists.

如果这个极限存在。

#### 2. Alternative Notation | 替代记法

**Leibniz Notation | 莱布尼茨记法**:
$\frac{d}{dx}f(x)$ or $\frac{df}{dx}$

**Prime Notation | 撇号记法**:
$f'(x)$

**Dot Notation | 点号记法** (for time derivatives):
$\dot{x}(t)$

### Geometric Interpretation | 几何解释

#### 1. Slope of Tangent Line | 切线斜率

The derivative $f'(a)$ represents the slope of the tangent line to the graph of $f(x)$ at the point $(a, f(a))$.

导数 $f'(a)$ 表示函数 $f(x)$ 在点 $(a, f(a))$ 处切线的斜率。

#### 2. Rate of Change | 变化率

The derivative measures the instantaneous rate of change of the function with respect to its variable.

导数测量函数相对于其变量的瞬时变化率。

### Physical Interpretation | 物理解释

#### 1. Velocity | 速度

If $s(t)$ represents position as a function of time, then:

如果 $s(t)$ 表示位置作为时间的函数，则：

$v(t) = s'(t) = \frac{ds}{dt}$

represents velocity.

表示速度。

#### 2. Acceleration | 加速度

The derivative of velocity is acceleration:

速度的导数是加速度：

$a(t) = v'(t) = s''(t) = \frac{d^2s}{dt^2}$

### Differentiability | 可微性

#### 1. Definition | 定义

A function $f(x)$ is differentiable at $x = a$ if the derivative $f'(a)$ exists.

如果导数 $f'(a)$ 存在，则函数 $f(x)$ 在 $x = a$ 处可微。

#### 2. Conditions for Differentiability | 可微性条件

**Necessary Conditions**:
- Function must be continuous at the point
- Limit of the difference quotient must exist

**充分条件**：
- 函数在该点必须连续
- 差商的极限必须存在

**Sufficient Conditions**:
- Function is continuous and has a well-defined tangent line
- Function is smooth (no sharp corners or cusps)

**充分条件**：
- 函数连续且有明确定义的切线
- 函数光滑（没有尖角或尖点）

### Basic Differentiation Rules | 基本求导法则

#### 1. Power Rule | 幂法则

$\frac{d}{dx}x^n = nx^{n-1}$

**Examples**:
- $\frac{d}{dx}x^2 = 2x$
- $\frac{d}{dx}x^3 = 3x^2$
- $\frac{d}{dx}\sqrt{x} = \frac{1}{2\sqrt{x}}$

#### 2. Constant Rule | 常数法则

$\frac{d}{dx}c = 0$

#### 3. Constant Multiple Rule | 常数倍法则

$\frac{d}{dx}[cf(x)] = cf'(x)$

#### 4. Sum Rule | 和法则

$\frac{d}{dx}[f(x) + g(x)] = f'(x) + g'(x)$

#### 5. Difference Rule | 差法则

$\frac{d}{dx}[f(x) - g(x)] = f'(x) - g'(x)$

#### 6. Product Rule | 积法则

$\frac{d}{dx}[f(x)g(x)] = f'(x)g(x) + f(x)g'(x)$

#### 7. Quotient Rule | 商法则

$\frac{d}{dx}\left[\frac{f(x)}{g(x)}\right] = \frac{f'(x)g(x) - f(x)g'(x)}{[g(x)]^2}$

#### 8. Chain Rule | 链式法则

$\frac{d}{dx}[f(g(x))] = f'(g(x)) \cdot g'(x)$

### Derivatives of Common Functions | 常见函数的导数

#### 1. Trigonometric Functions | 三角函数

- $\frac{d}{dx}\sin x = \cos x$
- $\frac{d}{dx}\cos x = -\sin x$
- $\frac{d}{dx}\tan x = \sec^2 x$
- $\frac{d}{dx}\cot x = -\csc^2 x$
- $\frac{d}{dx}\sec x = \sec x \tan x$
- $\frac{d}{dx}\csc x = -\csc x \cot x$

#### 2. Exponential and Logarithmic Functions | 指数和对数函数

- $\frac{d}{dx}e^x = e^x$
- $\frac{d}{dx}\ln x = \frac{1}{x}$
- $\frac{d}{dx}a^x = a^x \ln a$
- $\frac{d}{dx}\log_a x = \frac{1}{x \ln a}$

#### 3. Inverse Trigonometric Functions | 反三角函数

- $\frac{d}{dx}\sin^{-1} x = \frac{1}{\sqrt{1-x^2}}$
- $\frac{d}{dx}\cos^{-1} x = -\frac{1}{\sqrt{1-x^2}}$
- $\frac{d}{dx}\tan^{-1} x = \frac{1}{1+x^2}$

### Higher-Order Derivatives | 高阶导数

#### 1. Second Derivative | 二阶导数

$f''(x) = \frac{d^2}{dx^2}f(x) = \frac{d}{dx}[f'(x)]$

#### 2. nth Derivative | n阶导数

$f^{(n)}(x) = \frac{d^n}{dx^n}f(x)$

#### 3. Physical Interpretation | 物理解释

- First derivative: Velocity (速度)
- Second derivative: Acceleration (加速度)
- Third derivative: Jerk (急动度)

### Applications | 应用

#### 1. Optimization | 最优化

**Critical Points**: Points where $f'(x) = 0$ or $f'(x)$ is undefined.

**临界点**：$f'(x) = 0$ 或 $f'(x)$ 未定义的点。

**First Derivative Test**: Used to determine local maxima and minima.

**一阶导数检验**：用于确定局部最大值和最小值。

#### 2. Related Rates | 相关变化率

Problems involving the relationship between rates of change of different variables.

涉及不同变量变化率之间关系的问题。

#### 3. Linear Approximation | 线性近似

$f(x) \approx f(a) + f'(a)(x-a)$

for $x$ near $a$.

对于接近 $a$ 的 $x$。

### International Standards Alignment | 国际标准对齐

#### Common Core State Standards (CCSS)
- **HS.F-TF**: Extend the domain of trigonometric functions using the unit circle
- **HS.F-BF**: Build new functions from existing functions

#### UK National Curriculum
- **A-Level**: Understand and use differentiation
- **Further Mathematics**: Apply differentiation to solve problems

#### Singapore Mathematics Framework
- **Mathematical Reasoning**: Understand the concept of derivative and its applications
- **Mathematical Communication**: Use derivative notation and interpret results

### Exercises | 习题

#### Basic Level | 基础水平
1. Find the derivative of $f(x) = x^3 - 2x^2 + 5x - 1$
2. Calculate $\frac{d}{dx}\sin(x^2)$ using the chain rule
3. Find the equation of the tangent line to $y = x^2$ at $x = 2$

#### Advanced Level | 高级水平
1. Prove the product rule using the limit definition
2. Find all critical points of $f(x) = x^3 - 3x^2 + 2$
3. Use implicit differentiation to find $\frac{dy}{dx}$ for $x^2 + y^2 = 25$

### References | 参考文献

1. Stewart, J. (2015). *Calculus: Early Transcendentals*. Cengage Learning.
2. Apostol, T. M. (1974). *Mathematical Analysis*. Addison-Wesley.
3. Common Core State Standards Initiative. (2010). *Common Core State Standards for Mathematics*.
4. Department for Education. (2017). *Mathematics AS and A level content*.
5. Ministry of Education, Singapore. (2013). *Mathematics Syllabus Secondary*. 