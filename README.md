# imdb-data-interactive
An interactive dashboard for viewing plots I made for the kaggle imdb dataset

### Brushing 

The dashboard contains four of the visualizations that I made using python and javascript. For javascript I used d3.js (version 3),
and for python I used pandas, numpy, and sci-kit-learn. Using the dropdown menu, select a type of brush to use, the simply click and drag on a visualization to select data.
A brief explanation of the brushes are as follows:

- Highlight: Highlight the selected points on each plot
- Ignore: Remove the selected points on each plot
- Filter: Display only the selected points on each plot
- Enlarge: Increase the size of the selected points on each plot

### Viewing the data

Due to google chrome's cross-origin policy, viewing the visualizations is slightly
harder than just downloading them and opening in chrome. However, if you have python installed,
it is still easy. Simply open up a terminal and type in the following:

If you are on windows,

```
python -m http.server 8000
```

on linux,

```
python -m SimpleHTTPServer 8000
```

Then, check your localhost:8000 and the visualizations should be there.
