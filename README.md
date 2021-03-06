## Book Recommendation System
### *Massimo Malandra, November 2018*
<br>
This repository contains all the files related to the final project for the Master in Data Science, VI Edition, held by Kschool Madrid.

The objective of this project is the implementation of a **book recommender system**, using the data made available by Goodreads, a website where users can register and rate the books they have read, sharing their ratings and opinions with other readers. 
The approach chosen is to generate a system that recommends books using the information inherent in users' ratings. 
So, rather than predicting the ratings that each user would give to all the books included in this analysis that he hasn’t read yet (and hence trying to reduce the error in those predictions), I have chosen instead to generate a system that give relevant recommendations to each user based on a certain measure of similarity between the books he has already read and rated and the books he hasn't read but other users do.

In order to successfully run the code, please download all the .csv files included in this repository and place them in your own working directory and hence change the path at the beginning of each script (os.chdir("/Users/678094/Desktop/Goodreads")) so it will be pointing at your own working directory where the files have just been saved.
I have replicated this part at the beginning of each notebook because in order to build the recommender system it is not compulsory to run all three notebooks: notebooks 01. and 02. are facultative, they serve to scrape from the Goodreads website additional data used in the analysis. But the same data is saved as .csv file and loaded again in notebook .03. 
So the logical sequence of the code consists in running notebook 01, 02 and 03 respectively, but in case you want to skip the scraping part and go directly to the recommender system, you can run notebook 03. independently, changing the working directory accordingly as indicated above.
