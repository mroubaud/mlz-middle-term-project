# mlz-middle-term-project
In this repo you can find all the files related to the mlz middle term project of Matías Roubaud

You can find am online app of this project in [this link] (https://mlz-middle-term-project-app-app-cxbuwbwd4mumbg2rb54o2d.streamlit.app/). In the same link you will find the description of the problem, exploratory dana analysis and a simple app to use the trainned model. Repo for the streamlit app can be found [here] (https://github.com/mroubaud/mlz-middle-term-project-streamlit-app).

In this repository you will find the following files:

* ***salaries.csv***: Data set used for train and test the develop machine learning model 
* ***middle_term_project.ipynb***: ipynb notebook with exploratory data analysis, models tryed and all the process to reach the best final model
* ***dv.bin***: dict vectorized used to transform categorical values
* ***final_model.bin***: final model 
* ***Pipfile and Pipfile.lock***: files used to install all the dependencies and generate the virtual envirement. Both files are used in the Dockerfile
* ***Dockerfile***: Docker file for create the image to run the model in local host 
* ***traint.py***: python script that can be used to train the model and get dv.bin and final_model.bin
* ***predict.py***: python script that loads the final model and dict vectorized and listen and reply post requests
* ***request.py***: ython script that can be used to generate requests 



