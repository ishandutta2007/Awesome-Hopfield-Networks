# 🧠 Awesome Hopfield Networks 🚀

<div align="center">
  <img src="https://capsule-render.vercel.app/render?type=waving&color=auto&height=300&section=header&text=Hopfield%20Networks&fontSize=90&animation=fadeIn&fontAlignY=38" alt="Banner" />
  
  <p align="center">
    <a href="https://github.com/ishandutta2007/Awesome-Hopfield-Networks/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Hopfield-Networks?style=for-the-badge&color=yellow" alt="stars" /></a>
    <a href="https://github.com/ishandutta2007/Awesome-Hopfield-Networks/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Hopfield-Networks?style=for-the-badge&color=blue" alt="forks" /></a>
    <a href="https://github.com/ishandutta2007/Awesome-Hopfield-Networks/issues"><img src="https://img.shields.io/github/issues/ishandutta2007/Awesome-Hopfield-Networks?style=for-the-badge&color=red" alt="issues" /></a>
    <a href="https://github.com/ishandutta2007/Awesome-Hopfield-Networks/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Hopfield-Networks?style=for-the-badge&color=green" alt="license" /></a>
    <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow&style=for-the-badge" /></a>
  </p>

  <p align="center">
    <b>A curated list of awesome Hopfield Networks resources, papers, and implementations.</b>
  </p>
</div>

---

## 📖 Introduction to Hopfield Networks

Hopfield Networks are single-layer, recurrent artificial neural networks that function as content-addressable (associative) memory. They act like "energy landscapes." When you feed the network a partial or noisy pattern, it iteratively updates its states to find the nearest stable memory. 🛡️

---

## 📂 Types of Hopfield Networks

### 1. [Discrete Hopfield Networks](./docs/DISCRETE.md) (1982) 🔢
The original model introduced by John Hopfield operates using discrete time steps. Each neuron holds a strict binary or bipolar value, representing "on" or "off."
* **First Used:** 1982 in *"Neural networks and physical systems with emergent collective computational abilities"*
* **Mechanism:** Neurons update asynchronously to minimize the network's "energy."
* **Learn More:** See the [Detailed Discrete Guide](./docs/DISCRETE.md)

### 2. [Continuous Hopfield Networks](./docs/CONTINUOUS.md) (1984) 🌊
A modification that allows neuron states to take on a continuous, floating-point value.
* **First Used:** 1984 in *"Neurons with graded response have collective computational properties..."*
* **Mechanism:** Neurons take values between `0` and `1`, transitioning smoothly via differential equations.
* **Learn More:** See the [Detailed Continuous Guide](./docs/CONTINUOUS.md)

### 3. [Modern Hopfield Networks](./docs/MODERN.md) (2016) 🚀
Introduced in recent deep learning research, these networks (Dense Associative Memories) break the linear limit of traditional binary networks.
* **First Used:** 2016 in *"Dense Associative Memory for Pattern Recognition"*
* **Transformer Relationship:** Equivalence to self-attention mechanisms.
* **Learn More:** See the [Detailed Modern Guide](./docs/MODERN.md)

---

## 🛠️ Practical Examples & Use Cases

| Use Case | Description | Year | Original Paper |
| :--- | :--- | :--- | :--- |
| **Pattern Restoration / Completion** | Removing noise or static from data. | 1982 | [Neural networks and physical systems...](https://www.pnas.org/doi/10.1073/pnas.79.8.2554) |
| **Combinatorial Optimization** | Solving constraint-satisfaction problems (TSP, N-Queens). | 1985 | [“Neural” computation of decisions...](https://link.springer.com/article/10.1007/BF00337288) |
| **Deep Learning & Attention** | Implementing specialized layers for long-term memory. | 2020 | [Hopfield Networks is All You Need](https://arxiv.org/abs/2008.02217) |

---

## 📚 Resources & Deep Dives
* **Paper:** [Hopfield Networks is All You Need](https://github.io)
* **Implementation:** [GitHub - ML-JKU Hopfield Layers](https://github.com)
* **Code Example:** [GitHub - N-Queens Problem via Hopfield Networks](https://github.com)

---

## 📈 Star History
<div align="center">
   <a href="https://www.star-history.com/#ishandutta2007/Awesome-Hopfield-Networks&Date">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=ishandutta2007/Awesome-Hopfield-Networks&type=Date&theme=dark" />
      <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=ishandutta2007/Awesome-Hopfield-Networks&type=Date" />
      <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=ishandutta2007/Awesome-Hopfield-Networks&type=Date" />
    </picture>
   </a>
</div>
