# STAT545 HW08

This repo is for STAT545 homework 08 created by Minzhi Liao, contains a shiny app created based on BC liquor data.

Deployed version is here on the shinyapp.com: https://liaomz.shinyapps.io/BCLiquor/

## Introduction

We are supposed to modify the original app by adding a few features to it. Here is the list for changes I made in the requests:

- Add an option to sort the results table by price.
- Add an image of the BC Liquor Store to the UI.
- Use the DT package to turn the current results table into an interactive table.
- Place the plot and the table in separate tabs.
- If you know CSS, add CSS to make your app look nicer.
- Show the number of results found whenever the filters change. For example, when searching for Italian wines $20-$40, the app would show the text “We found 122 options for you”.
- Allow the user to download the results table as a ..csv file.
- Allow the user to search for multiple alcohol types simultaneously, instead of being able to choose only wines/beers/etc.
- Provide a way for the user to show results from all countries (instead of forcing a filter by only one specific country).

I also try to add something fancy like controlling the parameters in the plot, or making the side panel float. Anyway, please try it! It is fun!

## Resources
The data is from [OpenDataBC](https://www.opendatabc.ca/dataset/bc-liquor-store-product-price-list-current-prices).

The tutorial for creating a shiny app is here: [Dean Attali's tutorial](https://deanattali.com/blog/building-shiny-apps-tutorial).


