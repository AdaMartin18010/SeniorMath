# 数学建模概念

## 概念定义

### 1. 数学建模 (Mathematical Modeling)

**形式化定义**：

- 数学建模是将实际问题转化为数学问题的过程
- 建立数学模型：$M: \mathbb{R}^n \rightarrow \mathbb{R}^m$
- 模型参数：$\theta = (\theta_1, \theta_2, \ldots, \theta_p)$

**建模过程**：

1. 问题分析：理解实际问题
2. 假设建立：简化问题条件
3. 模型构建：建立数学关系
4. 求解验证：求解并验证结果
5. 结果解释：将数学结果转化为实际意义

### 2. 数学模型 (Mathematical Model)

**形式化定义**：

- 数学模型是描述现实系统的数学结构
- 一般形式：$F(x, y, \theta) = 0$
- 其中 $x$ 是输入变量，$y$ 是输出变量，$\theta$ 是参数

**模型类型**：

- 确定性模型：$y = f(x, \theta)$
- 随机模型：$y = f(x, \theta) + \epsilon$
- 动态模型：$\frac{dy}{dt} = f(y, t, \theta)$

### 3. 建模假设 (Modeling Assumptions)

**假设类型**：

- 简化假设：忽略次要因素
- 线性假设：假设关系为线性
- 均匀假设：假设空间或时间均匀
- 独立性假设：假设变量独立

**假设验证**：

- 敏感性分析：检验假设影响
- 稳健性检验：检验模型稳定性
- 预测检验：检验模型预测能力

## 建模方法

### 1. 微分方程建模

**常微分方程**：

- 一阶方程：$\frac{dy}{dt} = f(t, y)$
- 二阶方程：$\frac{d^2y}{dt^2} = f(t, y, \frac{dy}{dt})$
- 系统方程：$\frac{d\mathbf{y}}{dt} = \mathbf{f}(t, \mathbf{y})$

**偏微分方程**：

- 热传导方程：$\frac{\partial u}{\partial t} = \alpha \nabla^2 u$
- 波动方程：$\frac{\partial^2 u}{\partial t^2} = c^2 \nabla^2 u$
- 扩散方程：$\frac{\partial u}{\partial t} = D \frac{\partial^2 u}{\partial x^2}$

### 2. 优化建模

**线性规划**：

- 目标函数：$\max z = \mathbf{c}^T\mathbf{x}$
- 约束条件：$A\mathbf{x} \leq \mathbf{b}, \mathbf{x} \geq 0$

**非线性规划**：

- 目标函数：$\min f(\mathbf{x})$
- 约束条件：$g_i(\mathbf{x}) \leq 0, h_j(\mathbf{x}) = 0$

**动态规划**：

