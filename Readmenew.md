# Book Recommendation System
This repository contains the code for building book recommendation system.
## Details about Dataset
All the information related to dataset is described in this section.
 ### Dataset
 * We have used Books dataset in order to build Book recommendation system.
* You need to download dataset from this [link](http://www2.informatik.uni-freiburg.de/~cziegler/BX/).
* Put dataset inside `input_data`  folder.
### Types of dataset
1. **The full dataset**: This dataset consists of 26,000,000 ratings and 750,000 tag applications applied to 45,000 books by 270,000 users.

2. **The small dataset**: This dataset comprises of 100,000 ratings and 1,300 tag applications applied to 9,000 movies by 700 users.
3. We will build a simple Recommendation for movies using **The full dataset**.
### Data description
* It contains 100004 ratings and 1296 tag applications across 9125 books. These data were created by 671 users between January 09, 1995 and October 16, 2016. This dataset was generated on October 17, 2016.

* Users were selected at random for inclusion. All selected users had rated at least 20 movies. No demographic information is included. Each user is represented by an id, and no other information is provided.

* The data are contained in the following files.
```
credits.csv
keywords.csv
links.csv
links_small.csv
movies_metadata.csv
ratings.csv
ratings_small.csv 
```
### Dependencies
* Python >=3.5
* pandas
* numpy
* scipy
* scikit-learn
* scikit-surprise
* lightfm
* matplotlib
* seaborn
* jupyter notebook
* jupyter lab
* textblob
### Install dependencies
#### Windows OS
##### Install Python3 (install python 3.6.4)
* Step 1: Download python form [this link](https://www.python.org/downloads/).

* Step 2: Refer [this link](http://www.openbookproject.net/courses/webappdev/units/softwaredesign/resources/install_python_win7.html) or [this link](https://www.youtube.com/watch?v=V_ACbv4329E) in order to install python.
##### Install Pycharm IDE
* Step 1: Download pycharm IDE community edition by using [this link](https://www.jetbrains.com/edu-products/download/#section=idea).

* Step 2: Install ```.exe``` file.



