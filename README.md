# CS190N Term Project

### Group 8 Members
* Palvi Sabherwal (@psabherwal)
* Emily Thai (@emilythai)
* Hannah Shakouri (@hannahshakouri01)

## PROBLEM 
Videos from streaming platforms are downloaded in chunks and fluctuations in network performance can result in rebuffering, essentially lowering the quality of user experience. To minimize the interruptions caused by loading delays, our project aims to predict the time needed to download the next video chunk. By accurately predicting these download times, streaming platforms such as YouTube and Tubi can adjust video quality or pre-buffer data to reduce loading interruptions, while improving user experience. 

## INSTRUCTIONS

### Installation:
1. Git clone our team's project repo. Run this command in your terminal: git clone https://github.com/psabherwal/cs190n-group8.git
2. Once you have cloned our team's project repo, cd into the project folder. Use the files located in our project folder to continue data collection (optional) and run our model.
3. These files are ready to modify or rerun for reproducing results.

### Reproducing Results:
Below are a few ways to reproduce different results with our team's project:

**Adjusting the Train-Test Split in projectModel.ipynb**
1. Open the projectModel.ipynb notebook.
2. Modify the test_size parameter to change the proportion of data used for testing.
3. Rerun the relevant cells to train the model with the new split.
4. Observe the difference and compare with other test_size values.

**Adding More Data Using dataCollection.ipynb**
1. Open the dataCollection.ipynb notebook.
2. Follow the steps provided in this notebook to collect additional data.
3. Ensure the new data matches the format of the original dataset.
4. Save the added dataset to the appropriate directory. Make sure to add to preexisting data collection.
5. Update the data loading step in projectModel.ipynb to use the updated dataset.
6. Rerun the data preprocessing and training cells for updated data collection.
8. Observe the difference and compare with other results.

**Using a Different Machine Learning Model**
1. In projectModel.ipynb, find the section where the model is initialized and trained.
2. Replace this with another scikit-learn model.
3. Adjust any model-specific hyperparameters or preprocessing steps as needed.
4. Rerun the training and evaluation cells to see the results with the new model.
5. Observe the difference and compare with other results.
