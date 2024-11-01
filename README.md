# Plant_Disease_Classification_with_multiple_Model_For_Sustainable_Developement

## Workflows

1. update Module View and all ipynb file
2. update setup.py
3. update package version
4. update the entity like kaggle.json
5. update the docker file
6. update the components
7. update the flows
8. update the main.py

# How to run?
### STEPS:
## First of all in app/trained_model/.txt file download the model from google drive and used in this project

```bash
conda create -n plant python=3.8 -y 
```

```bash
conda activate plant
```


```bash
pip install -r requirements.txt
```
# This Step run inside the app folderin this repository
```bash
streamlit run main.py
```

```bash
Now open up your local host 0.0.0.0:8080
```
# Model Description and Their Accuracy:
<img width="238" alt="Screenshot 2024-11-01 173659" src="https://github.com/user-attachments/assets/e5b1ff38-4b0c-42c8-90a4-c96747af72d9">

this is all the accyracy of different model used in this code but the accuracy of **EfficientNETB0 model** is state of the art for leaf disease detection that why we used our UI integration and application is by using this model.

After that in this i am also integrating the Model that present in the Google Drive that provide you in the file name of the trained model because of the size of the model.

Dataset Available at: https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset

Downloading Model available at: https://drive.google.com/file/d/1rKh-IElSdHTqax7XdfSdZTn-r8T_qWPf/view?usp=drive_link 
