# 集合论核心概念定义

## 1. 集合 (Set / Menge / Ensemble)

### 中文定义

**集合**是数学中的基本概念，指具有某种特定性质的事物的总体。集合中的每个事物称为该集合的**元素**。

### English Definition

A **set** is a well-defined collection of distinct objects, considered as an object in its own right. The objects that make up a set are called its **elements** or **members**.

### Deutsche Definition

Eine **Menge** ist eine wohldefinierte Sammlung verschiedener Objekte, die als eigenständiges Objekt betrachtet wird. Die Objekte, aus denen eine Menge besteht, werden als ihre **Elemente** oder **Mitglieder** bezeichnet.

### Définition Française

Un **ensemble** est une collection bien définie d'objets distincts, considérée comme un objet en soi. Les objets qui composent un ensemble sont appelés ses **éléments** ou **membres**.

## 2. 集合的表示方法

### 2.1 列举法 (Roster Method / Aufzählungsmethode / Méthode d'énumération)

**中文**：将集合的所有元素一一列举出来，用花括号{}包围。

**English**：List all elements of the set within curly braces {}.

**Deutsch**：Alle Elemente der Menge werden in geschweiften Klammern {} aufgelistet.

**Français**：Énumérer tous les éléments de l'ensemble entre accolades {}.

**示例/Example/Beispiel/Exemple**：

- A = {1, 2, 3, 4, 5}
- B = {a, b, c, d}

### 2.2 描述法 (Set-Builder Notation / Mengenbildungsnotation / Notation en compréhension)

**中文**：用{x | P(x)}的形式表示满足性质P的所有元素x组成的集合。

**English**：Use the form {x | P(x)} to represent the set of all elements x that satisfy property P.

**Deutsch**：Verwenden Sie die Form {x | P(x)} um die Menge aller Elemente x zu repräsentieren, die die Eigenschaft P erfüllen.

**Français**：Utiliser la forme {x | P(x)} pour représenter l'ensemble de tous les éléments x qui satisfont la propriété P.

**示例/Example/Beispiel/Exemple**：

- A = {x | x ∈ ℕ ∧ 1 ≤ x ≤ 5}
- B = {x | x² = 4}

## 3. 集合的基本性质

### 3.1 确定性 (Determinacy / Determiniertheit / Détermination)

**中文**：对于任何对象，都能明确判断它是否属于某个集合。

**English**：For any object, it can be clearly determined whether it belongs to a given set.

**Deutsch**：Für jedes Objekt kann eindeutig bestimmt werden, ob es zu einer gegebenen Menge gehört.

**Français**：Pour tout objet, on peut déterminer clairement s'il appartient à un ensemble donné.

### 3.2 互异性 (Distinctness / Verschiedenheit / Distinction)

**中文**：集合中的元素各不相同，没有重复。

**English**：Elements in a set are distinct, with no repetition.

**Deutsch**：Elemente in einer Menge sind verschieden, ohne Wiederholung.

**Français**：Les éléments d'un ensemble sont distincts, sans répétition.

### 3.3 无序性 (Unorderedness / Ungeordnetheit / Non-ordre)

**中文**：集合中元素的排列顺序不影响集合的同一性。

**English**：The order of elements in a set does not affect the identity of the set.

**Deutsch**：Die Reihenfolge der Elemente in einer Menge beeinflusst nicht die Identität der Menge.

**Français**：L'ordre des éléments dans un ensemble n'affecte pas l'identité de l'ensemble.

## 4. 特殊集合

### 4.1 空集 (Empty Set / Leere Menge / Ensemble vide)

**中文**：不包含任何元素的集合，记作∅或{}。

**English**：A set containing no elements, denoted by ∅ or {}.

**Deutsch**：Eine Menge, die keine Elemente enthält, bezeichnet als ∅ oder {}.

**Français**：Un ensemble ne contenant aucun élément, noté ∅ ou {}.

### 4.2 单元素集 (Singleton / Einermenge / Singleton)

