# 函数与映射核心概念定义

## 1. 函数 (Function / Funktion / Fonction)

### 中文定义

**函数**是数学中的基本概念，指两个集合之间的一种特殊关系，其中第一个集合（定义域）的每个元素都唯一对应第二个集合（值域）中的一个元素。

### English Definition

A **function** is a fundamental mathematical concept that represents a special relationship between two sets, where each element of the first set (domain) is uniquely mapped to exactly one element of the second set (codomain).

### Deutsche Definition

Eine **Funktion** ist ein grundlegendes mathematisches Konzept, das eine spezielle Beziehung zwischen zwei Mengen darstellt, wobei jedes Element der ersten Menge (Definitionsbereich) eindeutig einem Element der zweiten Menge (Wertebereich) zugeordnet wird.

### Définition Française

Une **fonction** est un concept mathématique fondamental qui représente une relation spéciale entre deux ensembles, où chaque élément du premier ensemble (domaine de définition) est associé de manière unique à exactement un élément du second ensemble (ensemble d'arrivée).

## 2. 映射 (Mapping / Abbildung / Application)

### 1中文定义

**映射**是函数概念的推广，指从一个集合到另一个集合的对应关系，可以是单射、满射或双射。

### 1English Definition

A **mapping** is a generalization of the function concept, representing a correspondence from one set to another, which can be injective, surjective, or bijective.

### 1Deutsche Definition

Eine **Abbildung** ist eine Verallgemeinerung des Funktionsbegriffs und stellt eine Zuordnung von einer Menge zu einer anderen dar, die injektiv, surjektiv oder bijektiv sein kann.

### 1Définition Française

Une **application** est une généralisation du concept de fonction, représentant une correspondance d'un ensemble vers un autre, qui peut être injective, surjective ou bijective.

## 3. 函数的基本要素

### 3.1 定义域 (Domain / Definitionsbereich / Domaine de définition)

**中文**：函数中自变量的取值范围，记作dom(f)。

**English**：The set of all possible input values for a function, denoted dom(f).

**Deutsch**：Die Menge aller möglichen Eingabewerte für eine Funktion, bezeichnet als dom(f).

**Français**：L'ensemble de toutes les valeurs d'entrée possibles pour une fonction, noté dom(f).

### 3.2 值域 (Range / Wertebereich / Ensemble image)

**中文**：函数中因变量的取值范围，记作ran(f)。

**English**：The set of all possible output values for a function, denoted ran(f).

**Deutsch**：Die Menge aller möglichen Ausgabewerte für eine Funktion, bezeichnet als ran(f).

**Français**：L'ensemble de toutes les valeurs de sortie possibles pour une fonction, noté ran(f).

### 3.3 对应关系 (Correspondence / Zuordnung / Correspondance)

**中文**：定义域中每个元素与值域中唯一元素的对应关系。

**English**：The correspondence between each element in the domain and a unique element in the range.

**Deutsch**：Die Zuordnung zwischen jedem Element im Definitionsbereich und einem eindeutigen Element im Wertebereich.

**Français**：La correspondance entre chaque élément du domaine de définition et un élément unique de l'ensemble image.

## 4. 函数的表示方法

### 4.1 解析式表示 (Analytical Representation / Analytische Darstellung / Représentation analytique)

**中文**：用数学公式表示函数关系。

**English**：Representing function relationships using mathematical formulas.

**Deutsch**：Darstellung von Funktionsbeziehungen durch mathematische Formeln.

**Français**：Représentation des relations fonctionnelles à l'aide de formules mathématiques.

**示例/Example/Beispiel/Exemple**：

- f(x) = x² + 2x + 1
- g(x) = sin(x)
- h(x) = log(x)

### 4.2 表格表示 (Tabular Representation / Tabellarische Darstellung / Représentation tabulaire)

**中文**：用表格列出函数值。

**English**：Listing function values in a table.

**Deutsch**：Auflistung von Funktionswerten in einer Tabelle.

**Français**：Liste des valeurs de fonction dans un tableau.

**示例/Example/Beispiel/Exemple**：

| x | f(x) |
|---|------|
| 0 | 1    |
| 1 | 4    |
| 2 | 9    |
| 3 | 16   |

### 4.3 图形表示 (Graphical Representation / Grafische Darstellung / Représentation graphique)

**中文**：用坐标系中的曲线表示函数。

**English**：Representing functions using curves in a coordinate system.

**Deutsch**：Darstellung von Funktionen durch Kurven in einem Koordinatensystem.

**Français**：Représentation des fonctions par des courbes dans un système de coordonnées.

## 5. 函数的类型

### 5.1 单射函数 (Injective Function / Injektive Funktion / Fonction injective)

**中文**：定义域中不同元素对应值域中不同元素的函数。

**English**：A function where different elements in the domain correspond to different elements in the range.

**Deutsch**：Eine Funktion, bei der verschiedene Elemente im Definitionsbereich verschiedenen Elementen im Wertebereich entsprechen.

**Français**：Une fonction où différents éléments du domaine correspondent à différents éléments de l'ensemble image.

**数学定义**：∀x₁, x₂ ∈ dom(f), x₁ ≠ x₂ → f(x₁) ≠ f(x₂)

### 5.2 满射函数 (Surjective Function / Surjektive Funktion / Fonction surjective)

**中文**：值域中每个元素都是定义域中某个元素的像的函数。

**English**：A function where every element in the range is the image of some element in the domain.

**Deutsch**：Eine Funktion, bei der jedes Element im Wertebereich das Bild eines Elements im Definitionsbereich ist.

**Français**：Une fonction où chaque élément de l'ensemble image est l'image d'un élément du domaine.

**数学定义**：∀y ∈ ran(f), ∃x ∈ dom(f), f(x) = y

### 5.3 双射函数 (Bijective Function / Bijektive Funktion / Fonction bijective)

**中文**：既是单射又是满射的函数。

**English**：A function that is both injective and surjective.

**Deutsch**：Eine Funktion, die sowohl injektiv als auch surjektiv ist.

**Français**：Une fonction qui est à la fois injective et surjective.

**数学定义**：f是双射 ⇔ f是单射 ∧ f是满射

## 6. 函数的运算

### 6.1 函数复合 (Function Composition / Funktionskomposition / Composition de fonctions)

**中文**：两个函数f和g的复合函数记作(g∘f)(x) = g(f(x))。

**English**：The composition of two functions f and g is denoted (g∘f)(x) = g(f(x)).

**Deutsch**：Die Komposition zweier Funktionen f und g wird bezeichnet als (g∘f)(x) = g(f(x)).

**Français**：La composition de deux fonctions f et g est notée (g∘f)(x) = g(f(x)).

### 6.2 反函数 (Inverse Function / Umkehrfunktion / Fonction réciproque)

**中文**：如果函数f是双射，则存在反函数f⁻¹，满足f⁻¹(f(x)) = x。

**English**：If function f is bijective, then there exists an inverse function f⁻¹ such that f⁻¹(f(x)) = x.

**Deutsch**：Wenn die Funktion f bijektiv ist, dann existiert eine Umkehrfunktion f⁻¹ mit f⁻¹(f(x)) = x.

**Français**：Si la fonction f est bijective, alors il existe une fonction réciproque f⁻¹ telle que f⁻¹(f(x)) = x.

## 7. 特殊函数

### 7.1 常数函数 (Constant Function / Konstante Funktion / Fonction constante)

**中文**：对于所有x，函数值都相同的函数。

**English**：A function where the function value is the same for all x.

**Deutsch**：Eine Funktion, bei der der Funktionswert für alle x gleich ist.

**Français**：Une fonction où la valeur de la fonction est la même pour tous les x.

**示例/Example/Beispiel/Exemple**：f(x) = c

### 7.2 恒等函数 (Identity Function / Identitätsfunktion / Fonction identité)

**中文**：将每个元素映射到自身的函数。

**English**：A function that maps each element to itself.

**Deutsch**：Eine Funktion, die jedes Element auf sich selbst abbildet.

**Français**：Une fonction qui associe chaque élément à lui-même.

**示例/Example/Beispiel/Exemple**：f(x) = x

### 7.3 多项式函数 (Polynomial Function / Polynomfunktion / Fonction polynomiale)

**中文**：形如f(x) = aₙxⁿ + aₙ₋₁xⁿ⁻¹ + ... + a₁x + a₀的函数。

**English**：A function of the form f(x) = aₙxⁿ + aₙ₋₁xⁿ⁻¹ + ... + a₁x + a₀.

**Deutsch**：Eine Funktion der Form f(x) = aₙxⁿ + aₙ₋₁xⁿ⁻¹ + ... + a₁x + a₀.

**Français**：Une fonction de la forme f(x) = aₙxⁿ + aₙ₋₁xⁿ⁻¹ + ... + a₁x + a₀.

## 8. 函数的性质

### 8.1 单调性 (Monotonicity / Monotonie / Monotonie)

**中文**：函数在某个区间内的增减性质。

**English**：The increasing or decreasing property of a function over an interval.

**Deutsch**：Die steigende oder fallende Eigenschaft einer Funktion über einem Intervall.

**Français**：La propriété croissante ou décroissante d'une fonction sur un intervalle.

**单调递增**：∀x₁, x₂ ∈ I, x₁ < x₂ → f(x₁) < f(x₂)
**单调递减**：∀x₁, x₂ ∈ I, x₁ < x₂ → f(x₁) > f(x₂)

### 8.2 奇偶性 (Parity / Parität / Parité)

**中文**：函数关于原点的对称性质。

**English**：The symmetry property of a function with respect to the origin.

**Deutsch**：Die Symmetrieeigenschaft einer Funktion bezüglich des Ursprungs.

**Français**：La propriété de symétrie d'une fonction par rapport à l'origine.

**奇函数**：f(-x) = -f(x)
**偶函数**：f(-x) = f(x)

### 8.3 周期性 (Periodicity / Periodizität / Périodicité)

**中文**：函数值按固定周期重复的性质。

**English**：The property where function values repeat at fixed intervals.

**Deutsch**：Die Eigenschaft, dass Funktionswerte in festen Intervallen wiederholen.

**Français**：La propriété où les valeurs de fonction se répètent à intervalles fixes.

**数学定义**：∃T > 0, ∀x ∈ dom(f), f(x + T) = f(x)

---

*本定义遵循国际数学标准，确保函数与映射概念的多语言一致性和精确性。*
