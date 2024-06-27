# random-forest-land-classification
This project analyzes images from the summers of 2016 and 2019 using satellite imagery from NASA's Landsat 8. It employs random forest algorithms to study the spectral profile of the land and classify it into categories such as water, urban, rural, and burned areas. The project aims to create a map of the classified areas to determine the extent of burned land and assess how the land is recovering over time.

## Steps:
1) Defining Area of Interest
Specify the geographic region for analysis.

2) Defining Time of Interest for Image Collection
Select the time periods (summers of 2016 and 2019) for the imagery.

3) Applying Masks
Correct for atmospheric and satellite noise to ensure image clarity and accuracy.

4) Collecting Sample Points
Gather 100 sample points and classify them into categories: water, urban, rural, and burned areas.

5) Training the Model
Use the classified sample points to train the random forest model.

6) Assessing Model Validity
Evaluate the accuracy of the model using testing sample data.
