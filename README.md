# Prediction-UPDRS-Parkinson-scores
Prediction of UPDRS scores in Parkinson’s patients from voice recordings.

To reproduce the results obtained and commented on in the report, just follow these simple instructions:

1. Open the R document and change if necessary the path to the working directory of your R studio. Run the entire R document for pre-processing, regression techniques, and glm. 

2.Subsequently (without doing the pre-processing and saving the new data file we cannot execute the .ipynb) we execute the entire pyhton notebook from anaconda. (check you're working directory too).


Note1: The result should be the same given the use of a seed.

Note2: Some of the final functions of the .ipynb that we only use to create the informative tables for the report, will not generate them the same because we were continually modifying them. But they are just for visualization, the functions to obtain the data will work just as well.


Note3: If de dataset is removed or it doesn't work you can get it again following these steps:

1. Go to the repository whose link is on the second page of the report, in the dataset description section. We also add it here: http://archive.ics.uci.edu/ml/datasets/Parkinsons+Telemonitoring.

2. Click on "data folder" that appears at the top left underlined in yellow, once inside click on parkinsons_updrs.data so that the file is downloaded.

3. Put it all in the same folder along with the codes provided here. Open the R document and change if necessary the path to the working directory of your R studio.
