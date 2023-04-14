# foodiegang.io
UofO  Data Analytics Project 3
We are exploring how many Italian, Mexican, and Thai Restaruants there are in Portland, metro area, where are there located, and what is the distribution of the ratings
For this project used Yelp Reviews, using Yelp fusion API
We used Python to pull the API and we returned the data in JSON file (Yelp_data_pull.ipynb)
The restaurant JSON data is stored into SQLlite database (restaurant_data.json)
We used Flask server to host the pages (index.html), the SQLlite bd, and retuns the JSON file we needed for the visualizations (flask_server.ipynb)
We used d3 to read the JSON data file
Maps were done using leaflet.js (map.html)
Charts were done using ApexCharts and Plotly Js libraries. (chart.html)
