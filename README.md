# Predict-Browser-family-from-agent-string
This repo contains the report and Python code to predict browser family from its agents string.

##Author:
---------
Yue Wen
##Prerequisites:
--------------
1.Python 2/3 with the following libararies installed:

pandas
numpyp
random
operator
re
sklearn


##Running the tests:
------------------

1.Open the python termial with necessary libraries installed

2.Make the folder of the datasets as the working directory

3.Copy the python file into the same folder of the datasets

4.input the following code:

"""
python run.py train.txt test.txt prediction_results_path_of_output_data.txt

"""


Here, 
"train.txt" is file name of the training dataset, 
"test.txt" is the file name of the testing data set, 
"prediction_results_path_of_output_data.txt" is the file name of the output txt file containing the prediction results.

You can change the name as you wish, as long as they are consistent with the file name in the datasets folder!

5. Be patient and wait for the result :) It might take ~3 minutes to output the result.
