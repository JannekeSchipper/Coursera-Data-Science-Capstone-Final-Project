# Coursera Data Science Capstone

### Describing the Project
The goal of this exercise is to create a product to highlight the prediction algorithm that you have built and to provide an interface that can be accessed by others. For this project you must submit:

A Shiny app that takes as input a phrase (multiple words) in a text box input and outputs a prediction of the next word.
A slide deck consisting of no more than 5 slides created with R Studio Presenter (https://support.rstudio.com/hc/en-us/articles/200486468-Authoring-R-Presentations) pitching your algorithm and app as if you were presenting to your boss or an investor.


The data corpus for this project can be downloaded from Captsone Data (https://d396qusza40orc.cloudfront.net/dsscapstone/dataset/Coursera-SwiftKey.zip)

The data was cleaned using the tm, quanteda packages. These packages has various inbult functions for removing common puntuation, stopswords, numbers, twitter handles etc.The clean data was then combined together for furthur analysis.A sample of 10 percent of the data was used for the project. The N- Grams were created using  tokenization. The model algorithm uses the stupid back-off strategy for words prediction.

The final project was concluded with one Shiny application and a Pitch using R-Presentation.

Links to the app and presentation.

* The Milestone Project from Week two can be foun in this link:  [Milestone Project](http://rpubs.com/joseantonio/236625)

* The Word Prediction App can be found on shinyapps.io:
[Shine App](https://joseantonio.shinyapps.io/capstone-shiny-app/)

* This pitch deck with a short presentation for the capstone application is located here: 
[Data Science Capstone](http://rpubs.com/joseantonio/capstone-data-science)