**中文**：只包含一个元素的集合。

**English**：A set containing exactly one element.

**Deutsch**：Eine Menge, die genau ein Element enthält.

**Français**：Un ensemble contenant exactement un élément.

**示例/Example/Beispiel/Exemple**：

- {1}, {a}, {∅}

## 5. 集合的基数

### 5.1 有限集 (Finite Set / Endliche Menge / Ensemble fini)

**中文**：元素个数有限的集合。

**English**：A set with a finite number of elements.

**Deutsch**：Eine Menge mit endlich vielen Elementen.

**Français**：Un ensemble avec un nombre fini d'éléments.

### 5.2 无限集 (Infinite Set / Unendliche Menge / Ensemble infini)

**中文**：元素个数无限的集合。

**English**：A set with an infinite number of elements.

**Deutsch**：Eine Menge mit unendlich vielen Elementen.

**Français**：Un ensemble avec un nombre infini d'éléments.

## 6. 集合的运算

### 6.1 并集 (Union / Vereinigung / Union)

**中文**：两个集合A和B的并集是包含A和B中所有元素的集合，记作A∪B。

**English**：The union of two sets A and B is the set containing all elements from both A and B, denoted A∪B.

**Deutsch**：Die Vereinigung zweier Mengen A und B ist die Menge aller Elemente aus A und B, bezeichnet als A∪B.

**Français**：L'union de deux ensembles A et B est l'ensemble contenant tous les éléments de A et B, noté A∪B.

### 6.2 交集 (Intersection / Durchschnitt / Intersection)

**中文**：两个集合A和B的交集是同时属于A和B的所有元素的集合，记作A∩B。

**English**：The intersection of two sets A and B is the set of all elements that belong to both A and B, denoted A∩B.

**Deutsch**：Der Durchschnitt zweier Mengen A und B ist die Menge aller Elemente, die sowohl zu A als auch zu B gehören, bezeichnet als A∩B.

**Français**：L'intersection de deux ensembles A et B est l'ensemble de tous les éléments qui appartiennent à la fois à A et B, noté A∩B.

### 6.3 差集 (Difference / Differenz / Différence)

**中文**：集合A与B的差集是属于A但不属于B的所有元素的集合，记作A-B或A\B。

**English**：The difference of sets A and B is the set of all elements that belong to A but not to B, denoted A-B or A\B.

**Deutsch**：Die Differenz der Mengen A und B ist die Menge aller Elemente, die zu A gehören, aber nicht zu B, bezeichnet als A-B oder A\B.

**Français**：La différence des ensembles A et B est l'ensemble de tous les éléments qui appartiennent à A mais pas à B, noté A-B ou A\B.

## 7. 集合关系

### 7.1 包含关系 (Subset / Teilmenge / Sous-ensemble)

**中文**：如果集合A的每个元素都属于集合B，则称A是B的子集，记作A⊆B。

**English**：If every element of set A belongs to set B, then A is called a subset of B, denoted A⊆B.

**Deutsch**：Wenn jedes Element der Menge A zur Menge B gehört, dann heißt A eine Teilmenge von B, bezeichnet als A⊆B.

**Français**：Si chaque élément de l'ensemble A appartient à l'ensemble B, alors A est appelé un sous-ensemble de B, noté A⊆B.

### 7.2 真子集 (Proper Subset / Echte Teilmenge / Sous-ensemble propre)

**中文**：如果A是B的子集且A≠B，则称A是B的真子集，记作A⊂B。

**English**：If A is a subset of B and A≠B, then A is called a proper subset of B, denoted A⊂B.

**Deutsch**：Wenn A eine Teilmenge von B ist und A≠B, dann heißt A eine echte Teilmenge von B, bezeichnet als A⊂B.

**Français**：Si A est un sous-ensemble de B et A≠B, alors A est appelé un sous-ensemble propre de B, noté A⊂B.

---

*本定义遵循国际数学标准，确保概念精确性和多语言一致性。*
