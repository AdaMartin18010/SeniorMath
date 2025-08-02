# 极限与连续性核心概念定义

## 1. 极限 (Limit / Grenzwert / Limite)

### 中文定义

**极限**是微积分中的基本概念，描述当自变量趋近于某个值时，函数值趋近于的确定数值。极限是研究函数局部性质的重要工具。

### English Definition

A **limit** is a fundamental concept in calculus that describes the definite value that a function approaches as the independent variable approaches a certain value. Limits are essential tools for studying local properties of functions.

### Deutsche Definition

Ein **Grenzwert** ist ein grundlegendes Konzept der Analysis, das den bestimmten Wert beschreibt, dem sich eine Funktion annähert, wenn sich die unabhängige Variable einem bestimmten Wert annähert. Grenzwerte sind wesentliche Werkzeuge zur Untersuchung lokaler Eigenschaften von Funktionen.

### Définition Française

Une **limite** est un concept fondamental du calcul différentiel qui décrit la valeur définie vers laquelle tend une fonction lorsque la variable indépendante tend vers une certaine valeur. Les limites sont des outils essentiels pour étudier les propriétés locales des fonctions.

## 2. 函数极限的严格定义

### 2.1 ε-δ定义 (Epsilon-Delta Definition / Epsilon-Delta-Definition / Définition epsilon-delta)

**中文**：对于函数f(x)，当x趋近于a时，f(x)的极限为L，记作lim(x→a) f(x) = L，如果对于任意ε > 0，存在δ > 0，使得当0 < |x - a| < δ时，有|f(x) - L| < ε。

**English**：For a function f(x), the limit of f(x) as x approaches a is L, denoted lim(x→a) f(x) = L, if for every ε > 0, there exists δ > 0 such that whenever 0 < |x - a| < δ, we have |f(x) - L| < ε.

**Deutsch**：Für eine Funktion f(x) ist der Grenzwert von f(x) für x gegen a gleich L, bezeichnet als lim(x→a) f(x) = L, wenn für jedes ε > 0 ein δ > 0 existiert, so dass für alle x mit 0 < |x - a| < δ gilt |f(x) - L| < ε.

**Français**：Pour une fonction f(x), la limite de f(x) quand x tend vers a est L, notée lim(x→a) f(x) = L, si pour tout ε > 0, il existe δ > 0 tel que pour tout x avec 0 < |x - a| < δ, on a |f(x) - L| < ε.

**数学符号**：∀ε > 0, ∃δ > 0, ∀x ∈ dom(f), 0 < |x - a| < δ → |f(x) - L| < ε

### 2.2 单侧极限 (One-Sided Limit / Einseitiger Grenzwert / Limite unilatérale)

**中文**：当x从左侧或右侧趋近于a时，函数f(x)的极限。

**English**：The limit of function f(x) as x approaches a from the left or right side.

**Deutsch**：Der Grenzwert der Funktion f(x) für x gegen a von der linken oder rechten Seite.

**Français**：La limite de la fonction f(x) quand x tend vers a depuis le côté gauche ou droit.

**左极限**：lim(x→a⁻) f(x) = L
**右极限**：lim(x→a⁺) f(x) = L

## 3. 极限的性质

### 3.1 极限的唯一性 (Uniqueness of Limit / Eindeutigkeit des Grenzwerts / Unicité de la limite)

**中文**：如果函数在某个点的极限存在，那么这个极限是唯一的。

**English**：If the limit of a function exists at a point, then this limit is unique.

**Deutsch**：Wenn der Grenzwert einer Funktion an einem Punkt existiert, dann ist dieser Grenzwert eindeutig.

**Français**：Si la limite d'une fonction existe en un point, alors cette limite est unique.

### 3.2 极限的局部有界性 (Local Boundedness / Lokale Beschränktheit / Bornitude locale)

**中文**：如果函数在某个点的极限存在，那么函数在该点的某个邻域内有界。

**English**：If the limit of a function exists at a point, then the function is bounded in some neighborhood of that point.

**Deutsch**：Wenn der Grenzwert einer Funktion an einem Punkt existiert, dann ist die Funktion in einer Umgebung dieses Punktes beschränkt.

**Français**：Si la limite d'une fonction existe en un point, alors la fonction est bornée dans un voisinage de ce point.

### 3.3 极限的运算性质 (Operational Properties / Rechenregeln / Propriétés opérationnelles)

