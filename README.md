# Welcome to the LeuRah's MLBD2023 Repository Page!

![LeuRah](images/leurah.jpeg)

## About
This repository is for the MLBD2023 course at EPFL. It contains the project that we have done during the course through the Fall 2023 semester.

## Project
The work evloves about predicting user performance of the Calcularis dataset,
The purpose of this repo is to provide a comprehensive analysis of
the user data collected from the calcularis dataset. The dataset serves
as a valuable resource containing a wealth of information regarding
the performance of students who utilize the company’s mathematics
fun exercises. These exercises are designed to enhance students’ skills
in a wide range of mathematical topics, including counting, division,
multiplication, and more. By analyzing this dataset, we aim to gain
insights into the effectiveness of the calcularis program and explore
predictive models for user performance.

Please refer to the report for more details.


## Authors
- Youssef El Ouazzani (DS)
- Mohamed Yassine Aouam (DS)
- Mohamed Badr Taddist (CS)
  
## Structure
The project is divided into several notebooks and python scripts. The data used must be stored in the `data` folder. The notebooks are stored in the root folder along with the python scripts. 
The models folder include several sub-folders that contain the models that we have trained. 
- `all_data`: contains the models in free training mode contains several pickle files that contain useful dataframes.
- `plots`: contains some of but not all the plots that we have generated.
- `split_data`: dataframes that have been used to train and test some of the models .

## How to run
To run the notebooks, you need to install the requirements in the `requirements.txt` file. You can do so by running the following command in the terminal:
```
pip install -r requirements.txt
```
Some of the pickle files are too large so we provide a zipped version of them. You will have to unzip in the same folder to be able to use them.

