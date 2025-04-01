
---
  
## 📌 Part 1: Fundamental Markdown Functions

  
### 1. Headers

Use `#` for headings (up to 6 levels):

  

```markdown

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

```

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

---

  
### 2. Emphasis

  

```markdown

*italic* or _italic_

  

**bold** or __bold__

  

***bold and italic***

```

*italic* or _italic_

**bold** or __bold__

***bold and italic***

---

### 3. Lists

- **Unordered list** (use `-`, `*`, or `+`):

```markdown

- Item A

- Item B

  - Subitem B.1

```

  - Item A

- Item B

  - Subitem B.1
--- 
- **Ordered list**:

```markdown

1. First
   2. Second

```

1. First
    2. Second

---

### 4. Links and Images

  

```markdown

[Obsidian](https://obsidian.md)

  

![Obsidian Icon](chapter01-贝叶斯/assets/obsidian_icon.jpeg)

```

  [Obsidian](https://obsidian.md)
![Alt text](chapter01-贝叶斯/assets/obsidian_icon.jpeg)
---

  

### 5. Code

  

Inline code: `` `code` ``

  

Block code:

<pre>

```python

def hello():

    print("Hello, Obsidian!")

```

</pre>

  ```python

def hello():

    print("Hello, Obsidian!")

```

---

  

### 6. Blockquotes

  

```markdown

> This is a quote.

>> Nested quote.

```

  > This is a quote.

>> Nested quote.

---
### 7. Tables

```markdown
| Name   | Age |
|--------|-----|
| Alice  | 24  |
| Bob    | 30  |

```

| Name   | Age |
| ------ | --- |
| Alice  | 24  |
| Bob    | 30  |

---

### 8. Task Lists

  

```markdown

- [x] Done

- [ ] To do

```

- [x] Done

- [ ] To do

---
## ⚙️ Part 2: Advanced Features (Obsidian + CSS)

### 1. Internal Links (Wikilinks)

```markdown

[[Page Name]]

[[Page Name#Heading]]

```

[[c01-ref]]

[[c01-ref#🧐 **什么是贝叶斯推断**]]

---

  

### 2. Embeds

  

- Embed note: `![[Note Name]]`

- Embed section: `![[Note Name#Heading]]`

- Embed image: `![[image.png]]`

  

---

### 3. Callouts 

```markdown

> [!tip] Pro Tip
> Use custom callouts for extra clarity!

```

> [!tip] Pro Tip
> Use custom callouts for extra clarity!

> [!warning]
> Be careful!

---
### 4. MathJax (LaTeX)

Inline:
```markdown

$ \sum_{n=1}^{\infty} \frac{1}{n^2} = \frac{\pi^2}{6}$

```

$\displaystyle \sum_{n=1}^{\infty} \frac{1}{n^2} = \frac{\pi^2}{6}$

Block:

```latex

$$
\frac{1}{n} \sum_{i=1}^n x_i
$$

```

$$
\frac{1}{n} \sum_{i=1}^n x_i
$$


$$H D^{2}(P_{1},P_{2})=1-\sqrt{\frac{2\sigma_{1}\sigma_{2}}{\sigma_{1}^{2}+\sigma_{2}^{2}}}\exp\left[-\frac{1}{4}\frac{(\mu_{1}-\mu_{2})^{2}}{\sigma_{1}^{2}+\sigma_{2}^{2}}\right],$$
###  LaTeX Syntax Cheatsheet

| Concept       | Syntax Example                                              | Rendered Output                            |
| ------------- | ----------------------------------------------------------- | ------------------------------------------ |
| Superscript   | `$x^2$`                                                     | $x^2$                                      |
| Subscript     | `$x_1$`                                                     | $x_1$                                      |
| Fractions     | `$\frac{a}{b}$`                                             | $\frac{a}{b}$                              |
| Square root   | `$\sqrt{a^2 + b^2}$`                                        | $\sqrt{a^2 + b^2}$                         |
| Greek letters | `$\alpha, \beta, \gamma, \pi$`                              | $\alpha, \beta, \gamma, \pi$               |
| Summation     | `$\sum_{i=1}^n x_i$`                                        | $\sum_{i=1}^n x_i$                         |
| Integral      | `$\int_0^1 x^2 dx$`                                         | $\int_0^1 x^2 dx$                          |
| Matrix        | <code>$$\begin{bmatrix}a & b\\\\c & d\end{bmatrix}$$</code> | $\begin{bmatrix}a & b\\c & d\end{bmatrix}$ |