**中文**：极限运算满足线性性质、乘法性质和除法性质。

**English**：Limit operations satisfy linearity, multiplication, and division properties.

**Deutsch**：Grenzwertoperationen erfüllen Linearität, Multiplikation und Divisionsregeln.

**Français**：Les opérations de limite satisfont les propriétés de linéarité, multiplication et division.

**线性性质**：lim(x→a) [αf(x) + βg(x)] = αlim(x→a) f(x) + βlim(x→a) g(x)
**乘法性质**：lim(x→a) [f(x)·g(x)] = lim(x→a) f(x) · lim(x→a) g(x)
**除法性质**：lim(x→a) [f(x)/g(x)] = lim(x→a) f(x) / lim(x→a) g(x) (当分母极限不为0时)

## 4. 连续性 (Continuity / Stetigkeit / Continuité)

### 4.1 连续性的定义

**中文**：函数f(x)在点a处连续，如果lim(x→a) f(x) = f(a)。

**English**：A function f(x) is continuous at point a if lim(x→a) f(x) = f(a).

**Deutsch**：Eine Funktion f(x) ist stetig an der Stelle a, wenn lim(x→a) f(x) = f(a).

**Français**：Une fonction f(x) est continue au point a si lim(x→a) f(x) = f(a).

**数学定义**：∀ε > 0, ∃δ > 0, ∀x ∈ dom(f), |x - a| < δ → |f(x) - f(a)| < ε

### 4.2 连续性的等价条件

**中文**：函数在点a处连续的等价条件。

**English**：Equivalent conditions for continuity of a function at point a.

**Deutsch**：Äquivalente Bedingungen für die Stetigkeit einer Funktion an der Stelle a.

**Français**：Conditions équivalentes pour la continuité d'une fonction au point a.

**条件1**：lim(x→a) f(x) = f(a)
**条件2**：lim(x→a⁺) f(x) = lim(x→a⁻) f(x) = f(a)
**条件3**：对于任意收敛于a的序列{xₙ}，有lim(n→∞) f(xₙ) = f(a)

### 4.3 连续函数的性质

**中文**：连续函数具有重要的性质。

**English**：Continuous functions have important properties.

**Deutsch**：Stetige Funktionen haben wichtige Eigenschaften.

**Français**：Les fonctions continues ont des propriétés importantes.

**中间值定理**：如果f在[a,b]上连续，且f(a) < c < f(b)，则存在ξ ∈ (a,b)使得f(ξ) = c。

**最值定理**：如果f在[a,b]上连续，则f在[a,b]上取得最大值和最小值。

**一致连续性**：如果f在区间I上连续，且对于任意ε > 0，存在δ > 0，使得对于任意x₁, x₂ ∈ I，当|x₁ - x₂| < δ时，有|f(x₁) - f(x₂)| < ε。

## 5. 无穷极限 (Infinite Limits / Unendliche Grenzwerte / Limites infinies)

### 5.1 正无穷极限

**中文**：当x趋近于a时，f(x)趋近于正无穷，记作lim(x→a) f(x) = +∞。

**English**：As x approaches a, f(x) approaches positive infinity, denoted lim(x→a) f(x) = +∞.

**Deutsch**：Für x gegen a strebt f(x) gegen plus unendlich, bezeichnet als lim(x→a) f(x) = +∞.

**Français**：Quand x tend vers a, f(x) tend vers plus l'infini, noté lim(x→a) f(x) = +∞.

**数学定义**：∀M > 0, ∃δ > 0, ∀x ∈ dom(f), 0 < |x - a| < δ → f(x) > M

### 5.2 负无穷极限

**中文**：当x趋近于a时，f(x)趋近于负无穷，记作lim(x→a) f(x) = -∞。

**English**：As x approaches a, f(x) approaches negative infinity, denoted lim(x→a) f(x) = -∞.

**Deutsch**：Für x gegen a strebt f(x) gegen minus unendlich, bezeichnet als lim(x→a) f(x) = -∞.

**Français**：Quand x tend vers a, f(x) tend vers moins l'infini, noté lim(x→a) f(x) = -∞.

**数学定义**：∀M < 0, ∃δ > 0, ∀x ∈ dom(f), 0 < |x - a| < δ → f(x) < M

## 6. 极限的计算方法

### 6.1 直接代入法

**中文**：对于连续函数，可以直接代入计算极限。

**English**：For continuous functions, limits can be calculated by direct substitution.

