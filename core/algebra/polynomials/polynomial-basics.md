# Polynomial Basics

## 多项式基础

### Overview | 概述

Polynomials are fundamental algebraic expressions that form the basis for much of algebra, calculus, and mathematical analysis. They are expressions consisting of variables and coefficients, involving only the operations of addition, subtraction, multiplication, and non-negative integer exponents.

多项式是基础的代数表达式，构成了代数、微积分和数学分析的基础。它们是由变量和系数组成的表达式，只涉及加法、减法、乘法和非负整数指数的运算。

### Definition | 定义

**Polynomial**: An expression of the form:

**多项式**：形如以下的表达式：

$P(x) = a_nx^n + a_{n-1}x^{n-1} + \cdots + a_1x + a_0$

where:

- $a_i$ are coefficients (real or complex numbers)
- $x$ is the variable
- $n$ is a non-negative integer (the degree of the polynomial)
- $a_n \neq 0$ (leading coefficient)

其中：

- $a_i$ 是系数（实数或复数）
- $x$ 是变量
- $n$ 是非负整数（多项式的次数）
- $a_n \neq 0$（首项系数）

### Standard Form | 标准形式

A polynomial is in standard form when:
多项式在标准形式时：

1. Terms are arranged in descending order of degree
2. Like terms are combined
3. The leading coefficient is positive (if possible)

   1. 项按次数降序排列
   2. 同类项合并
   3. 首项系数为正（如果可能）

**Example**: $2x^3 - 5x^2 + 3x - 7$

### Degree and Classification | 次数和分类

#### 1. Degree | 次数

**Degree of a Polynomial**: The highest power of the variable in the polynomial.

**多项式的次数**：多项式中变量的最高幂次。

**Examples**:

- $P(x) = 2x^3 - 5x^2 + 3x - 7$ has degree 3
- $Q(x) = x^2 + 1$ has degree 2
- $R(x) = 5$ has degree 0 (constant polynomial)

#### 2. Classification by Degree | 按次数分类

**Constant Polynomial | 常数多项式**: Degree 0

- Example: $P(x) = 5$

**Linear Polynomial | 一次多项式**: Degree 1

- Example: $P(x) = 2x + 3$

**Quadratic Polynomial | 二次多项式**: Degree 2

- Example: $P(x) = x^2 - 4x + 4$

**Cubic Polynomial | 三次多项式**: Degree 3

- Example: $P(x) = x^3 - 2x^2 + x - 1$

**Quartic Polynomial | 四次多项式**: Degree 4

- Example: $P(x) = x^4 - 3x^2 + 2$

**Quintic Polynomial | 五次多项式**: Degree 5

- Example: $P(x) = x^5 - x^3 + x$

### Operations | 运算

#### 1. Addition and Subtraction | 加法和减法

To add or subtract polynomials, combine like terms:

要加减多项式，合并同类项：

$(3x^2 + 2x - 1) + (x^2 - 3x + 4) = 4x^2 - x + 3$

$(3x^2 + 2x - 1) - (x^2 - 3x + 4) = 2x^2 + 5x - 5$

#### 2. Multiplication | 乘法

Use the distributive property and combine like terms:

使用分配律并合并同类项：

$(2x + 3)(x^2 - 2x + 1) = 2x^3 - 4x^2 + 2x + 3x^2 - 6x + 3 = 2x^3 - x^2 - 4x + 3$

#### 3. Division | 除法

**Long Division | 长除法**：

Divide $P(x)$ by $D(x)$ to get quotient $Q(x)$ and remainder $R(x)$:

将 $P(x)$ 除以 $D(x)$ 得到商 $Q(x)$ 和余数 $R(x)$：

$P(x) = D(x) \cdot Q(x) + R(x)$

where $\deg(R(x)) < \deg(D(x))$

其中 $\deg(R(x)) < \deg(D(x))$

### Special Polynomials | 特殊多项式

#### 1. Monic Polynomial | 首一多项式

A polynomial where the leading coefficient is 1.

首项系数为1的多项式。

