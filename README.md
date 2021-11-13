# COS711_A3
Add the 'Train.csv','Test.csv', unzipped Test_Images and unzipped Train_Images to the folder where the notebooks are located.
Four notebooks are added, one each to train the RPN, DCN and BGCN respectively, and one where the three networks are combined to make predictions.
Train the RPN, Classifier and Background classifier, by uncommenting the cells named Training, and then running all cells. This will save the weights to a checkpoints folder.
Only then can the 'RPN, CN and BGCN Combined.ipynb' file be run, as this file loads the weights from the checkpoints folder.
