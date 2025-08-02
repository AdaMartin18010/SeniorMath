# 概率统计概念核心定义

## 1. 概率 (Probability / Wahrscheinlichkeit / Probabilité)

### 1.1 中文定义

**概率**是描述随机事件发生可能性大小的数值，取值范围在0到1之间，其中0表示不可能事件，1表示必然事件。

### 1.2 English Definition

**Probability** is a numerical value describing the likelihood of occurrence of a random event, ranging from 0 to 1, where 0 represents an impossible event and 1 represents a certain event.

### 1.3 Deutsche Definition

**Wahrscheinlichkeit** ist ein numerischer Wert, der die Wahrscheinlichkeit des Eintretens eines zufälligen Ereignisses beschreibt, reichend von 0 bis 1, wobei 0 ein unmögliches Ereignis und 1 ein sicheres Ereignis darstellt.

### 1.4 Définition Française

La **probabilité** est une valeur numérique décrivant la vraisemblance d'occurrence d'un événement aléatoire, allant de 0 à 1, où 0 représente un événement impossible et 1 représente un événement certain.

## 2. 随机事件 (Random Event / Zufallsereignis / Événement aléatoire)

### 2.1 中文定义

**随机事件**是在一定条件下可能发生也可能不发生的事件，其发生与否具有不确定性。

### 2.2 English Definition

A **random event** is an event that may or may not occur under certain conditions, with uncertainty about whether it will occur.

### 2.3 Deutsche Definition

Ein **Zufallsereignis** ist ein Ereignis, das unter bestimmten Bedingungen eintreten kann oder nicht, mit Unsicherheit darüber, ob es eintreten wird.

### 2.4 Définition Française

Un **événement aléatoire** est un événement qui peut ou ne peut pas se produire sous certaines conditions, avec une incertitude quant à sa réalisation.

### 2.5 事件类型

**必然事件 (Certain Event / Sicheres Ereignis / Événement certain)**：

- 在给定条件下必定发生的事件
- 概率为1

**不可能事件 (Impossible Event / Unmögliches Ereignis / Événement impossible)**：

- 在给定条件下必定不发生的事件
- 概率为0

**随机事件 (Random Event / Zufallsereignis / Événement aléatoire)**：

- 在给定条件下可能发生也可能不发生的事件
- 概率在0到1之间

## 3. 样本空间 (Sample Space / Stichprobenraum / Espace échantillon)

### 3.1 中文定义

**样本空间**是随机试验所有可能结果的集合，通常用Ω表示。

### 3.2 English Definition

A **sample space** is the set of all possible outcomes of a random experiment, usually denoted by Ω.

### 3.3 Deutsche Definition

Ein **Stichprobenraum** ist die Menge aller möglichen Ergebnisse eines Zufallsexperiments, gewöhnlich bezeichnet als Ω.

### 3.4 Définition Française

Un **espace échantillon** est l'ensemble de tous les résultats possibles d'une expérience aléatoire, généralement noté Ω.

### 3.5 样本空间的性质

**完备性 (Completeness / Vollständigkeit / Complétude)**：

- 包含试验的所有可能结果

**互斥性 (Mutual Exclusivity / Gegenseitiger Ausschluss / Exclusivité mutuelle)**：

- 不同结果之间互不相容

**等可能性 (Equiprobability / Gleichwahrscheinlichkeit / Équiprobabilité)**：

- 在古典概型中，所有结果具有相同的概率

## 4. 随机变量 (Random Variable / Zufallsvariable / Variable aléatoire)

### 4.1 中文定义

**随机变量**是将样本空间中的每个结果映射到实数的函数，用于量化随机现象。

### 4.2 English Definition

A **random variable** is a function that maps each outcome in the sample space to a real number, used to quantify random phenomena.

### 4.3 Deutsche Definition

Eine **Zufallsvariable** ist eine Funktion, die jedes Ergebnis im Stichprobenraum auf eine reelle Zahl abbildet, verwendet zur Quantifizierung zufälliger Phänomene.

### 4.4 Définition Française

Une **variable aléatoire** est une fonction qui associe chaque résultat de l'espace échantillon à un nombre réel, utilisée pour quantifier les phénomènes aléatoires.

### 4.5 随机变量的类型

**离散随机变量 (Discrete Random Variable / Diskrete Zufallsvariable / Variable aléatoire discrète)**：

- 取值有限或可数无限的随机变量
- 例如：掷骰子的点数

**连续随机变量 (Continuous Random Variable / Stetige Zufallsvariable / Variable aléatoire continue)**：

- 取值在某个区间内连续变化的随机变量
- 例如：人的身高

## 5. 概率分布 (Probability Distribution / Wahrscheinlichkeitsverteilung / Distribution de probabilité)

### 5.1 中文定义

**概率分布**是描述随机变量取各个值的概率的规律，包括概率质量函数和概率密度函数。