**Example**: $x^3 - 2x^2 + x - 1$

#### 2. Zero Polynomial | 零多项式

The polynomial with all coefficients equal to zero.

所有系数都为零的多项式。

**Notation**: $P(x) = 0$

#### 3. Constant Polynomial | 常数多项式

A polynomial of degree 0.

次数为0的多项式。

**Example**: $P(x) = 5$

### Polynomial Functions | 多项式函数

#### 1. Definition | 定义

A polynomial function is a function defined by a polynomial expression.

多项式函数是由多项式表达式定义的函数。

$f(x) = a_nx^n + a_{n-1}x^{n-1} + \cdots + a_1x + a_0$

#### 2. Properties | 性质

**Domain**: All real numbers (or complex numbers)
**Range**: Depends on the degree and coefficients
**Continuity**: Polynomial functions are continuous everywhere
**Differentiability**: Polynomial functions are differentiable everywhere

**定义域**：所有实数（或复数）
**值域**：取决于次数和系数
**连续性**：多项式函数处处连续
**可微性**：多项式函数处处可微

### Roots and Zeros | 根和零点

#### 1. Definition | 1定义

**Root/Zero**: A value $r$ such that $P(r) = 0$

**根/零点**：使得 $P(r) = 0$ 的值 $r$

#### 2. Fundamental Theorem of Algebra | 代数基本定理

Every non-constant polynomial with complex coefficients has at least one complex root.

每个非常数的复系数多项式至少有一个复根。

#### 3. Factor Theorem | 因式定理

If $r$ is a root of $P(x)$, then $(x - r)$ is a factor of $P(x)$.

如果 $r$ 是 $P(x)$ 的根，则 $(x - r)$ 是 $P(x)$ 的因式。

#### 4. Multiplicity | 重数

The multiplicity of a root is the number of times it appears as a factor.

根的重数是它作为因式出现的次数。

**Example**: In $P(x) = (x-2)^3(x+1)$, the root 2 has multiplicity 3.

### Applications | 应用

#### 1. Algebra | 代数

- Solving equations
- Factoring expressions
- Simplifying rational expressions

#### 2. Calculus | 微积分

- Differentiation and integration
- Taylor series
- Approximation of functions

#### 3. Physics | 物理学

- Motion equations
- Force calculations
- Energy expressions

#### 4. Engineering | 工程学

- Signal processing
- Control systems
- Optimization problems

### International Standards Alignment | 国际标准对齐

#### Common Core State Standards (CCSS)

- **HS.A-APR**: Understand the relationship between zeros and factors of polynomials
- **HS.A-APR.1**: Understand that polynomials form a system analogous to the integers

#### UK National Curriculum

- **Key Stage 4**: Understand and use polynomial expressions
- **A-Level**: Factorise polynomials and solve polynomial equations

#### Singapore Mathematics Framework

- **Mathematical Reasoning**: Understand polynomial properties and relationships
- **Mathematical Communication**: Use polynomial notation and operations

### Exercises | 习题

#### Basic Level | 基础水平

1. Add the polynomials: $(2x^2 + 3x - 1) + (x^2 - 2x + 4)$
2. Multiply: $(x + 2)(x^2 - 3x + 1)$
3. Find the degree of $P(x) = 3x^4 - 2x^2 + 5x - 1$

#### Advanced Level | 高级水平

1. Use long division to divide $x^3 - 2x^2 + 3x - 1$ by $x - 1$
2. Find all roots of $P(x) = x^3 - 6x^2 + 11x - 6$
3. Prove that if $r$ is a root of $P(x)$, then $(x-r)$ is a factor

### References | 参考文献

1. Lang, S. (2002). *Algebra*. Springer.
2. Hungerford, T. W. (1974). *Algebra*. Springer.
3. Common Core State Standards Initiative. (2010). *Common Core State Standards for Mathematics*.
4. Department for Education. (2014). *Mathematics programmes of study: key stage 4*.
5. Ministry of Education, Singapore. (2013). *Mathematics Syllabus Secondary*.
