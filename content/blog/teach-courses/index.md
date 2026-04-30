---
title: 👩🏼‍🏫 Outreach in mathematics
summary: We present a new theory  of stationarity for a class of stochastic Volterra integral equations.
date: 2026-04-20
math: true
authors:
  - me
tags:
- Stochastic Volterra Processes 
- Stochastic Differential Equations 
- Fourier-Laplace Transforms
- Jordan-Cauchy Residue Theorem
- Regular Variation 
- Tauberian Theorems
- Limit theorems
- Confluence

image:
  caption: 'Stochastic Volterra Integral Equations: Asymptotic Stationarity'
cover:
  image: "https://images.unsplash.com/photo-1557682250-33bd709cbe85?q=80&w=2560"
  position:
    x: 50
    y: 40
  overlay:
    enabled: true
    type: "gradient"
    opacity: 0.4
    gradient: "bottom"
  fade:
    enabled: true
    height: "80px"
  icon:
    name: "✨"
---
<!--
[HugoBlox Kit](https://hugoblox.com) is designed to give technical content creators a seamless experience. You can focus on the content and the HugoBlox Kit which this template is built upon handles the rest.
-->
**Stochastic Volterra Integral Equations: Asymptotic Stationarity!**

## Citation

Here are some publications associated to the topic:

{{< cite page="/publications/preprint3" view="citation" >}}

{{< cite page="/publications/journal-article" >}}

## Video

Teach your course by sharing videos with your students. Choose from one of the following approaches:

**Youtube**:

    {{</* youtube D2vj0WcvH5c */>}}

{{< youtube D2vj0WcvH5c >}}

**Bilibili**:

    {{</* bilibili BV1WV4y1r7DF */>}}


**Video file**

Videos may be added to a page by either placing them in your `assets/media/` media library or in your [page's folder](https://gohugo.io/content-management/page-bundles/), and then embedding them with the _video_ shortcode:

    {{</* video src="my_video.mp4" controls="yes" */>}}

## Podcast
    {{</* audio src="ambient-piano.mp3" */>}}

Try it out:

{{< audio src="ambient-piano.mp3" >}}

## Test students

Provide a simple yet fun self-assessment by revealing the solutions to challenges with the `spoiler` shortcode:

```markdown
{{</* spoiler text="👉 Click to view the solution" */>}}
You found me!
{{</* /spoiler */>}}
```

renders as

{{< spoiler text="👉 Click to view the solution" >}} You found me 🎉 {{< /spoiler >}}

## Math block:
<!--
renders as

$$\begin{tikzpicture}[scale=1.1]\def\gammaVal{1.5}
				\def\R{2.5}
				\def\deltaVal{0.15}
				\def\c{0.5}
				\def\r{1/\R}
				\draw[->] (-3, 0) -- (3, 0) node[right] {$\Re(z)$};
				\draw[->] (0, -3) -- (0, 3) node[above] {$\Im(z)$};
				\draw[blue, thick, ->] (\gammaVal, -\R) -- (\gammaVal, \R);
				\node at (\gammaVal + 0.3, 0.2) {\small \textcolor{blue}{$\textit{Br}(\gamma, R)$}};
				\draw[red, thick, ->] (\gammaVal, \R) -- (0, \R) node[midway, above] {\small $C^+$};
				\draw[red, thick, <-] (\gammaVal, -\R) -- (0, -\R) node[midway, below] {\small $C^-$};
				\draw[green, thick, ->] (0, \R) arc[start angle=90, end angle=175, radius=\R];
				\draw[green, thick, <-] (0, -\R) arc[start angle=270, end angle=185, radius=\R];
				\node at (-2.4, 2.1) {\small $C_R^+$};
				\node at (-2.4, -2.1) {\small $C_R^-$};
				\draw[orange, thick, <-] (-\R, \deltaVal) -- (-\c, \deltaVal);
				\draw[orange, thick, ->] (-\R, -\deltaVal) -- (-\c, -\deltaVal);
				\node at (-1.8, -0.35) {\small \textit{H}$(\delta, \tfrac{1}{R})$};
				\draw[orange, thick] (-\c, \deltaVal) arc[start angle=160, end angle=-155, radius=\r];
			\end{tikzpicture}
			\captionof{figure}{Jordan contour \( \Gamma_{\gamma, \delta, R} \).}$$
-->
```latex
$$	\begin{align*}
		&\sum_{z \in \mathbb{C} \setminus \{-1\}: z^\alpha=-1} \text{Res}(J_{\alpha}(t, \cdot), z) 
		= \frac{1}{2\pi i} \oint_{\Gamma_{\gamma, \delta, R}} J_{\alpha}(t, z) \, dz 
		= \frac{1}{2\pi i}\int_{\textit{Br}(\gamma, R)} J_{\alpha}(t, z) \, dz + \frac{1}{2\pi i}\int_{C^+} J_{\alpha}(t, z) \, dz \\
		&\quad \hspace{1.5cm} + \frac{1}{2\pi i}\int_{C_R^+} J_{\alpha}(t, z) \, dz - \frac{1}{2\pi i}\int_{\textit{H}(\delta, \frac{1}{R})} J_{\alpha}(t, z) \, dz  + \frac{1}{2\pi i}\int_{C_R^-} J_{\alpha}(t, z) \, dz + \frac{1}{2\pi i}\int_{C^-} J_{\alpha}(t, z) \, dz.
	\end{align*}$$
```

renders as

$$\begin{align*}
		&\sum_{z \in \mathbb{C} \setminus \{-1\}: z^\alpha=-1} \text{Res}(J_{\alpha}(t, \cdot), z) 
		= \frac{1}{2\pi i} \oint_{\Gamma_{\gamma, \delta, R}} J_{\alpha}(t, z) \, dz 
		= \frac{1}{2\pi i}\int_{\textit{Br}(\gamma, R)} J_{\alpha}(t, z) \, dz + \frac{1}{2\pi i}\int_{C^+} J_{\alpha}(t, z) \, dz \\
		&\quad \hspace{1.5cm} + \frac{1}{2\pi i}\int_{C_R^+} J_{\alpha}(t, z) \, dz - \frac{1}{2\pi i}\int_{\textit{H}(\delta, \frac{1}{R})} J_{\alpha}(t, z) \, dz  + \frac{1}{2\pi i}\int_{C_R^-} J_{\alpha}(t, z) \, dz + \frac{1}{2\pi i}\int_{C^-} J_{\alpha}(t, z) \, dz.\end{align*}
$$

## Code

HugoBlox Kit utilises Hugo's Markdown extension for highlighting code syntax. The code theme can be selected in the `config/_default/params.yaml` file.


    ```python
    import pandas as pd
    data = pd.read_csv("data.csv")
    data.head()
    ```

renders as

```python
import pandas as pd
data = pd.read_csv("data.csv")
data.head()
```

## Inline Images

```go
{{</* icon name="python" */>}} Python
```

renders as

{{< icon name="python" >}} Python

