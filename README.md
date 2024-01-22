# Mapper-pie-nodes
Implementation of KeplerMapper with pie chart nodes. We use KeplerMapper in Python to generate the graph structure then use d3 in Javascript to produce the graph visualization. This repository uses data on Passiflora leaves from the paper [Morphometric analysis of Passiflora leaves: the relationship between landmarks of the vasculature and elliptical Fourier descriptors of the blade](https://academic.oup.com/gigascience/article/6/1/giw008/2865207?login=true#supplementary-data)

Step 1: Download the jupyter notebook and the procrustes.py file and put them in the same folder.

Step 2: Inside of your directory, create a folder called "passiflora_pie_graph".

Step 3: Inside of this folder, create a folder called "kepler".

Step 4: Download the rest of the files (except for the readme) and put them in the "kepler" folder.

Step 5: Inside the "kepler" folder, make a folder called "node_avg_outline".

Step 6: Run the Jupyter notebook.

Step 7: Type 

    python3 -m http.server 
    
into a terminal window to start a local server.

Step 8: Go to the URL in the terminal output (something like http://0.0.0.0:8000/).

Step 9: Navigate to the folder containing the index.html file.

Step 10: Now that you have successfully ran the Passiflora example, try modifying it for your data!

Thank you to the following resources:

    - https://bl.ocks.org/puzzler10/4438752bb93f45dc5ad5214efaa12e4a
    
    - https://gist.github.com/kgeorgiou/68f864364f277720252d0329408433ae

    - https://bl.ocks.org/mbostock/3355967
    
    - https://codepen.io/renx777/pen/BmBvzL
    
    - https://bl.ocks.org/almsuarez/4333a12d2531d6c1f6f22b74f2c57102
    
    - https://stackoverflow.com/questions/20052964/d3-how-to-add-image-to-the-label-of-a-graph-node
