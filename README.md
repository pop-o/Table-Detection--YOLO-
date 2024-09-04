This is a simple table detection trained on a custom dataset that separates two tables into two classes: borderless_table and border_table.

It is done using YOLOv8n model.

Recommended Python version >=3.9

YOLO version: YOLOv8n
To run the project follow the following steps:

->create a virtual environment using the commmand:
  python -m venv myev
  (you can replace the myev with your preferred environment name)
  
->activate your environemtn using the command:
  myev\Scripts\activate
  
->install jupyter notebook for running the tableDetection(two classes).ipynb file: 
  pip install jupyter

->install the requirements mentioned in the requirements.txt file. use the command:
  pip install -r requirements.txt

->open jupyter notebook using the command:
  jupyter notebook

->open the tableDetection(two classes).ipynb file and run all cells
  

To train using your own data follow these steps:
->create a dataset folder in the folder you have created the virtual environment.

->create two folders named "train" and "val"

->inside each folder train and val create two folders named "images" and "labels". The labels folder contains the annoated yolo files for each image in the images folder. (labeling was done by using labelimg)

->in the dataset folder create a data.yaml file with the following format

![{0427B847-8CB4-43CD-AE4C-AD3CE211446F}](https://github.com/user-attachments/assets/4c8df2e0-c1ac-405b-b21c-1a86b2210ad4)

->replace the paths with your file paths to your train and val folders.

->now you can run the tabledetection(two classes).ipynb file and train your model and perform inferences.

->This part of the code in the tabledetection(two classes).ipynb file is used to crop the detected tables from a specified folder of 20 images and move them into another folder named cropped_images2

![{5B53858B-12B5-4187-8273-1D36460217E2}](https://github.com/user-attachments/assets/60744f06-f4c2-40dd-b315-4b46fb98c46f)


