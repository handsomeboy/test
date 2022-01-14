# 多目标优化的发展历史

This is some sample text.

(section-label)=
## Here's my first section

Here is a [reference to the intro](intro.md). Here is a reference to [](section-label).


$$
a^2+b^2=c^2  
$$(my_other_label)

> what is wrong {eq}`my_other_label`

## 这是一个中文标题

我们希望完成的是一个凸优化问题

生活中,许多问题都是由相互冲突和影响的多个目标组成。人们会经常遇到使多个目标在给定区域同时尽可能最佳的优化问题 ,也就是多目标优化问题。优化问题存在的优化目标超过一个并需要同时处理 ,就成为多目标优化问题。

多目标优化问题在工程应用等现实生活中非常普遍并且处于非常重要的地位 ,这些实际问题通常非常复杂、困难 ,是主要研究领域之一。自 20世纪 60年代早期以来 ,多目标优化问题吸引了越来越多不同背景研究人员的注意力。因此 ,解决多目标优化问题具有非常重要的科研价值和实际意义。

实际中优化问题大多数是多目标优化问题 ,一般情况下 ,多目标优化问题的各个子目标之间是矛盾的 ,一个子目标的改善有可能会引起另一个或者另几个子目标的性能降低 , 也就是要同时使多个子目标一起达到最优值是不可能的 , 而只能在它们中间进行协调和折中处理 , 使各个子目标都尽可能地达到最优化。其与单目标优化问题的本质区别在于 ,它的解并非唯一 ,而是存在一组由众多 Pareto最优解组成的最优解集合 ,集合中的各个元素称为 Pareto最优解或非劣最优解。

### 多目标优化问题 

不失去一般性，一个典型的多目`标优化问题`Multiobjective Optimization Problem

:::{note}
多目标优化算法$\frac{1}{\sin{\theta}} = a^2+b^2 =c^2$,我们随接触带的 
:::


After `import numpy as np` we have access to these attributes via the
syntax `np.attribute`.

Here\'s two more examples

We could also use the following syntax:

```{code-cell} python3
import numpy

numpy.sqrt(4)
```
我们平常所接触到的多目标优化问题具有很多不同的场景，其中关键的一点是。`lieu`安徽省那么上述**喊饿** 很少会在额

| Tables        | Are           | Cool  |
| :------------ |:-------------:| -----:|
| col 1 is      | left-aligned  |     A |
| col 3 is      | right-aligned |     B |
| col 2 is      | centered      |     C |


Here are some of the features of Jupyter Book:


:::{panels}
:container: +full-width text-center
:column: col-lg-6 px-2 py-2
:card:

**[Publication-quality content](file-types:markdown)** ✍
^^^
Write in either Jupyter Markdown, MyST Markdown for more [publishing features](content/myst), [reStructuredText](file-types:rst), [Jupyter Notebooks](file-types:notebooks), or [any Jupytext format](file-types:custom).
Includes support for rich syntax such as [citations and cross-references](content/citations), [math and equations](content/math), and [figures](content/figures).

---
**[Execute, cache, and insert computational content](content/execute)** 🚀
^^^
Execute notebook cells, then [format and insert the latest outputs](content:code-outputs) into your book.
[Cache outputs to save time in re-building later](execute/cache).
Even [save notebook outputs and insert them into other pages](content:code-outputs:glue).

---
**[Add interactivity to content and outputs](interactive/launchbuttons)** ✨
^^^
Create interactive content blocks such as [](content:tabs), [](content:dropdowns). [Toggle cell visibility](interactive/hiding) and include [interactive cell outputs](interactive/interactive) with Jupyter notebooks. [Launch interactive sessions](interactive/launchbuttons) with Binder or Colab, [make your code executable with Thebe](launch:thebe), or [connect with commenting services like Hypothes.is](interactive:comments).

---
**[Build books and articles in many formats](start/build)** 🎁
^^^
Build [multi-page books](structure:book) or [single articles](structure:article), and generate many kinds of outputs from them, such as [HTML websites](start/build) or [PDF outputs](advanced/pdf). Jupyter Book uses [the Sphinx Documentation engine](https://www.sphinx-doc.org) which supports [a variety of output types](https://www.sphinx-doc.org/en/master/usage/builders/index.html).

:::

This documentation is organized into a few major sections.

```{prf:algorithm} Ford–Fulkerson
:label: my-algorithm

**Inputs** Given a Network $G=(V,E)$ with flow capacity $c$, a source node $s$, and a sink node $t$

**Output** Compute a flow $f$ from $s$ to $t$ of maximum value

1. $f(u, v) \leftarrow 0$ for all edges $(u,v)$
2. While there is a path $p$ from $s$ to $t$ in $G_{f}$ such that $c_{f}(u,v)>0$
	for all edges $(u,v) \in p$:

	1. Find $c_{f}(p)= \min \{c_{f}(u,v):(u,v)\in p\}$
	2. For each edge $(u,v) \in p$

		1. $f(u,v) \leftarrow f(u,v) + c_{f}(p)$ *(Send flow along the path)*
		2. $f(u,v) \leftarrow f(u,v) - c_{f}(p)$ *(The flow might be "returned" later)*
```


````{tabbed} A histogram
```{glue:figure} boot_fig
:figwidth: 300px
:name: "fig-boot-tab"

This is a **caption**, with an embedded `{glue:text}` element: {glue:text}`boot_mean:.2f`!
```
````

````{tabbed} A table
```{glue:figure} df_tbl
:figwidth: 300px
:name: "tbl:df-tab"

A caption for a pandas table.
```
````

````{tabbed} Code to generate this
`{ code block here }`
````