# Big-Data-Project-AirBnB_Clustering

## Introduction and Problem Statement:
Airbnb, an online marketplace established in 2008, revolutionized lodging by allowing hosts to rent out unused space or entire homes. This platform offered a cost-effective and unique alternative to traditional hotels and B&Bs. One challenge guests face is determining the quality of a listing without any firsthand experience. This issue has given rise to a phenomenon known as social proof, where potential guests rely heavily on reviews from others to assess the desirability of a listing. New listings, however, suffer from a lack of reviews, creating a "cold start" problem where both Airbnb and prospective guests struggle to evaluate the quality of these properties.

Therefore, this project aims to explore the potential of Airbnb listings with zero reviews, which might be overlooked due to the absence of feedback, yet could be promising options for travelers. Our goal is to assess these properties' value and enhance their visibility to potential guests by categorizing each zero-review listing as ‘Poor’, ‘Average’, or ‘Great’. Through this classification, Airbnb can better recommend specific listings to different users, addressing the initial challenge of the cold start problem for new listings on the platform.

## File Folder Structure:
Most of our files are broken up based on the milestone goals accomplished that particular week:
- data_for_modeling : Folder contains our final dataset that we used in pySpark to create our transformations and use in our models.
- milestone1 : Contains notebooks on doing EDA for each of our regions: East, Central, and West along with an example joining calendar and listings-detailed tables.
- milestone2 : Contains notebooks on resolving misisng values, doing initial feature engineering, conducting EDA on the aggregate 15 cities, and applying the table joins.
- milestone3 : Contains notebooks on creating an intiial modeling pipeline via pySpark, creating our finalized feature engineering dataset, and conducting an initial attempt on decision tree & random forest models.
- milestone4 : Contains notebooks on all of our baseline & fine-tuned models for various number of features. The models we conducted in this project are decision tree, logisitic regression, and random forest. Our final predicted zero-review results from the random forest model are in this folder as a zipped up parquet file.

## Data Preprocessing

## Exploratory Data Analysis
To conduct our Exploratory Data Analysis (EDA), we first divided our data into three distinct regions to conduct regional-specific EDA before doing EDA on all 15 cities at once. We decided to take this approach to get a granular understanding of whether there were specific regional differences in our datasets before aggregating all 15 of our cities together. 
For regional EDA, we have created three Python notebooks, each housed within the 'milestone1' folder. These notebooks facilitate a comprehensive examination of our entire dataset on a regional level, including identifying missing values, analyzing data types, assessing the general range of each column, and compiling essential statistics such as mean, median, and standard deviation.
Plots that we created within our region-specific notebooks can be grouped into the following broad categories:
- Price
- Reviews
- Geojson file to render each city’s geographic area
- General property listing information like availability, amenities, host sign-ups, and room type.

For the aggregate 15 cities, EDA can be found in our ‘milestone2’ folder on our Github repository. Plots that we created within our aggregate 15 cities EDA can be grouped into the following broad categories:
- Amenities
- Reviews
- Individual property features such as bedrooms and num_bath features
- Host related information


## Feature Engineering

## Modeling

## Conclusion

























## Contact:
If you have any questions or issues, please feel free to reach out to Ji Noh, Minwoo Sohn, and Tiffany Lee:
- **Ji Noh**
  - Email: eun.ji.noh@Vanderbilt.Edu
  - GitHub: jinoh0731
- **Minwoo Sohn**
  - Email: minwoo.sohn@Vanderbilt.Edu
  - GitHub: minu803
- **Tiffany Lee**
  - Email: Tiffany.Lee@vanderbilt.edu
  - GitHub: Math1019
