---
output:
  pdf_document: default
  html_document: default
---
# Reflection for Example Coursework (Week 0)

## Daniel Gardner

For this project we were assigned into a group of 4 and tasked with finding a dataset, finding existing code, and getting this code to run on our data in order to begin visualizing it. We ended up choosing the Titanic Passengers dataset as it is known online as a good beginners dataset for this project, i.e. good data with few missing values and lots of pre-existing code available to try and use for ourselves.

Getting github working was a challenging learning curve, especially as I have never used it before, although after 2 weeks of using it it seems a lot easier to understand now. In retrospect it has proved a very useful tool in sharing code and all being able to see what the others are doing. As well as this the project dynamic ended up working well: it helped that me and Tom knew each other as well as Xinyu and Xinyue. We were able to have an in-person group meeting each week as well as the supervisor meeting which kept us on track. 

Finding the data was initially quite tricky as there was so much choice available and the project objectives were quite vague. Initially we decided to go for a health approach and find binary data on obesity, cancer risk etc. I found a dataset of obesity statistics for each US state across 4 years and thought this seemed good as it was very large with many different covariates to analyse. However upon further inspection this was actually just a very big survey simply cut into lots of subsections, with only really 50 observed data points (the 50 US states). We decided this wasn't what we wanted and after a meeting with our supervisor, instead used Kaggle to search for simpler datasets that already had visualization code available. The advantage of this as well was we could then sort the projects by R and Python so I could choose a project in R where I am most comfortable. Out of these the best we found was the Titanic dataset for reasons discussed above, so I found a competition project someone had already done on it concerning finding groups of passengers.

Getting the code working didn't turn up too many difficulties. The main trouble was just installing all packages required that whoever wrote the code had used, and loading the dataset onto my Rmd document. After that pretty much all the code was copied straight from their directory, so it worked just as it had in theirs. The main changes I had to make were when we tried to combine all our code; i.e. trying to change a lot of my variable names to match Xinyue's so our code all matched. Overall I think we managed to cover a lot of different visualizations and make them look good with the ggplot2 and ggplots packages.

In terms of what been could have done better, the main stumbling block for us was actually grasping what the project wanted to do. This took up the majority of our time and if we could've found a dataset quicker we could've spent more time understanding the associated code and potentially tried to use more complex code. As it stands the visualizations I have included are all quite trivial, although I think they still meet the learning objectives well.
