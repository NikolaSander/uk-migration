## Visualising interregional migration flows in the UK

July 2014

Migration flows between Nuts1 and Nuts3 regions in the UK as estimated by Nik Lomax in collaboration with ONS. 

Re-formatted version of csv. file with original flows is called uk_flows_formatted.csv. This file was then converted into .json format using the circular-migration-plot tool by Johannes Schmidt @jo. 
* flows need to be integers
* table headings should say regionflow and countryflow

This first draft shows flows with at least 3,500 migrants. The same threshold has been used for a plot of Australian flow data at http://nikolasander.com/Australia-migration/ 

#### hand hints: change between years using 1 - 10 on your keyboard. Use ctrl+r to reset the plot. 

### TO DO:
* the page itself (index.html) needs extensive editing once the plot has been finalised.
* adjust placement of regions within the circle
* adjust threshold above which individual flows are shown
* do not show regions with very small gross migration???
* adjust colours of regions
* etc

The plot is configured via /dist/circular-migration-plot.js and /lib/ 

### To edit the plot using Git: 
Install locally the circular-migration-plot tool available at https://github.com/jo/circular-migration-plot to convert csv to json. Install Git to clone the uk-migration repo onto your hard drive. Edit the plot or replace the input data locally. Then use Git to push the revised plot back to the uk-migration repo on Github. 

$ git clone https://github.com/nikolasander/uk-migration

navigate to the newly cloned repo

$ git add .

$ git commit -m "commit message"

$ git push -u origin gh-pages

*Important: push to gh-pages branch, not to master branch.*


