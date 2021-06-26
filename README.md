# Kickstarter Analysis

This project serves to analyze a database of 4,000 past Kickstarter projects to see any hidden trends and make some initial conclusions. For more details, see `KickstarterAnalysis.xlsx`.

## An Initial Look

1. *Given the provided data, what are some conclusions we can draw about Kickstarter campaigns?*

* Music projects are the most successful Kickstarter projects if you are trying to get a project funded
* Theater projects are popular from a creator standpoint to try and get funded. They also *do* get funded at a bit less than a 2:1 ratio (eg. 1.7:1)
* From *February to late May* appears to be the best time to get a project funded. The area under the curve appears to be the widest between successful and failed projects during that period
* September and December are the worst times to get a project funded

2. *What are some limitations of this dataset?*

* All the journalism projects were canceled. While this definitely seems worrisome, it would be helpful to see if there are any successful journalism projects if attempting to make conclusions about journalism projects
* Similarly other more niche subcategories don't have enough data to make real conclusions.
* The number of projects that Kickstarter has on it has numbered over 300,000 so this is a small subset of that to make conclusions (particularly for projects that don't have a lot of data). It maybe not be a uniform set which could lead to wrong conclusions.
* Internet culture changes over time with some types of technologies. For example, microlending was extremely popular for a while, but it talked about very little today. Depending on when the data set was taken could change both the projects being submitted and funded.

3. *What are some other possible tables and/or graphs that we could create?*

Further analyis could include:

* A column standardizing the currency in US Dollars by the day the project was started or completed.
* A table/chart including the success percentage by both category/subcategory
* A table/chart analyzing outdoor projects to see if they do better in the spring/summer. A hypothesis might be that outdoor projects are better funded during the spring/summer months.
* A similar table/chart analyzing indoor projects to see if they do better in winter/fall for testing whether indoor projects are better funded during months we are more indoors.
* An table/chart showing the length of the blurb vs category/subcategory. Certain projects like plays might do better with more details in the blurb.

## A Brief Statistical Look

1. Use your data to determine whether the mean or the median summarizes the data more meaningfully.

* It appears the median is a better representation of the data. The mean appears to be influenced by some very well backed projects.

2. Use your data to determine if there is more variability with successful or unsuccessful campaigns. Does this make sense? Why or why not?

* There is more variability with successful campaigns. This makes sense as successful campaigns can go vastly over their goals. Unsuccesful campaigns will be below their goals so there is a limited range for how badly they can fail.
