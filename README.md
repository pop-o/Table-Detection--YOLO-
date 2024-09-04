This is a simple table detection trained on a custom dataset that separates two tables into two classes: border_table and borderless_table
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
  
