---
title: Platform
nav:
  order: 2
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}platform

GraPharm harnesses vast biological datasets encompassing human genes, chemical compounds, biological processes, drug side effects, diseases, and symptoms to construct a sophisticated knowledge graph. 
This innovative platform excels in uncovering previously undiscovered connections, facilitating advancements such as drug repurposing, biomarker discovery, and identification of new therapeutic targets.
By integrating diverse sources of information, GraPharm empowers researchers and healthcare professionals to navigate complex biological relationships and unlock transformative insights in drug development and personalized medicine.


{% include tags.html tags="github, web server, demo" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filters="group: featured" %}

{% include section.html %}

## Look what we discovered
<div>
    <h2>This is HTML content</h2>
    <p>This is a paragraph of HTML content.</p>
</div>
{% include sub_graph.html %}

<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/vis/4.16.1/vis-network.min.js"> </script> <style type="text/css"> #mynetwork { width: 100%; height: 750px; background-color: #ffffff; position: relative; float: left; } </style>
<script type="text/javascript"> // initialize global variables. var edges; var nodes; var network; var container; var options, data; // This method is responsible for drawing the graph, returns the drawn network function drawGraph() { var container = document.getElementById('mynetwork'); // parsing and collecting nodes and edges from the python nodes = new vis.DataSet([{"id": "Hoa Nguyen", "image": "https://raw.githubusercontent.com/hnguyentt/cv_graph/master/images/Gau.jpg", "label": "Hoa Nguyen", "shape": "circularImage", "size": 50}, {"id": "Education", "image": "https://raw.githubusercontent.com/hnguyentt/cv_graph/master/images/education.png", "label": "Education", "shape": "circularImage"}, {"id": "Luong The Vinh high school for the gifted", "image": "https://raw.githubusercontent.com/hnguyentt/cv_graph/master/images/LTV.jpg", "label": "Luong The Vinh high school for the gifted", "shape": "circularImage"}, {"id": "University of Medicine and Pharmacy, Ho Chi Minh city", "image": "https://raw.githubusercontent.com/hnguyentt/cv_graph/master/images/UMPHCM.png", "label": "University of Medicine and Pharmacy, Ho Chi Minh city", "shape": "circularImage"}, {"id": "VietAI", "image": "https://raw.githubusercontent.com/hnguyentt/cv_graph/master/images/VietAI.png", "label": "VietAI", "shape": "circularImage"}, {"id": "Research Experience", "image": "https://raw.githubusercontent.com/hnguyentt/cv_graph/master/images/research.png", "label": "Research Experience", "shape": "circularImage"}, {"id": "Online Research Club", "image": "https://raw.githubusercontent.com/hnguyentt/cv_graph/master/images/ORC.png", "label": "Online Research Club", "shape": "circularImage"}, {"id": "Working Experience", "image": "https://raw.githubusercontent.com/hnguyentt/cv_graph/master/images/working.png", "label": "Working Experience", "shape": "circularImage"}, {"id": "Cao Thang Eye Hospital", "image": "https://raw.githubusercontent.com/hnguyentt/cv_graph/master/images/CTEH.png", "label": "Cao Thang Eye Hospital", "shape": "circularImage"}, {"id": "Hobbies", "image": "https://raw.githubusercontent.com/hnguyentt/cv_graph/master/images/hobby.jpg", "label": "Hobbies", "shape": "circularImage"}, {"id": "Playing musical instruments", "image": "https://raw.githubusercontent.com/hnguyentt/cv_graph/master/images/piano.jpg", "label": "Playing musical instruments", "shape": "circularImage"}, {"id": "Cycling", "image": "https://raw.githubusercontent.com/hnguyentt/cv_graph/master/images/cycling.jpg", "label": "Cycling", "shape": "circularImage"}, {"id": "Drawing", "image": "https://raw.githubusercontent.com/hnguyentt/cv_graph/master/images/drawing.png", "label": "Drawing", "shape": "circularImage"}, {"id": "Reading", "image": "https://raw.githubusercontent.com/hnguyentt/cv_graph/master/images/reading.png", "label": "Reading", "shape": "circularImage"}, {"id": "Pasteur Institute", "image": "https://raw.githubusercontent.com/hnguyentt/cv_graph/master/images/pasteur.jpg", "label": "Pasteur Institute", "shape": "circularImage"}]); edges = new vis.DataSet([{"color": "#0B806C", "from": "Hoa Nguyen", "to": "Education"}, {"color": "#0B806C", "from": "Education", "to": "Luong The Vinh high school for the gifted"}, {"color": "#0B806C", "from": "Education", "to": "University of Medicine and Pharmacy, Ho Chi Minh city"}, {"color": "#0B806C", "from": "Education", "to": "VietAI"}, {"color": "#0B3080", "from": "Hoa Nguyen", "to": "Research Experience"}, {"color": "#0B3080", "from": "Research Experience", "to": "University of Medicine and Pharmacy, Ho Chi Minh city"}, {"color": "#0B3080", "from": "Research Experience", "to": "Online Research Club"}, {"color": "#805B0B", "from": "Hoa Nguyen", "to": "Working Experience"}, {"color": "#805B0B", "from": "Working Experience", "to": "VietAI"}, {"color": "#805B0B", "from": "Working Experience", "to": "Cao Thang Eye Hospital"}, {"color": "#800B64", "from": "Hoa Nguyen", "to": "Hobbies"}, {"color": "#800B64", "from": "Hobbies", "to": "Playing musical instruments"}, {"color": "#800B64", "from": "Hobbies", "to": "Cycling"}, {"color": "#800B64", "from": "Hobbies", "to": "Drawing"}, {"color": "#800B64", "from": "Hobbies", "to": "Reading"}, {"color": "#0B3080", "from": "Research Experience", "to": "Pasteur Institute"}, {"color": "#805B0B", "from": "Working Experience", "to": "Pasteur Institute"}]); // adding nodes and edges to the graph data = {nodes: nodes, edges: edges}; var options = {"nodes": {"color": {"background": "rgba(255,253,248,1)"}}, "edges": {"color": {"inherit": true}, "smooth": true}, "physics": {"minVelocity": 0.75}}; network = new vis.Network(container, data, options); return network; } drawGraph(); </script>

{% include section.html %}