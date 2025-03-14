# Graph Neural Networks (GNNs)

## 📌 Introduction
A **Graph Neural Network (GNN)** is a type of neural network designed to process **graph-structured data**. Unlike traditional neural networks that work on grids (e.g., images) or sequences (e.g., text), GNNs operate on **nodes, edges, and their relationships**. GNNs are especially useful for handling **non-Euclidean data**, such as:

- **Social Networks** (e.g., friend connections, influencer detection)
- **Biological Networks** (e.g., molecular interactions, protein folding)
- **Traffic Networks** (e.g., roadmaps, sensor networks)

---
## 📊 Graph Data Structure
A graph consists of:
- **Nodes (Vertices)** → Represent entities.
- **Edges** → Define relationships between nodes.
- **Features** → Store relevant data associated with nodes or edges.

Graphs are represented using an **Adjacency Matrix**, a square matrix of size **V × V** (where V is the number of nodes), indicating connections between nodes.

### 🏛️ Types of Graphs
#### 🔄 **Based on Direction:**
- **Directed Graph** → Edges have a direction (A → B).
- **Undirected Graph** → Edges have no direction (A — B).

#### ⚖ **Based on Weights:**
- **Weighted Graph** → Edges have associated weights (e.g., cost, distance, or probability).
- **Unweighted Graph** → All edges are equal (no weights assigned).

---
## 🎯 Tasks Done with GNNs
GNNs are used for different tasks at various levels:

### 1️⃣ **Node-Level Tasks**
- **Node Classification** → Predict the label/class of a node (e.g., identifying fraud accounts in a network).

### 2️⃣ **Edge-Level Tasks**
- **Edge Prediction** → Predict the existence or strength of a connection (e.g., friend recommendation in social networks).

### 3️⃣ **Graph-Level Tasks**
- **Graph Classification** → Classify an entire graph (e.g., predicting whether a molecular structure is toxic or not).

---
## 🛠️ How GNNs Work
A GNN follows these steps:

- 1️⃣ **Initialization** → Convert all feature vectors into node embeddings.
- 2️⃣ **Message Passing** → Nodes exchange information with neighboring nodes to update their representation.
- 3️⃣ **Message Aggregation** → Combine messages from neighbors using aggregation functions (sum, mean, max, etc.).
- 4️⃣ **Node Updation** → Update the node representation based on aggregated messages.

🔹 These steps repeat over multiple layers to learn deeper node representations.

## 📚 Further Learning Resources
- [PyTorch Geometric Documentation](https://pytorch-geometric.readthedocs.io/)
- [Stanford CS224W: Machine Learning with Graphs](http://web.stanford.edu/class/cs224w/)

Happy Coding! 🚀

