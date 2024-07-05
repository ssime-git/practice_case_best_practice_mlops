# practice_case_best_practice_mlops

## Your tasks :

0. Create a virtual environment and activate it
1. Read, understand and may be execute the notebook in the `notebooks/` folder
2. create the python scripts to train a new model based on new data :
The script should takes as input to train and save a new model in `models/`:
* The training data (may be X_train that has been saved in `data/processed/` sub-folder
* The new data that was saved recently (in real case or here you can use the X_test from `data/processed/` so simulate this)
3. (for later) create an API to consume your model
4. (for later) create a container to hold your API with your model
5. (for later) create a github action to retrain your model and save it on github (if very light model) and push a new container o fyour API on your dockerhub account (CHALLENGING)
