# Mapper-pie-nodes
Implementation of Mapper with pie chart nodes. We use KeplerMapper in Python to generate the graph structure then use d3 in Javascript to produce the graph visualization. This repository uses data on Passiflora leaves from the paper [Morphometric analysis of Passiflora leaves: the relationship between landmarks of the vasculature and elliptical Fourier descriptors of the blade](https://academic.oup.com/gigascience/article/6/1/giw008/2865207?login=true#supplementary-data)

Step 0: Install KeplerMapper with

        pip install kmapper
        
Step 2: Download the two .py files and replace the ones installed on your system in step 1. In Linux, the filepath is something like

        Home/Anaconda3/envs/myenvironment/lib/python3.8/site-packages/kmapper
        
Step 3: Download the jupyter notebook and the procrustes.py file and put them in the same folder.

Step 4: Inside of your directory, create a folder called "passiflora_pie_graph".

Step 5: Download the rest of the files (except for the readme) and put them in the "passiflora_pie_graph" folder.

Step 6: Inside the "passiflora_pie_graph" folder, make a folder called "node_avg_outline".

Step 7: Run the Jupyter notebook.

Step 8: Type 

    python3 -m http.server 
    
into a terminal window to start a local server.

Step 9: Go to the URL in the temrinal output (something like http://0.0.0.0:8000/).

Step 10: Navigate to the folder containing the index.html file.
