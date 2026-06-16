# Awesome-Hopfield-Networks
## Hopfield Networks

Hopfield Networks are single-layer, recurrent artificial neural networks that function as content-addressable (associative) memory. They act like "energy landscapes." When you feed the network a partial or noisy pattern, it iteratively updates its states to find the nearest stable memory.

---

## Types of Hopfield Networks

### 1. Discrete Hopfield Networks
The original model introduced by John Hopfield operates using discrete time steps. Each neuron holds a strict binary or bipolar value, representing "on" or "off."
* **Binary Networks:** Neurons take values of either `0` or `1`. 
* **Bipolar Networks:** Neurons take values of `-1` or `+1`.
* **Mechanism:** Neurons update asynchronously—one at a time in a random order—to minimize the network's "energy" until it stabilizes on a memorized pattern. 
* **Limitations:** Low storage capacity (roughly 0.14N patterns for N neurons) and susceptible to "spurious states" (false memories).

### 2. Continuous Hopfield Networks
A modification that allows neuron states to take on a continuous, floating-point value.
* **Mechanism:** Neurons take values between `0` and `1`. The network transitions smoothly across states using differential equations, allowing for higher precision and more complex memory recall.

### 3. Modern Hopfield Networks (Dense Associative Memories)
Introduced in recent deep learning research, these networks break the linear limit of traditional binary networks by introducing stronger non-linearities.
* **Mechanism:** Allows the network to store an exponentially large number of patterns relative to the dimension of the data.
* **Transformer Relationship:** Research shows that the self-attention mechanisms used in Transformers are computationally equivalent to a single update step in a Modern Continuous Hopfield Network.

---

## Practical Examples & Use Cases

* **Pattern Restoration / Completion:** Removing noise or static from data. If you input a noisy, partially corrupted image of a face, the network updates pixel by pixel until it snaps into a clean, fully recognized face.
* **Combinatorial Optimization:** Solving constraint-satisfaction problems, like the Traveling Salesperson or the N-Queens problem. Neurons act as constraints, and the network settles into the optimal configuration by minimizing its energy function.
* **Deep Learning & Attention:** Implementing specialized Hopfield layers within modern architectures to act as long-term memory components, often used in tasks like immune repertoire classification.

---

## Resources & Deep Dives
* **Paper:** [Hopfield Networks is All You Need](https://github.io)
* **Implementation:** [GitHub - ML-JKU Hopfield Layers](https://github.com)
* **Code Example:** [GitHub - N-Queens Problem via Hopfield Networks](https://github.com)
