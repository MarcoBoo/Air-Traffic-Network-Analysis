# Air Traffic Network Analysis  
 
This study applies **Network Analysis** to evaluate the global air traffic network's efficiency, resilience, and role in trade, tourism, and international relations. Key goals include identifying strategic hubs, detecting connectivity clusters, and analyzing correlations between flight patterns and political structures.   

## Validity & Reliability  
The analysis leverages a **globally representative routes dataset** comprising **59,036 routes**, **3,209 airports**, and **531 airlines**, ensuring proportional coverage across geographic regions. While the dataset is smaller than real-world air traffic volumes due to computational constraints, its global scope and inclusion of major airports and routes enhance its validity as a model of aviation networks. Reliability is strengthened by a **transparent methodology**: raw route data is directly mapped to nodes (airports) and directed edges (flight frequency), minimizing preprocessing and enabling reproducibility.  

## Measures & Results  
The study focused on **regional subnetworks** (Africa, USA, Europe) and a global network to assess connectivity patterns across diverse political and geographic contexts. Subnetworks were constructed using only internal nodes and edges (e.g., intra-European flights for Europe’s subnetwork). Analyses included **directed edges weighted by flight frequency** to identify strategic hubs, clusters of high connectivity, and correlations between flight density and political alliances or economic partnerships, as suggested by aviation diplomacy frameworks.  

The Jupyter Notebook generate large outputs (e.g., visualizations, dataset previews, or verbose logs),thus the `.ipynb` file size can easily exceed GitHub's 100 MB limit. To resolve this, we distributed informations as follow:

- **Jupyter Notebook (`.ipynb`)**  
  Contains **only**:
  - Code cells (Python)
  - Markdown documentation
  
- **HTML Export (`.html`)**  
  Stores **outputs** like:
  - Maps
  - Images/plots (Matplotlib, Seaborn)
  - Execution logs