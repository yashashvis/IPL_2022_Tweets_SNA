IPL 2022 Twitter Network Analysis

This project analyzes social media interactions during the Indian Premier League (IPL) 2022 season to uncover fan behaviour, rivalry dynamics, and structural polarization in online communities. Using a dataset of IPL-related tweets, the project applies network analysis and community detection techniques to map how fans engage across teams and over time.

🚀 Project Overview

Collected and filtered IPL 2022 tweet data (March 26 – May 29, 2022).
Identified user fan affiliations using team-specific hashtags and keywords.
Constructed a weighted interaction network of mentions and retweets.
Applied Louvain community detection to measure modularity and network polarization.
Analyzed temporal slices around the MI vs CSK match to study rivalry intensity.
Computed betweenness centrality to identify key "gatekeeper" users who bridge rival groups.

🔍 Key Objectives
Understand how fan communities form and behave online.
Detect patterns of polarization between rival teams.
Study how interactions change before, during, and after a match.
Highlight influential users in the conversation network.

🧠 Methods & Techniques

Python
Pandas – Data cleaning & transformation
NetworkX – Graph creation & centrality analysis
Louvain Algorithm – Community detection
Matplotlib – Visualizations
Regular Expressions – Extracting mentions from tweets

📊 Results & Insights

Clear structural polarization between fan communities.
MI vs CSK rivalry showed noticeable spikes in interaction intensity.
Gatekeeper users played a crucial role in cross-community communication.
Visual network graphs revealed community clusters and cross-links.

📁 Project Structure
├── data/
│   └── IPL_2022_tweets.csv
├── src/
│   └── analysis.ipynb
├── outputs/
│   ├── network_plots/
│   └── rivalry_charts/
└── README.md

✅ How to Run

Clone the repository:

git clone <your-repo-url>
Install required dependencies:
pip install python-louvain networkx pandas matplotlib
Run the notebook or script in your environment.

📌 Future Enhancements
Add sentiment analysis for deeper context.
Expand to multiple seasons.
Build a dashboard for interactive exploration.
