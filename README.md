# Wikipedia Network

This repository is intended to visualize the data present in the [.graphml file](https://github.com/AugustoOliveira099/Wikipedia_Network_View/cna.graphml), generated by running this [notebook](https://github.com/AugustoOliveira099/Data-Structure-II/Wikipedia_Network_Construction_and_Analisys).

Using the .graphml file, [Gephi](https://gephi.org/), an open-source software, was used to process the data and analyze the following parameters:

- Out-Degree;
- Modularity;
- Eccentricity;
- Closeness Centrality;
- Hub;
- Degree;
- Authority;
- Betweenness Centrality;
- PageRank;
- Harmonic Closeness Centrality;
- Strongly-Connected ID: 612.

Based on modularity, each node was classified into 6 communities.

The analysis results were added to the data from the .graphml file, and a [new file](https://github.com/AugustoOliveira099/Wikipedia_Network_View/final_graph.graphml) .graphml was generated.

Using the ["SigmaExporter"](https://github.com/oxfordinternetinstitute/gephi-plugins/tree/sigmaexporter-plugin) plugin to export the network as a collection of HTML5 files, it becomes interactive.

To deploy this network, two tools were used, considering the benefits of both visualizations:

1. The first tool was provided by GitHub itself. To access it, simply click [here](https://augustooliveira099.github.io/Wikipedia_Network_View/network).
2. The second tool for deployment was a [plugin](https://gephi.org/plugins/#/plugin/web-publish-plugin) provided by Gephi called [Retina](https://ouestware.gitlab.io/retina/beta). To access it, click [here](https://ouestware.gitlab.io/retina/beta/#/graph/?url=https%3A%2F%2Fgist.githubusercontent.com%2FAugustoOliveira099%2Fdd447dec82f77c20d5ad703a076fb031%2Fraw%2F91537e2cc64a0a6d429e00f3f010a56faa74b290%2Ffinal_graph.graphml&r=d&sa[]=s&sa[]=r&ca[]=i-s&ca[]=o-s&ca[]=d-s&ca[]=e-s&ca[]=c-s&ca[]=ha-s&ca[]=b-s&ca[]=p-s&ca[]=m-s&ca[]=a-s&ca[]=hu-s).
