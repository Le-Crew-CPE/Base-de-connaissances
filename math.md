# 📐 Mathématiques en Markdown + LaTeX — Référence complète

---

## 1. Fonctions

```latex
% Définition d'une fonction
$$f : \mathbb{R} \to \mathbb{R}, \quad x \mapsto x^2 + 3x - 5$$

% Composition
$$(f \circ g)(x) = f(g(x))$$

% Valeur absolue
$$|x| = \begin{cases} x & \text{si } x \geq 0 \\ -x & \text{si } x < 0 \end{cases}$$

% Fonction exponentielle et logarithme
$$e^{x+y} = e^x \cdot e^y \qquad \ln(ab) = \ln a + \ln b$$

% Trigonométrie
$$\cos^2(x) + \sin^2(x) = 1$$
```

**Rendu :**

$$f : \mathbb{R} \to \mathbb{R}, \quad x \mapsto x^2 + 3x - 5$$

$$(f \circ g)(x) = f(g(x))$$

$$|x| = \begin{cases} x & \text{si } x \geq 0 \\ -x & \text{si } x < 0 \end{cases}$$

$$e^{x+y} = e^x \cdot e^y \qquad \ln(ab) = \ln a + \ln b$$

$$\cos^2(x) + \sin^2(x) = 1$$

---

## 2. Matrices

```latex
% Matrice simple (parenthèses)
$$A = \begin{pmatrix} a & b \\ c & d \end{pmatrix}$$

% Matrice avec crochets
$$B = \begin{bmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \\ 7 & 8 & 9 \end{bmatrix}$$

% Déterminant (barres)
$$\det(A) = \begin{vmatrix} a & b \\ c & d \end{vmatrix} = ad - bc$$

% Matrice identité
$$I_3 = \begin{pmatrix} 1 & 0 & 0 \\ 0 & 1 & 0 \\ 0 & 0 & 1 \end{pmatrix}$$

% Transposée
$$A^T = \begin{pmatrix} a & c \\ b & d \end{pmatrix}$$
```

**Rendu :**

$$A = \begin{pmatrix} a & b \\ c & d \end{pmatrix}$$

