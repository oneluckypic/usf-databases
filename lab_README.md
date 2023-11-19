## Elephant SQL Account
You'll need to create a free tier Elephant SQL account. [https://www.elephantsql.com/plans.html](https://www.elephantsql.com/plans.html). Get the Tiny Turtle tier.

## Install Mamba

Mambaforge is a common python tool and instructions online are plentiful

## Create conda environment
```
mamba env create -f environment.yml
```
## Activate new conda environment
```
conda activate usf-database
```
## Start Jupyter Lab
```
jupyter lab
```
Your web browser should open a new tab. If not, open a web browser and navigate to localhost:8888
## Lab Workflow (Open the Jupyter Notebooks (.ipynb files) from top to bottom, update your database information and run the notebook cells.
![](data/lab_workflow.png)