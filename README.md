# Welcome to the LeuRah's MLBD2023 Repository Page!

![LeuRah](images/leurah.jpeg)

## About
This repository is for the MLBD2023 course at EPFL. It contains the project that we have done during the course through the Spring 2023 semester.

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
The notebooks are defined as follows:
* `skill_kmeans.ipynb`: contains the work done on the skill clustering using kmeans ith Jacard similarity.
* `skill_clustering.ipynb`: contains the work done on the skill clustering with interpretation and further skills analysis and categorization.
* `final-calcularis-LeuRah.ipynb`: contains the final version of the project. It includes all our work and the final results.


The models folder include several sub-folders that contain the models that we have trained. 
- `all_data`: contains the models in free training mode contains several pickle files that contain useful dataframes.
- `plots`: contains some of but not all the plots that we have generated.
- `split_data`: pickled BKT models that have been used to train and test our models .

## How to run
To run the notebooks, you need to install the requirements in the `requirements.txt` file. You can do so by running the following command in the terminal:
```
pip install -r requirements.txt
```

&#9888; **Some of the pickle files are too large so we provide a zipped version of them. You will have to unzip in the same folder to be able to use them.**

1. To generate the skill clusters first run the `skill_kmeans.ipynb` notebook. It will generate the necessary pickle files that will be used in the `skill_clustering.ipynb` notebook.
2. Preprocess the categorical clusters by running the `skill_clustering.ipynb` notebook. It will generate the final pickle files wth regards to skills categories that will be used in the `final-calcularis-LeuRah.ipynb` notebook.
3. Run the `final-calcularis-LeuRah.ipynb` notebook to preprocess calcularis data, train the models, generate the final results and plots. The notebook is divided into several sections that are clearly defined. You can run the notebook from the beginning to the end or run each section separately.


Finally, we hope that you will enjoy our work and that it will be useful for the calcularis team. If you have any questions, please do not hesitate to contact us.