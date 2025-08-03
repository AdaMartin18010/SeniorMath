# Real Number System

## 实数系统

### Overview | 概述

The real number system is the foundation of modern mathematics, providing a complete ordered field that serves as the basis for calculus, analysis, and most mathematical applications.

实数系统是现代数学的基础，提供了一个完整的有序域，作为微积分、分析和大多数数学应用的基础。

### Definition | 定义

**Real Numbers**: The set of all numbers that can be represented on a number line, including all rational and irrational numbers.

**实数**：可以在数轴上表示的所有数的集合，包括所有有理数和无理数。

**Notation**: $\mathbb{R}$

### Properties | 性质

#### 1. Field Properties | 域性质

The real numbers form a complete ordered field with the following properties:

实数形成一个完整的有序域，具有以下性质：

**Commutative Laws | 交换律**:

- $a + b = b + a$ (addition)
- $a \cdot b = b \cdot a$ (multiplication)

**Associative Laws | 结合律**:

- $(a + b) + c = a + (b + c)$ (addition)
- $(a \cdot b) \cdot c = a \cdot (b \cdot c)$ (multiplication)

**Distributive Law | 分配律**:

- $a \cdot (b + c) = a \cdot b + a \cdot c$

**Identity Elements | 单位元**:

- $a + 0 = a$ (additive identity)
- $a \cdot 1 = a$ (multiplicative identity)

**Inverse Elements | 逆元**:

- $a + (-a) = 0$ (additive inverse)
- $a \cdot \frac{1}{a} = 1$ (multiplicative inverse, $a \neq 0$)

#### 2. Order Properties | 序性质

**Trichotomy | 三分律**
For any real numbers $a$ and $b$, exactly one of the following holds:
对于任意实数 $a$ 和 $b$，以下三种情况恰好有一种成立：

- $a < b$
- $a = b$
- $a > b$

**Transitivity | 传递性**
If $a < b$ and $b < c$, then $a < c$

**Addition Property | 加法性质**
If $a < b$, then $a + c < b + c$ for any real number $c$

**Multiplication Property | 乘法性质**
If $a < b$ and $c > 0$, then $a \cdot c < b \cdot c$

#### 3. Completeness | 完备性

**Least Upper Bound Property | 最小上界性质**
Every non-empty set of real numbers that is bounded above has a least upper bound.

每个有上界的非空实数集都有最小上界。

### Subsets | 子集

#### 1. Natural Numbers | 自然数

**Notation**: $\mathbb{N} = \{1, 2, 3, 4, \ldots\}$

#### 2. Integers | 整数

**Notation**: $\mathbb{Z} = \{\ldots, -2, -1, 0, 1, 2, \ldots\}$

#### 3. Rational Numbers | 有理数

**Notation**: $\mathbb{Q} = \{\frac{p}{q} : p, q \in \mathbb{Z}, q \neq 0\}$

#### 4. Irrational Numbers | 无理数

**Notation**: $\mathbb{R} \setminus \mathbb{Q}$

Examples: $\sqrt{2}, \pi, e$

### Number Line | 数轴

The real numbers can be represented as points on a number line:

实数可以表示为数轴上的点：

```text
<--|--|--|--|--|--|--|--|--|--|--|--|-->
   -3  -2  -1   0   1   2   3   4   5
```

### Operations | 运算

#### 1. Addition | 加法

- **Definition**: $a + b$ is the sum of real numbers $a$ and $b$
- **Properties**: Commutative, associative, has identity element 0

#### 2. Multiplication | 乘法

- **Definition**: $a \cdot b$ is the product of real numbers $a$ and $b$
- **Properties**: Commutative, associative, has identity element 1

#### 3. Subtraction | 减法

- **Definition**: $a - b = a + (-b)$

#### 4. Division | 除法

- **Definition**: $a \div b = a \cdot \frac{1}{b}$ (for $b \neq 0$)

### Inequalities | 不等式

#### 1. Basic Inequalities | 基本不等式

- $a < b$ means $a$ is less than $b$
- $a \leq b$ means $a$ is less than or equal to $b$
- $a > b$ means $a$ is greater than $b$
- $a \geq b$ means $a$ is greater than or equal to $b$

#### 2. Properties | 性质

- If $a < b$ and $c > 0$, then $ac < bc$
- If $a < b$ and $c < 0$, then $ac > bc$
- If $a < b$ and $c < d$, then $a + c < b + d$

### Absolute Value | 绝对值

**Definition**: $|a| = \begin{cases} a & \text{if } a \geq 0 \\ -a & \text{if } a < 0 \end{cases}$

**Properties**:

- $|a| \geq 0$ for all real numbers $a$
- $|a| = 0$ if and only if $a = 0$
- $|ab| = |a| \cdot |b|$
- $|a + b| \leq |a| + |b|$ (Triangle Inequality)

### Applications | 应用

#### 1. Calculus | 微积分

- Real numbers provide the foundation for limits, continuity, and differentiation
- The completeness property is essential for the Intermediate Value Theorem

#### 2. Analysis | 分析

- Real numbers are used in convergence of sequences and series
- Essential for the definition of continuous functions

#### 3. Geometry | 几何

- Real numbers provide coordinates for geometric objects
- Used in distance calculations and geometric transformations

### International Standards Alignment | 国际标准对齐

#### Common Core State Standards (CCSS)

- **HS.N-RN**: Extend the properties of exponents to rational exponents
- **HS.A-REI**: Solve equations and inequalities in one variable

#### UK National Curriculum

- **Key Stage 4**: Understand and use place value for decimals, measures and integers of any size
- **A-Level**: Understand the real number system and its properties

#### Singapore Mathematics Framework

- **Mathematical Reasoning**: Understand the structure and properties of the real number system
- **Mathematical Communication**: Use precise mathematical language to describe number properties

### Exercises | 习题

#### Basic Level | 基础水平

1. Prove that $\sqrt{2}$ is irrational
2. Show that the sum of two rational numbers is rational
3. Demonstrate that the real numbers are uncountable

#### Advanced Level | 高级水平

1. Prove the completeness property of real numbers
2. Show that every real number has a decimal representation
3. Prove the Archimedean property of real numbers

### References | 参考文献

1. Rudin, W. (1976). *Principles of Mathematical Analysis*. McGraw-Hill.
2. Apostol, T. M. (1974). *Mathematical Analysis*. Addison-Wesley.
3. Common Core State Standards Initiative. (2010). *Common Core State Standards for Mathematics*.
4. Department for Education. (2014). *Mathematics programmes of study: key stage 4*.
5. Ministry of Education, Singapore. (2013). *Mathematics Syllabus Secondary*.
