# Facebook Network Analysis

This project analyzes the Facebook Pages Food network, exploring relationships, influence and flow of information/content among food-related pages through network visualizations, centrality measures and information spread models.

## Dataset
- **Source**: [Network Repository - Facebook Pages Food Graph](https://networkrepository.com/fb-pages-food.php)
- 620 Nodes, 2102 Edges
- The dataset consists of nodes representing food pages and edges representing mutual likes between these pages.

## Information Spread Models
- **Independent Cascade Model**: Models information spread where each active node has a single chance to activate each of its neighbors.
- **Linear Threshold Model**: Models spread based on nodes being influenced by a threshold level of neighboring active nodes.

## Results
- **Visualizations**: A Fruchterman-Reingold layout is used for network visualization.
- **Centrality Analysis**: Key nodes in the network were identified based on various centrality measures, providing insights into the most influential pages within the Facebook food pages network.
- **Information Spread Analysis**: Results from the Independent Cascade model and Linear Threshold model indicate the potential reach of information originating from key nodes.
