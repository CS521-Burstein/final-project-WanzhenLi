CS 521 Project
Topic: Predicting Housing Prices (Linear Regression)
Names: Wanzhen Li, Tomas Hornicek

In our project we will explore a housing dataset containning data about houses that were sold in the previous years. Based upon the dataset we will use linear/logistic regression to predict house prices for the coming years. The data set we choose to explore is very large, therefore the first step we will take would be to dumify the data, meaning that we will take out all the rows that contain null data. We realise that this will that the opportunity cost of this action is that our project analysis will lose some accuracy, however by doing this we will make our data easy to manipulate with.(Is there a better way to do it Prof Burstein?). After we have dummified the data we have to pick out the variables that affect the housing prices the most. In order to do that we will use the correlation coefficient measuring how closely each variable is correlated to the Sale Price. We then decided to analyze the data which have the coorelation coefficient higher than |+-0.3| and built a new data frame from them. Using the newly created data frame we will compare and contrast the variables to predict how different variables affect the Sale Price and how the Sale Price will look based off those variables.  We are sure that we will uncover very interesting discoveries and predictive analytics. We are really excited to move forward with this project！

- All our code for reading the dataset, dummifying the dataset and manipulating the dataset to visualize it, is written in 3rd deliverable.ipynb
- Housing_Price.csv us our data set that we will use
- data_description.txt is the description of the Housing_Price.csv  dataset



- Graph 1 -> g1 : Shows the relationship between the Garage Area and the Sale Price
- Graph 2 -> g2 : Shows how houses, with over 1400 sqft above ground area, have cost over the years (In order to see this graph, install plotly. In terminal -> "pip install plotly")
- Graph 3 -> g3 : Shows how houses, with under 1400 sqft above ground area, have cost over the years (In order to see this graph, install plotly. In terminal -> "pip install plotly")
- Graph 4 -> g4: Shows the relationship between the Sale Price and the Year the house was remodeled as a bar chart
- Graph 5 -> g5: Shows the relationship between the Sale Price and the Year the house was remodeled as a scatter plot (The bar chart was hard to read)
- Graph 6 -> g6: This graph compares the average of each Masonry veneer type (Stone, None, Brick Face, Cinder Block and Brick Common) with the Sale price.



