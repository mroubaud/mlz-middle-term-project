# mlz-middle-term-project
In this repo you can find all the files related to the mlz middle term project of Matías Roubaud

You can find the streamlit app I created for this project in [this link](https://mlz-middle-term-project-app-app-cxbuwbwd4mumbg2rb54o2d.streamlit.app/). In the same link you will find the description of the problem, exploratory dana analysis and an interactive interface to play with it. The repository for the streamlit app can be found [here](https://github.com/mroubaud/mlz-middle-term-project-streamlit-app).

In this repository you will find the following files:

* ***salaries.csv***: Data set used for train and test the develop machine learning model.
* ***middle_term_project.ipynb***: ipynb notebook with exploratory data analysis, models tryed and all the process to reach the best final model.
* ***dv.bin***: dict vectorized used to transform categorical values.
* ***final_model.bin***: final model.
* ***Pipfile and Pipfile.lock***: files used to install all the dependencies and generate the virtual environment. Both files are used in the Dockerfile.
* ***Dockerfile***: Docker file for create the image and run the model in your local host.
* ***traint.py***: python script that can be used to train the model and generate dv.bin and final_model.bin.
* ***predict.py***: python script that loads the final model and dict vectorized and listen and reply the post requests.
* ***request.py***: python script that can be used to generate requests. 



