IPS_ME_1&2_GNG_SPS_1.html file can be opened in any preferred web browser and represents a network created using the latest release of the fruit fly brain connectome. 
For this purpose, I used the file provided at https://codex.flywire.ai/api/download, which has been filtered to include only the Filtered synaptic connectivity table 
(5+ synapse threshold). From this file, I further filtered the data to retain only the upstream and downstream synapses of three neurons of interest, which have been previously 
characterized and are part of the fly’s visual system. These neurons are identified as IPS.ME.1, IPS.ME.2, and GNG.SPS.1. Using the resulting edge list, available in this repository 
under the name Synapses_IPS_ME_1&2_GNG_SPS_1.tsv, I generated the visualization using the R programming language, employing the igraph and visNetwork packages.