### 5.2 English Definition

A **probability distribution** is a rule describing the probability of a random variable taking various values, including probability mass functions and probability density functions.

### 5.3 Deutsche Definition

Eine **Wahrscheinlichkeitsverteilung** ist eine Regel, die die Wahrscheinlichkeit beschreibt, mit der eine Zufallsvariable verschiedene Werte annimmt, einschließlich Wahrscheinlichkeitsmassenfunktionen und Wahrscheinlichkeitsdichtefunktionen.

### 5.4 Définition Française

Une **distribution de probabilité** est une règle décrivant la probabilité qu'une variable aléatoire prenne diverses valeurs, incluant les fonctions de masse de probabilité et les fonctions de densité de probabilité.

### 5.5 常见概率分布

**二项分布 (Binomial Distribution / Binomialverteilung / Distribution binomiale)**：

- 描述n次独立试验中成功次数的分布
- 参数：n（试验次数），p（成功概率）

**正态分布 (Normal Distribution / Normalverteilung / Distribution normale)**：

- 连续随机变量的重要分布
- 参数：μ（均值），σ²（方差）

**泊松分布 (Poisson Distribution / Poissonverteilung / Distribution de Poisson)**：

- 描述稀有事件发生次数的分布
- 参数：λ（平均发生次数）

## 6. 期望 (Expectation / Erwartungswert / Espérance)

### 6.1 中文定义

**期望**是随机变量的平均值，表示随机变量在长期试验中的中心趋势。

### 6.2 English Definition

**Expectation** is the average value of a random variable, representing the central tendency of the random variable in long-term experiments.

### 6.3 Deutsche Definition

Der **Erwartungswert** ist der Durchschnittswert einer Zufallsvariable, der die zentrale Tendenz der Zufallsvariable in langfristigen Experimenten darstellt.

### 6.4 Définition Française

L'**espérance** est la valeur moyenne d'une variable aléatoire, représentant la tendance centrale de la variable aléatoire dans des expériences à long terme.

### 6.5 期望的性质

**线性性 (Linearity / Linearität / Linéarité)**：

- E(aX + b) = aE(X) + b

**可加性 (Additivity / Additivität / Additivité)**：

- E(X + Y) = E(X) + E(Y)

**独立性 (Independence / Unabhängigkeit / Indépendance)**：

- 如果X和Y独立，则E(XY) = E(X)E(Y)

## 7. 方差 (Variance / Varianz / Variance)

### 7.1 中文定义

**方差**是随机变量与其期望值差的平方的期望，用于衡量随机变量的离散程度。

### 7.2 English Definition

**Variance** is the expectation of the square of the difference between a random variable and its expected value, used to measure the dispersion of a random variable.

### 7.3 Deutsche Definition

Die **Varianz** ist der Erwartungswert des Quadrats der Differenz zwischen einer Zufallsvariable und ihrem Erwartungswert, verwendet zur Messung der Streuung einer Zufallsvariable.

### 7.4 Définition Française

La **variance** est l'espérance du carré de la différence entre une variable aléatoire et son espérance, utilisée pour mesurer la dispersion d'une variable aléatoire.

### 7.5 方差的性质

**非负性 (Non-negativity / Nicht-Negativität / Non-négativité)**：

- Var(X) ≥ 0

**线性变换 (Linear Transformation / Lineare Transformation / Transformation linéaire)**：

- Var(aX + b) = a²Var(X)

**可加性 (Additivity / Additivität / Additivité)**：

- 如果X和Y独立，则Var(X + Y) = Var(X) + Var(Y)

## 8. 统计推断 (Statistical Inference / Statistische Inferenz / Inférence statistique)

### 8.1 中文定义

**统计推断**是基于样本数据对总体参数进行估计和假设检验的过程。

### 8.2 English Definition

**Statistical inference** is the process of estimating population parameters and conducting hypothesis tests based on sample data.

### 8.3 Deutsche Definition

**Statistische Inferenz** ist der Prozess der Schätzung von Populationsparametern und der Durchführung von Hypothesentests basierend auf Stichprobendaten.

### 8.4 Définition Française

L'**inférence statistique** est le processus d'estimation des paramètres de population et de conduite de tests d'hypothèses basés sur des données d'échantillon.

### 8.1 统计推断的方法

**参数估计 (Parameter Estimation / Parameterschätzung / Estimation de paramètres)**：

- 点估计：用单个数值估计参数
- 区间估计：用区间估计参数

