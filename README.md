# Facebook Ego Network Analysis for Political Outreach Optimization

![Network Visualization](day3_activation.png)

## 📌 Overview
This project analyzes Facebook ego networks to optimize political outreach by identifying high-influence users and communities. Using network science techniques, we:
- Detect algorithmic communities (Louvain method).
- Compare them to user-defined social circles.
- Simulate influence spread via threshold models.
- Prioritize nodes for cost-efficient advertising.

**Dataset**: [Stanford SNAP Ego-Facebook](https://snap.stanford.edu/data/ego-Facebook.html)

## 🔑 Key Features
- **Network Analysis**: Degree distribution, clustering coefficient, path length.
- **Community Detection**: Louvain algorithm vs. user-defined circles (Adjusted Rand Index).
- **Centrality Metrics**: Degree, betweenness, eigenvector centrality.
- **Influence Simulation**: Threshold model for targeted vs. random seeding.
- **Visualizations**: Network structure, community alignment, activation spread.

## 🛠️ Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/facebook-ego-network-analysis.git
    ```
2. Install dependencies:
    ```bash
    pip install networkx pandas matplotlib python-louvain scikit-learn tqdm
    ```
3. Download the dataset from [Stanford SNAP](https://snap.stanford.edu/data/ego-Facebook.html) and place it in /data/.

## 🚀 Usage

## 📊 Results
- Community Alignment: ARI = 0.144 (low overlap between algorithmic and user-defined groups).
- Top Central Nodes: Degree centrality outperformed other metrics.
- Influence Spread: Targeted seeding activated 92% of nodes vs. 7.8% for random.

## 📚 References
- Dataset: [Stanford SNAP](https://snap.stanford.edu/data/ego-Facebook.html)
- Libraries: NetworkX, pandas, matplotlib, python-louvain.