$$B = \begin{bmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \\ 7 & 8 & 9 \end{bmatrix}$$

$$\det(A) = \begin{vmatrix} a & b \\ c & d \end{vmatrix} = ad - bc$$

$$I_3 = \begin{pmatrix} 1 & 0 & 0 \\ 0 & 1 & 0 \\ 0 & 0 & 1 \end{pmatrix}$$

---

## 3. Tableau de variations

Les tableaux de variations se font avec `array` en LaTeX :

```latex
$$\begin{array}{|c|ccccc|}
\hline
x      & -\infty &   & 1  &   & +\infty \\
\hline
f'(x)  &         & - & 0  & + &         \\
\hline
        & +\infty &   &    &   & +\infty \\
f(x)   &         & \searrow &   & \nearrow &  \\
        &         &   & -3 &   &         \\
\hline
\end{array}$$
```

**Rendu :**

$$\begin{array}{|c|ccccc|}
\hline
x      & -\infty &   & 1  &   & +\infty \\
\hline
f'(x)  &         & - & 0  & + &         \\
\hline
        & +\infty &   &    &   & +\infty \\
f(x)   &         & \searrow &   & \nearrow &  \\
        &         &   & -3 &   &         \\
\hline
\end{array}$$

---

## 4. Exposants & Indices

```latex
% Exposants
$x^2 \quad x^{n+1} \quad e^{-x^2} \quad 2^{32}$

% Indices
$a_n \quad u_{n+1} \quad x_{i,j}$

% Les deux combinés
$\sum_{i=0}^{n} \quad \int_a^b \quad A_i^j$

% Puissances de puissances
$\left(x^2\right)^3 = x^6$
```

**Rendu :**

$$x^2 \quad x^{n+1} \quad e^{-x^2} \quad 2^{32}$$

$$a_n \quad u_{n+1} \quad x_{i,j}$$

$$\left(x^2\right)^3 = x^6$$

---

## 5. Limites

```latex
% Limite simple
$$\lim_{x \to +\infty} \frac{1}{x} = 0$$

% Limite à gauche / droite
$$\lim_{x \to 0^+} \ln(x) = -\infty \qquad \lim_{x \to 0^-} \frac{1}{x} = -\infty$$

% Forme indéterminée classique
$$\lim_{x \to 0} \frac{\sin x}{x} = 1$$

% Limite d'une suite
$$\lim_{n \to +\infty} \left(1 + \frac{1}{n}\right)^n = e$$

% Règle de L'Hôpital
$$\lim_{x \to a} \frac{f(x)}{g(x)} = \lim_{x \to a} \frac{f'(x)}{g'(x)}$$
```

**Rendu :**

$$\lim_{x \to +\infty} \frac{1}{x} = 0$$

$$\lim_{x \to 0^+} \ln(x) = -\infty \qquad \lim_{x \to 0^-} \frac{1}{x} = -\infty$$

$$\lim_{x \to 0} \frac{\sin x}{x} = 1$$

$$\lim_{n \to +\infty} \left(1 + \frac{1}{n}\right)^n = e$$

---

## 6. Sommes & Produits

```latex
% Somme finie
$$\sum_{k=1}^{n} k = \frac{n(n+1)}{2}$$

% Somme infinie (série)
$$\sum_{n=0}^{+\infty} \frac{x^n}{n!} = e^x$$

% Produit
$$\prod_{k=1}^{n} k = n!$$

% Double somme
$$\sum_{i=1}^{m} \sum_{j=1}^{n} a_{ij}$$

% Série de Riemann
$$\sum_{n=1}^{\infty} \frac{1}{n^2} = \frac{\pi^2}{6}$$
```

**Rendu :**

$$\sum_{k=1}^{n} k = \frac{n(n+1)}{2}$$

$$\sum_{n=0}^{+\infty} \frac{x^n}{n!} = e^x$$

$$\prod_{k=1}^{n} k = n!$$

$$\sum_{n=1}^{\infty} \frac{1}{n^2} = \frac{\pi^2}{6}$$

---

## 7. Systèmes d'équations

```latex
% Système 2x2
$$\begin{cases} 2x + 3y = 7 \\ x - y = 1 \end{cases}$$

% Système 3x3
$$\begin{cases} x + y + z = 6 \\ 2x - y + z = 3 \\ x + 2y - z = 2 \end{cases}$$

% Système avec conditions
$$f(x) = \begin{cases} x^2 & \text{si } x < 0 \\ 0 & \text{si } x = 0 \\ \sqrt{x} & \text{si } x > 0 \end{cases}$$
```

**Rendu :**

$$\begin{cases} 2x + 3y = 7 \\ x - y = 1 \end{cases}$$

$$\begin{cases} x + y + z = 6 \\ 2x - y + z = 3 \\ x + 2y - z = 2 \end{cases}$$

$$f(x) = \begin{cases} x^2 & \text{si } x < 0 \\ 0 & \text{si } x = 0 \\ \sqrt{x} & \text{si } x > 0 \end{cases}$$

---

## 8. Intégrales

```latex
% Intégrale définie
$$\int_a^b f(x)\, dx$$

% Intégrale indéfinie
$$\int x^n\, dx = \frac{x^{n+1}}{n+1} + C$$

% Intégrale par parties
$$\int u\, dv = uv - \int v\, du$$

% Exemples classiques
$$\int_0^{\pi} \sin(x)\, dx = 2$$

$$\int_{-\infty}^{+\infty} e^{-x^2}\, dx = \sqrt{\pi}$$

% Primitive
$$F(x) = \int_a^x f(t)\, dt \implies F'(x) = f(x)$$
```

**Rendu :**

$$\int_a^b f(x)\, dx$$

$$\int x^n\, dx = \frac{x^{n+1}}{n+1} + C$$

$$\int_0^{\pi} \sin(x)\, dx = 2$$

$$\int_{-\infty}^{+\infty} e^{-x^2}\, dx = \sqrt{\pi}$$

---

## 9. Intégrales doubles & triples

```latex
% Intégrale double
$$\iint_D f(x, y)\, dx\, dy$$

% Intégrale double avec bornes
$$\int_0^1 \int_0^x f(x,y)\, dy\, dx$$

% Intégrale triple
$$\iiint_V f(x, y, z)\, dx\, dy\, dz$$

% Intégrale curviligne
$$\oint_C \vec{F} \cdot d\vec{r}$$

% Changement de variable (coordonnées polaires)
$$\iint_D f(r,\theta)\, r\, dr\, d\theta$$
```

**Rendu :**

$$\iint_D f(x, y)\, dx\, dy$$

$$\int_0^1 \int_0^x f(x,y)\, dy\, dx$$

$$\iiint_V f(x, y, z)\, dx\, dy\, dz$$

$$\oint_C \vec{F} \cdot d\vec{r}$$

---

## 10. Fractions & Racines

```latex
% Fractions simples
$$\frac{a}{b} \qquad \frac{x^2 + 1}{x - 3}$$

% Fractions imbriquées
$$\cfrac{1}{1 + \cfrac{1}{1 + \cfrac{1}{x}}}$$

% Racine carrée
$$\sqrt{x} \qquad \sqrt{x^2 + y^2}$$

% Racine n-ième
$$\sqrt[3]{8} = 2 \qquad \sqrt[n]{a^n} = a$$

% Formule quadratique complète
$$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$

% Fraction dans une racine
$$\sqrt{\frac{a}{b}} = \frac{\sqrt{a}}{\sqrt{b}}$$
```

**Rendu :**

$$\cfrac{1}{1 + \cfrac{1}{1 + \cfrac{1}{x}}}$$

$$\sqrt[n]{a^n} = a$$

$$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$

---

## 11. Dérivées & Différentielles

```latex
% Notation de Leibniz
$$\frac{dy}{dx} \qquad \frac{d^2y}{dx^2} \qquad \frac{\partial f}{\partial x}$$

% Notation de Lagrange (prime)
$$f'(x) \qquad f''(x) \qquad f^{(n)}(x)$$

% Gradient, divergence, rotationnel
$$\nabla f \qquad \nabla \cdot \vec{F} \qquad \nabla \times \vec{F}$$

% Laplacien
$$\Delta f = \nabla^2 f = \frac{\partial^2 f}{\partial x^2} + \frac{\partial^2 f}{\partial y^2}$$

% Règle de la chaîne
$$\frac{d}{dx}[f(g(x))] = f'(g(x)) \cdot g'(x)$$
```

**Rendu :**

$$\frac{dy}{dx} \qquad \frac{d^2y}{dx^2} \qquad \frac{\partial f}{\partial x}$$

$$\nabla f \qquad \nabla \cdot \vec{F} \qquad \nabla \times \vec{F}$$

$$\Delta f = \frac{\partial^2 f}{\partial x^2} + \frac{\partial^2 f}{\partial y^2}$$

---

## 12. Vecteurs & Géométrie

```latex
% Vecteur
$$\vec{u} = \begin{pmatrix} x \\ y \\ z \end{pmatrix}$$

% Norme
$$\|\vec{u}\| = \sqrt{x^2 + y^2 + z^2}$$

% Produit scalaire
$$\vec{u} \cdot \vec{v} = \|\vec{u}\| \|\vec{v}\| \cos\theta$$

% Produit vectoriel
$$\vec{u} \times \vec{v} = \begin{vmatrix} \vec{i} & \vec{j} & \vec{k} \\ u_1 & u_2 & u_3 \\ v_1 & v_2 & v_3 \end{vmatrix}$$
```

**Rendu :**

$$\vec{u} = \begin{pmatrix} x \\ y \\ z \end{pmatrix} \qquad \|\vec{u}\| = \sqrt{x^2 + y^2 + z^2}$$

$$\vec{u} \cdot \vec{v} = \|\vec{u}\| \|\vec{v}\| \cos\theta$$

---

## 13. Probabilités & Statistiques

```latex
% Probabilité conditionnelle
$$P(A|B) = \frac{P(A \cap B)}{P(B)}$$

% Formule de Bayes
$$P(A|B) = \frac{P(B|A)\, P(A)}{P(B)}$$

% Espérance et variance
$$\mathbb{E}[X] = \sum_{i} x_i p_i \qquad \text{Var}(X) = \mathbb{E}[X^2] - \mathbb{E}[X]^2$$

% Loi normale
$$f(x) = \frac{1}{\sigma\sqrt{2\pi}} e^{-\frac{(x-\mu)^2}{2\sigma^2}}$$

% Combinaisons
$$\binom{n}{k} = \frac{n!}{k!(n-k)!}$$
```

**Rendu :**

$$P(A|B) = \frac{P(B|A)\, P(A)}{P(B)}$$

$$\mathbb{E}[X] = \sum_{i} x_i p_i \qquad \text{Var}(X) = \mathbb{E}[X^2] - \mathbb{E}[X]^2$$

$$f(x) = \frac{1}{\sigma\sqrt{2\pi}} e^{-\frac{(x-\mu)^2}{2\sigma^2}}$$

$$\binom{n}{k} = \frac{n!}{k!(n-k)!}$$

---

## 14. Logique & Ensembles

```latex
% Ensembles classiques
$$\mathbb{N} \subset \mathbb{Z} \subset \mathbb{Q} \subset \mathbb{R} \subset \mathbb{C}$$

% Opérations ensemblistes
$$A \cup B \qquad A \cap B \qquad A \setminus B \qquad \bar{A} \qquad A \times B$$

% Appartenance et inclusion
$$x \in A \qquad A \subseteq B \qquad A \subsetneq B$$

% Quantificateurs
$$\forall x \in \mathbb{R},\; x^2 \geq 0$$
$$\exists x \in \mathbb{R},\; x^2 = 2$$

% Implication et équivalence
$$P \implies Q \qquad P \iff Q$$
```

**Rendu :**

$$\mathbb{N} \subset \mathbb{Z} \subset \mathbb{Q} \subset \mathbb{R} \subset \mathbb{C}$$

$$A \cup B \qquad A \cap B \qquad A \setminus B$$

$$\forall x \in \mathbb{R},\; x^2 \geq 0 \qquad \exists x \in \mathbb{R},\; x^2 = 2$$

$$P \implies Q \qquad P \iff Q$$

---

## 15. Algèbre & Suites

```latex
% Suite arithmétique
$$u_n = u_0 + nr \qquad S_n = \frac{n(u_0 + u_n)}{2}$$

% Suite géométrique
$$u_n = u_0 \cdot q^n \qquad S_n = u_0 \cdot \frac{1 - q^n}{1 - q}$$

% Développement limité (Taylor)
$$f(x) = \sum_{n=0}^{N} \frac{f^{(n)}(a)}{n!}(x-a)^n + o\left((x-a)^N\right)$$

% Binôme de Newton
$$(a+b)^n = \sum_{k=0}^{n} \binom{n}{k} a^{n-k} b^k$$
```

**Rendu :**

$$u_n = u_0 \cdot q^n \qquad S_n = u_0 \cdot \frac{1 - q^n}{1 - q}$$

$$(a+b)^n = \sum_{k=0}^{n} \binom{n}{k} a^{n-k} b^k$$

$$f(x) = \sum_{n=0}^{N} \frac{f^{(n)}(a)}{n!}(x-a)^n + o\left((x-a)^N\right)$$

---

## 💡 Aide-mémoire syntaxe rapide

| Ce que tu veux | Code LaTeX |
|---|---|
| Fraction | `\frac{a}{b}` |
| Racine | `\sqrt{x}` ou `\sqrt[n]{x}` |
| Exposant | `x^{n}` |
| Indice | `x_{n}` |
| Intégrale | `\int_a^b f(x)\,dx` |
| Somme | `\sum_{k=0}^{n}` |
| Produit | `\prod_{k=1}^{n}` |
| Limite | `\lim_{x \to 0}` |
| Infini | `\infty` |
| Flèche | `\to` ou `\rightarrow` |
| Grec | `\alpha \beta \gamma \delta \pi \sigma \omega` |
| Vecteur | `\vec{u}` |
| Norme | `\|x\|` |
| Appartient | `\in` |
| Pour tout | `\forall` |
| Il existe | `\exists` |
| Implique | `\implies` |
| Équivalent | `\iff` |
| Ensemble N,Z,R... | `\mathbb{N}` |
| Texte dans formule | `\text{si } x > 0` |
| Grand espace | `\quad` ou `\qquad` |
| Petit espace | `\,` |