**假设检验 (Hypothesis Testing / Hypothesentest / Test d'hypothèse)**：

- 零假设：H₀
- 备择假设：H₁
- 显著性水平：α

## 9. 置信区间 (Confidence Interval / Konfidenzintervall / Intervalle de confiance)

### 9.1 中文定义

**置信区间**是包含总体参数真值的区间，具有指定的置信水平。

### 9.2 English Definition

A **confidence interval** is an interval that contains the true value of a population parameter with a specified confidence level.

### 9.3 Deutsche Definition

Ein **Konfidenzintervall** ist ein Intervall, das den wahren Wert eines Populationsparameters mit einem angegebenen Konfidenzniveau enthält.

### 9.4 Définition Française

Un **intervalle de confiance** est un intervalle qui contient la vraie valeur d'un paramètre de population avec un niveau de confiance spécifié.

### 9.1 置信区间的性质

**置信水平 (Confidence Level / Konfidenzniveau / Niveau de confiance)**：

- 置信区间包含真值的概率
- 通常取90%、95%、99%

**区间长度 (Interval Length / Intervalllänge / Longueur d'intervalle)**：

- 置信区间的长度反映估计精度
- 样本量越大，区间越窄

## 10. 假设检验 (Hypothesis Testing / Hypothesentest / Test d'hypothèse)

### 10.1 中文定义

**假设检验**是基于样本数据对总体参数或分布形式进行判断的统计方法。

### 10.2 English Definition

**Hypothesis testing** is a statistical method for making judgments about population parameters or distribution forms based on sample data.

### 10.3 Deutsche Definition

**Hypothesentest** ist eine statistische Methode zur Beurteilung von Populationsparametern oder Verteilungsformen basierend auf Stichprobendaten.

### 10.4 Définition Française

Le **test d'hypothèse** est une méthode statistique pour faire des jugements sur les paramètres de population ou les formes de distribution basés sur des données d'échantillon.

### 10.1 假设检验的要素

**零假设 (Null Hypothesis / Nullhypothese / Hypothèse nulle)**：

- 要检验的假设，通常表示"无差异"
- 记作H₀

**备择假设 (Alternative Hypothesis / Alternativhypothese / Hypothèse alternative)**：

- 与零假设对立的假设
- 记作H₁

**显著性水平 (Significance Level / Signifikanzniveau / Niveau de signification)**：

- 犯第一类错误的概率
- 通常取0.05或0.01

**p值 (p-value / p-Wert / Valeur p)**：

- 在零假设为真时，获得当前或更极端结果的概率

## 11. 回归分析 (Regression Analysis / Regressionsanalyse / Analyse de régression)

### 11.1 中文定义

**回归分析**是研究变量之间依赖关系的统计方法，用于预测和解释变量间的关系。

### 11.2 English Definition

**Regression analysis** is a statistical method for studying the dependency relationships between variables, used for prediction and explanation of relationships between variables.

### 11.3 Deutsche Definition

**Regressionsanalyse** ist eine statistische Methode zur Untersuchung von Abhängigkeitsbeziehungen zwischen Variablen, verwendet für Vorhersage und Erklärung von Beziehungen zwischen Variablen.

### 11.4 Définition Française

L'**analyse de régression** est une méthode statistique pour étudier les relations de dépendance entre variables, utilisée pour la prédiction et l'explication des relations entre variables.

### 11.1 回归分析的类型

**线性回归 (Linear Regression / Lineare Regression / Régression linéaire)**：

- 因变量与自变量呈线性关系
- 形式：Y = β₀ + β₁X + ε

**多元回归 (Multiple Regression / Multiple Regression / Régression multiple)**：

- 一个因变量与多个自变量的关系
- 形式：Y = β₀ + β₁X₁ + β₂X₂ + ... + βₖXₖ + ε

**非线性回归 (Nonlinear Regression / Nichtlineare Regression / Régression non linéaire)**：

- 因变量与自变量呈非线性关系
- 例如：指数回归、对数回归

## 12. 时间序列分析 (Time Series Analysis / Zeitreihenanalyse / Analyse de séries temporelles)

### 12.1 中文定义

**时间序列分析**是研究按时间顺序排列的数据序列的统计方法，用于预测和模式识别。

### 12.2 English Definition

**Time series analysis** is a statistical method for studying data sequences arranged in chronological order, used for prediction and pattern recognition.

### 12.3 Deutsche Definition

**Zeitreihenanalyse** ist eine statistische Methode zur Untersuchung von Datenreihen, die in chronologischer Reihenfolge angeordnet sind, verwendet für Vorhersage und Mustererkennung.

### 12.4 Définition Française

L'**analyse de séries temporelles** est une méthode statistique pour étudier des séquences de données arrangées dans l'ordre chronologique, utilisée pour la prédiction et la reconnaissance de patterns.

### 12.1 时间序列的组成

**趋势成分 (Trend Component / Trendkomponente / Composante de tendance)**：

- 长期变化趋势

**季节成分 (Seasonal Component / Saisonale Komponente / Composante saisonnière)**：

- 周期性变化

**随机成分 (Random Component / Zufällige Komponente / Composante aléatoire)**：

- 不可预测的随机波动

---

*本定义遵循国际数学标准，确保概率统计概念的多语言一致性和精确性。*
