This project is to demontrate an example of end-to-end Neural Network model development process using Pytorch. It starts with EDA, then develops the model, and use the pre-trained model to make inference. 
Opportunities: 
	1. Further input data analysis should reveal more ideas for feature engineering and selection.
 	2. Cross validation may be useful to reduce overfitting problem.
	3. Train the model on GPU will increase the speed.
  

Project Structure:

The code base include 6 Jupyter Notebook scripts as follows.
	EAD Step:
	- 01-EDA-data overview.ipynb -> raw data is imported and examined at high level.
	- 02-EDA-data cleansing.ipynb -> closely investigated the outlier and missing values, and fixed the issues whenever needed. This step also provides insight for modeling phase. details see the in-script markdowns. 
	- 03-EDA-bivariate analysis -> check the correlation between pairs of variables, provide initial idea of variable selection
	- 04-feature engineer -> created new features
	- 05-model dev -> construct the Neural Network model and train the model using Pytorch
	- 06-Inference -> Use the pre-trained model to inference the test dataset. 

The scripts should be executed sequentially using Jupyter Notebook or Lab.

Dependencies see the requirement.txt file.
	