- 贝尔曼方程：$V(s) = \max_a \{R(s, a) + \gamma V(s')\}$

### 3. 统计建模

**回归模型**：

- 线性回归：$y = \beta_0 + \beta_1 x_1 + \cdots + \beta_p x_p + \epsilon$
- 非线性回归：$y = f(x, \beta) + \epsilon$
- 逻辑回归：$\log\frac{p}{1-p} = \beta_0 + \beta_1 x_1 + \cdots + \beta_p x_p$

**时间序列模型**：

- AR模型：$y_t = \phi_1 y_{t-1} + \cdots + \phi_p y_{t-p} + \epsilon_t$
- MA模型：$y_t = \epsilon_t + \theta_1 \epsilon_{t-1} + \cdots + \theta_q \epsilon_{t-q}$
- ARMA模型：$y_t = \phi_1 y_{t-1} + \cdots + \phi_p y_{t-p} + \epsilon_t + \theta_1 \epsilon_{t-1} + \cdots + \theta_q \epsilon_{t-q}$

### 4. 图论建模

**网络模型**：

- 图 $G = (V, E)$
- 节点集：$V = \{v_1, v_2, \ldots, v_n\}$
- 边集：$E = \{e_1, e_2, \ldots, e_m\}$

**网络分析**：

- 度中心性：$C_D(v_i) = \frac{d_i}{n-1}$
- 接近中心性：$C_C(v_i) = \frac{n-1}{\sum_{j \neq i} d_{ij}}$
- 介数中心性：$C_B(v_i) = \sum_{j \neq k} \frac{\sigma_{jk}(v_i)}{\sigma_{jk}}$

## 建模应用

### 1. 物理建模

**力学模型**：

- 牛顿第二定律：$F = ma$
- 弹簧振动：$m\frac{d^2x}{dt^2} + kx = 0$
- 阻尼振动：$m\frac{d^2x}{dt^2} + c\frac{dx}{dt} + kx = 0$

**热学模型**：

- 热传导：$\frac{\partial T}{\partial t} = \alpha \frac{\partial^2 T}{\partial x^2}$
- 对流换热：$q = hA(T_s - T_\infty)$
- 辐射换热：$q = \sigma A(T_s^4 - T_\infty^4)$

### 2. 经济建模

**供需模型**：

- 需求函数：$Q_d = a - bP$
- 供给函数：$Q_s = c + dP$
- 市场均衡：$Q_d = Q_s$

**经济增长模型**：

- 索洛模型：$\frac{dK}{dt} = sY - \delta K$
- 生产函数：$Y = AK^\alpha L^{1-\alpha}$
- 人均资本：$\frac{dk}{dt} = sf(k) - (n+\delta)k$

### 3. 生物建模

**种群模型**：

- 马尔萨斯模型：$\frac{dN}{dt} = rN$
- 逻辑斯蒂模型：$\frac{dN}{dt} = rN(1-\frac{N}{K})$
- 捕食者-猎物模型：$\frac{dx}{dt} = ax - bxy, \frac{dy}{dt} = -cy + dxy$

**流行病模型**：

- SIR模型：$\frac{dS}{dt} = -\beta SI, \frac{dI}{dt} = \beta SI - \gamma I, \frac{dR}{dt} = \gamma I$
- 基本再生数：$R_0 = \frac{\beta S_0}{\gamma}$

### 4. 工程建模

**结构分析**：

- 梁弯曲：$EI\frac{d^4y}{dx^4} = q(x)$
- 应力分析：$\sigma = \frac{F}{A}$
- 应变分析：$\epsilon = \frac{\Delta L}{L}$

**流体力学**：

- 连续性方程：$\frac{\partial \rho}{\partial t} + \nabla \cdot (\rho \mathbf{v}) = 0$
- 纳维-斯托克斯方程：$\rho(\frac{\partial \mathbf{v}}{\partial t} + \mathbf{v} \cdot \nabla \mathbf{v}) = -\nabla p + \mu \nabla^2 \mathbf{v} + \mathbf{f}$

## 模型验证

### 1. 参数估计

**最小二乘法**：

- 目标函数：$\min \sum_{i=1}^{n} (y_i - f(x_i, \theta))^2$
- 正规方程：$X^TX\hat{\beta} = X^Ty$

**最大似然估计**：

- 似然函数：$L(\theta) = \prod_{i=1}^{n} f(y_i|\theta)$
- 对数似然：$\ell(\theta) = \sum_{i=1}^{n} \log f(y_i|\theta)$

**贝叶斯估计**：

- 后验分布：$p(\theta|y) \propto p(y|\theta)p(\theta)$
- 先验分布：$p(\theta)$

### 2. 模型检验

**拟合优度**：

- 决定系数：$R^2 = 1 - \frac{SSE}{SST}$
- 调整决定系数：$\bar{R}^2 = 1 - \frac{SSE/(n-p)}{SST/(n-1)}$
- AIC准则：$AIC = 2k - 2\ln(L)$

**残差分析**：

- 残差：$e_i = y_i - \hat{y}_i$
- 标准化残差：$r_i = \frac{e_i}{s\sqrt{1-h_{ii}}}$
- 学生化残差：$t_i = \frac{e_i}{s_{(i)}\sqrt{1-h_{ii}}}$

### 3. 预测检验

**交叉验证**：

- 留一法：每次留一个样本作为测试集
- k折交叉验证：将数据分为k份，轮流使用
- 时间序列交叉验证：按时间顺序分割数据

**预测误差**：

- 均方误差：$MSE = \frac{1}{n}\sum_{i=1}^{n} (y_i - \hat{y}_i)^2$
- 平均绝对误差：$MAE = \frac{1}{n}\sum_{i=1}^{n} |y_i - \hat{y}_i|$
- 平均绝对百分比误差：$MAPE = \frac{100}{n}\sum_{i=1}^{n} |\frac{y_i - \hat{y}_i}{y_i}|$

## 应用实例

### 1. 人口增长建模

**例1**：建立人口增长模型

**模型假设**：

- 人口增长率恒定
- 无迁移影响
- 无环境限制

**数学模型**：

- $\frac{dP}{dt} = rP$
- 解：$P(t) = P_0 e^{rt}$

**参数估计**：

- 历史数据拟合
- 最小二乘法估计 $r$

### 2. 经济供需建模

**例2**：建立市场供需模型

**模型假设**：

- 线性供需关系
- 市场完全竞争
- 价格弹性恒定

**数学模型**：

- 需求：$Q_d = a - bP$
- 供给：$Q_s = c + dP$
- 均衡：$Q_d = Q_s$

**求解**：

- 均衡价格：$P^* = \frac{a-c}{b+d}$
- 均衡数量：$Q^* = \frac{ad+bc}{b+d}$

### 3. 传染病传播建模

**例3**：建立SIR传染病模型

**模型假设**：

- 人群分为易感者(S)、感染者(I)、康复者(R)
- 感染率恒定
- 康复率恒定

**数学模型**：

- $\frac{dS}{dt} = -\beta SI$
- $\frac{dI}{dt} = \beta SI - \gamma I$
- $\frac{dR}{dt} = \gamma I$

**参数估计**：

- $\beta$：感染率
- $\gamma$：康复率
- $R_0 = \frac{\beta S_0}{\gamma}$：基本再生数

## 认知适配设计

### 1. 直观理解阶段

**具体表征**：

- 通过具体例子理解建模概念
- 使用实物演示建模过程
- 通过实验验证建模结果

**语言表征**：

- 用自然语言描述建模概念
- 通过类比理解抽象概念
- 用具体例子说明建模性质

### 2. 符号引入阶段

**符号系统**：

- 逐步引入建模符号
- 建立符号与概念的对应关系
- 通过符号表达建模关系

**公式推导**：

- 从具体问题推导建模公式
- 通过公式验证建模性质
- 建立建模与数学的联系

### 3. 抽象概括阶段

**概念抽象**：

- 从具体问题抽象出建模概念
- 建立建模概念的一般性质
- 形成建模理论体系

**推理系统**：

- 建立建模推理规则
- 形成建模分析方法
- 发展建模思维能力

### 4. 理论应用阶段

**问题解决**：

- 应用建模知识解决实际问题
- 建立建模方法体系
- 发展建模应用能力

**创新应用**：

- 探索建模的新应用领域
- 发展建模的创新思维
- 培养建模的创新能力
