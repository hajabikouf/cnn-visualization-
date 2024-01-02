# cnn-visualization-
ARI5004  Deep Learning 2023/2024

to run the code the following should be done:
- upload notebook to kaggle
- add the dataset from the link to the kaggle work environment  
https://www.kaggle.com/datasets/biaiscience/dogs-vs-cats
- upload the model to kaggle, it can be found in google drive  at https://drive.google.com/file/d/1FohwVnUoDJSdZH583VO6IrWuTMUcFTfz/view?usp=sharing

- modify notebook code under  Part II activation maximization| 
change the line in the first cell to point to the uploaded model or train new model from scratch and point to it

original_model.load_state_dict(torch.load('/kaggle/input/final-model/class_model.pth',map_location=torch.device('cpu')))

- run the entire notebook or run cell by cell skipping the training part