**Deutsch**：Für stetige Funktionen können Grenzwerte durch direkte Einsetzung berechnet werden.

**Français**：Pour les fonctions continues, les limites peuvent être calculées par substitution directe.

**示例/Example/Beispiel/Exemple**：

- lim(x→2) (x² + 3x + 1) = 2² + 3·2 + 1 = 11

### 6.2 因式分解法

**中文**：对于0/0型不定式，可以通过因式分解消去零因子。

**English**：For 0/0 indeterminate forms, zero factors can be eliminated by factoring.

**Deutsch**：Für 0/0 unbestimmte Formen können Nullfaktoren durch Faktorisierung eliminiert werden.

**Français**：Pour les formes indéterminées 0/0, les facteurs nuls peuvent être éliminés par factorisation.

**示例/Example/Beispiel/Exemple**：

- lim(x→2) (x² - 4)/(x - 2) = lim(x→2) (x + 2) = 4

### 6.3 有理化法

**中文**：对于含有根号的不定式，可以通过有理化处理。

**English**：For indeterminate forms containing radicals, rationalization can be used.

**Deutsch**：Für unbestimmte Formen mit Wurzeln kann Rationalisierung verwendet werden.

**Français**：Pour les formes indéterminées contenant des radicaux, la rationalisation peut être utilisée.

**示例/Example/Beispiel/Exemple**：

- lim(x→0) (√(x + 1) - 1)/x = lim(x→0) 1/(√(x + 1) + 1) = 1/2

### 6.4 夹逼定理

**中文**：如果g(x) ≤ f(x) ≤ h(x)，且lim(x→a) g(x) = lim(x→a) h(x) = L，则lim(x→a) f(x) = L。

**English**：If g(x) ≤ f(x) ≤ h(x) and lim(x→a) g(x) = lim(x→a) h(x) = L, then lim(x→a) f(x) = L.

**Deutsch**：Wenn g(x) ≤ f(x) ≤ h(x) und lim(x→a) g(x) = lim(x→a) h(x) = L, dann ist lim(x→a) f(x) = L.

**Français**：Si g(x) ≤ f(x) ≤ h(x) et lim(x→a) g(x) = lim(x→a) h(x) = L, alors lim(x→a) f(x) = L.

## 7. 重要极限

### 7.1 基本极限

**中文**：一些重要的基本极限。

**English**：Some important basic limits.

**Deutsch**：Einige wichtige grundlegende Grenzwerte.

**Français**：Quelques limites de base importantes.

**lim(x→0) sin(x)/x = 1**
**lim(x→0) (1 + x)^(1/x) = e**
**lim(x→∞) (1 + 1/x)^x = e**
**lim(x→0) (e^x - 1)/x = 1**

### 7.2 无穷小量

**中文**：当x→0时，一些函数的无穷小量阶数。

**English**：Orders of infinitesimals for some functions as x→0.

**Deutsch**：Ordnungen von Infinitesimalen für einige Funktionen für x→0.

**Français**：Ordres d'infiniment petits pour certaines fonctions quand x→0.

**sin(x) ~ x (一阶无穷小)**
**1 - cos(x) ~ x²/2 (二阶无穷小)**
**tan(x) ~ x (一阶无穷小)**
**ln(1 + x) ~ x (一阶无穷小)**

## 8. 极限的应用

### 8.1 导数定义

**中文**：函数f(x)在点a处的导数定义为f'(a) = lim(h→0) [f(a + h) - f(a)]/h。

**English**：The derivative of function f(x) at point a is defined as f'(a) = lim(h→0) [f(a + h) - f(a)]/h.

**Deutsch**：Die Ableitung der Funktion f(x) an der Stelle a ist definiert als f'(a) = lim(h→0) [f(a + h) - f(a)]/h.

**Français**：La dérivée de la fonction f(x) au point a est définie comme f'(a) = lim(h→0) [f(a + h) - f(a)]/h.

### 8.2 积分定义

**中文**：定积分可以通过极限定义。

**English**：Definite integrals can be defined through limits.

**Deutsch**：Bestimmte Integrale können durch Grenzwerte definiert werden.

**Français**：Les intégrales définies peuvent être définies par des limites.

**黎曼和极限**：∫[a,b] f(x)dx = lim(n→∞) Σ[i=1,n] f(ξᵢ)Δxᵢ

---

*本定义遵循国际数学标准，确保极限与连续性概念的多语言一致性和精确性。*
