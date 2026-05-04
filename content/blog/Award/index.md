---
title: 👩🏼‍🏫 Awards and Certificates
summary: This page highlights selected awards and recognitions !
date: 2025-10-22
math: true
authors:
  - me
tags:
  - Deep Reinforcement Learning
  - Actor-Critic
  - Continuous Control
  - Sequential Decision making
  - Stochastic Environment
image:
  caption: 'Embed rich media such as videos and LaTeX math'
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

## 🏆 Award: 2025 Best European Master’s Thesis in Mathematical Finance. 
Recipient of the 2025 Natixis Award for Best Master’s Thesis in Mathematical Finance, awarded by the [Natixis Foundation for Research and Innovation](https://natixis.groupebpce.com/articles/prize-for-best-masters-thesis-in-quantitative-finance/). | [PDF of my Master’s thesis](/uploads/MasterThesis_EmmanuelGnabeyeu.pdf) |

## Related Work

Below is the research paper associated with this award:

{{< cite page="/publications/conference-paper" >}}

## Video

Here I share the Full ceremony replay: | [Images of the ceremony](/uploads/10303CRMBestThesis.pdf) |

**Dailymotion**:
<iframe frameborder="0" width="670" height="400" src="https://geo.dailymotion.com/player/xh36y.html?video=k3bKFXMZ7XNtD6E3r5U" allowfullscreen></iframe>

**Video file**

Videos Videos of some annimation:
<!--
may be added to a page by either placing them in your `assets/media/` media library  
-->
| Training Skew | Volatility Fitting |
|---|---|
| <div style="width:100%; max-width:720px; height:520px; margin:auto; overflow:hidden; display:flex; align-items:center; justify-content:center;">{{< video src="TrainingSkew_RL_animation.mp4" controls="yes" >}}</div> | <div style="width:90%; max-width:520px; height:520px; margin:auto; overflow:hidden; display:flex; align-items:center; justify-content:center;">{{< video src="vol_fitting_animation_equity.mp4" controls="yes" >}}</div> |
    
## Podcast
    {{</* audio src="ambient-piano.mp3" */>}}

Try it out:

{{< audio src="ambient-piano.mp3" >}}

## Math block:

$$
\textcolor{red}{\text{Action network:}} \quad \text{DPG} = \textcolor{blue}{\text{Deep Policy Gradient}}
$$

$$
a_t \sim \textcolor{red}{\pi^{D}(s_t,\theta^{\pi})} + \epsilon_t,
\quad \text{with} \quad
\textcolor{brown}{\epsilon_t \sim \mathcal{N}(0, \sigma_n^2 I_K)},
\quad \text{and} \quad
\sigma_n = \max\!\left(\sigma_0\left(1-\frac{n}{N}\right)^4,\sigma_{\min}\right)
$$

$$
\textcolor{red}{\text{Critic network:}} \quad \textcolor{blue}{\text{Q-Learning and Bellman equation}}
$$

$$
\begin{cases}
R_{t}=\sum_{i=t}^{T}\gamma^{(i-t)} r(s_{i},a_{i}) \\[6pt]
Q^{\pi}(s_{t},a_{t})=\mathbb{E}[R_{t}\mid s_{t},a_{t}]
\end{cases}
\quad \Rightarrow \quad
\textcolor{red}{
L(\theta^{Q})=
\mathbb{E}\left[
\left(
Q^{\pi}(s_{t},a_{t}; \theta^{Q})-
\left(r(s_{t},a_{t})+\gamma Q^{\pi}(s_{t+1},a_{t+1};\theta^{Q})\right)
\right)^{2}
\right]
}
$$

**Latex code**
```latex
\begin{itemize}
	\item \textcolor{red}{Action network:} DPG=  \textcolor{blue}{Deep Policy gradient} % $ J = \mathbb{E}[R_{s_{t}}] ==== $ (\textbf{Proof:} Cf. Report)
\end{itemize}
$$ 
a_t \sim  \textcolor{red}{\pi^{D} (s_t,\theta^{\pi})} + \epsilon_t \quad \text{with} \quad \textcolor{brown}{\epsilon_t \sim \mathcal{N}(0, \sigma_n^2 I_K)} \quad \text{and} \quad \sigma_n = \text{max}(\sigma_0(1-\frac{n}{N} )^{4},\sigma_{\text{min}})
$$
\begin{itemize}
	\item \textcolor{red}{Critic network:} \textcolor{blue}{Q-Learning and Bellman equation.} % $ Q_{\theta^{Q}}(s_{t_{i}},a_{t_{i}}) =  - \sum_{k=t_i}^{T} \mathbb{E}_{(s_{k},a_{k})\sim \rho_\pi} [ \gamma^{(k-t_i)} \xi (\vec{\theta}_{t_{k}} )] $             
\end{itemize}
$$ 
\begin{cases} R_{t}=\sum_{i=t}^{T}\gamma^{(i- t)}r(s_{i},a_{i})\\Q^{\pi}(s_{t},a_{t})=\mathbb{E}[R_{t}|s_{t},a_{t}]&
\end{cases} \quad \Rightarrow \textcolor{red}{L(\theta^{Q})=\mathbb{E}[(Q^{\pi}(s_{t},a_{t}; \theta^{Q})-[r(s_{t},a_{t})+\gamma Q^{\pi}(s_{t+1},a_{t+1};\theta^{Q})])^{2}]}
$$
```


