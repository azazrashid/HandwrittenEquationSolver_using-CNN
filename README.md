# HandwrittenEquationSolver_using-CNN

This is a Handwritten Equation solver using CNN code written in Python.

Download the dataset from this link https://www.kaggle.com/xainano/handwrittenmathsymbols

Equation can contain any digit from 0-9 and symbol +,x,- 
This works on images with white background and digits/symbols in black.

The three ipynb files contain the code for extraction, training and testing. 
1. Run Data_extraction.ipynb first after downloading training imagess and extract it in the folder containing Data_extaction.ipynb file. Save the train_data.csv file after running this code and then load it in train.ipynb.  
2. Run train.ipynb, after succesfully running Data_extraction.ipynb .
3. Run CNN test.ipynb, you either need to download model_final.h5 and model_final.json file or you can run it after succesfully running train.ipynb file. You also need to replace the path of the image in code from the local path of image to be tested on your computer.
