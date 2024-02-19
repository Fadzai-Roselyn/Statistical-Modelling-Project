# Statistical-Modelling-with-Python

## Project/Goals
To make use of the API in Python knowledge acquired in class, in addition to SQLite3 and regression
to come up with a project that ties together the different concepts.

## Process

### Connecting to Citybikes API
This process allowed for more practice with understanding json output. From the different city options, I went with Vancouver and sought to understand some parameters that are important to bike companies, such as geoloction, ratings, distance and available bikes per station.

### Pulling information from Foursquare and Yelp
The data used in analysis was mainly from this step. Successful API calls allowed for data to be arranged in to Data Frames for further analysis. The output from Foursquare and Yelp could also be compared

### Data merging
The data frames from the first and second processes were joined. This allowed for the exploration of SQLite3. At this point, it was also possible to attempt data visualization.

### Regression model
This process allowed for the creation of a regression model, with the added challenge of stretching the mind to think of ways in which the model could be turned in to a classification model.

## Results
Each subsection had it's own results and they all culminated in the result represented by the regression model. The analysis suggested 'rating' significantly influenced the predicted values of 'Bikes Available' in the model,
whereas 'distance' did not show statistical significance in this particular context.
The overall model fit was somewhat relatively weak as signified by the R-squared; 0.004 and other diagnostic measures' values

## Challenges 
Bringing all the concepts harmoniously together was a bit of a challenge, an exciting one nonetheless as there were a lot of learning points.

## Future Goals
One thing that stood out to me as a factor that could influence the results of a bigger study is seasonality, which in this case covers time and weather. It would be interesting to see how the metrics are affected over time not only at a particular live time selection.
