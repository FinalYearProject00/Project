Movie Recommendation Engine
This repository contains the code for building movie recommendation engine.

Details about Dataset
All the information related to dataset is described in this section.

Dataset
We have used MovieLens dataset in order to build movie recommendation engine.
You need to download dataset from this link
Put dataset inside input_data folder.
Types of dataset
The full dataset: This dataset consists of 26,000,000 ratings and 750,000 tag applications applied to 45,000 movies by 270,000 users. Includes tag genome data with 12 million relevance scores across 1,100 tags.
The small dataset: This dataset comprises of 100,000 ratings and 1,300 tag applications applied to 9,000 movies by 700 users.
We will build a simple Recommendation for movies using The full dataset.
Data description
It contains 100004 ratings and 1296 tag applications across 9125 movies. These data were created by 671 users between January 09, 1995 and October 16, 2016. This dataset was generated on October 17, 2016.

Users were selected at random for inclusion. All selected users had rated at least 20 movies. No demographic information is included. Each user is represented by an id, and no other information is provided.

The data are contained in the following files.

credits.csv
keywords.csv
links.csv
links_small.csv
movies_metadata.csv
ratings.csv
ratings_small.csv
More details about the contents and use of all these files is given in README.txt

Download dataset
In-case, there is need to download dataset then use either of the given links.

If you wnat to download MovieLens dataset hosted on Kaggle then use this link
If you want to download MovieLens dataset from its official website then use this link
List of other dataset
MovieLens - Movie Recommendation Data Sets link
Netflix Prize Dataset link
Yahoo! - Movie, Music, and Images Ratings Data Sets link
Cornell University - Movie-review data for use in sentiment-analysis experiments link
MovieTweetings - link
Dependencies
Python >=3.5
pandas
numpy
scipy
scikit-learn
scikit-surprise
lightfm
matplotlib
seaborn
jupyter notebook
jupyter lab
textblob
Install dependencies
Linux OS (Ubuntu 16.04 LTS / Ubuntu 17.10)
Commands for installing pip package manager for python3
Step 1: $ sudo apt-get -y install python3-pip
Step 2: $ sudo pip3 install --upgrade pip
Step 3: $ pip3 --version

Commands for installing pip package manager for python2
Step 1: $ sudo apt-get -y install python-pip
Step 2: $ sudo pip2 install --upgrade pip 
               OR 
        $ sudo pip install --upgrade pip

Step 3: $ pip2 --version
              OR
        $ pip --version

Commands for installing all dependencies are given below.
nltk:             $ sudo pip install nltk
numpy:            $ sudo pip install numpy
scipy:            $ sudo pip install scipy
scikit-learn:     $ sudo pip install -U scikit-learn
scikit-surprise:  $ sudo pip install scikit-surprise
Pandas:           $ sudo pip install pandas
matplotlib: 
                  $ sudo apt-get install libfreetype6-dev libpng-dev
                  $ sudo pip install matplotlib 
seaborn:          $ sudo pip install seaborn
jupyter notebook: $ sudo apt-get -y install ipython ipython-notebook
                  $ sudo -H pip install jupyter
jupyter lab       $ sudo pip install jupyterlab
textblob          $ sudo pip install textblob
Commands for installing pycharm
Step 1: Downlaod pycharm IDE community edition form [this link]()

Step 2: Untar the tar.gz file in /opt path
        $ tar xvzf ~/Downloads/pycharm-community*.tar.gz -C /opt

Step 3: Change ownership if only need
        $ sudo chown -R Username:username  /opt/pycharm-community-*.*
        For example : $ sudo chown -R jalaj:jalaj  /opt/pycharm-community-*.*

Step 4: Jump to the following path
        $ cd /opt/pycharm-community-2016.3.2/bin`

Step 5: Now you can see the pycharm.sh
        $ sh ./pycharm.sh or sudo sh ./pycharm.sh

Step 6: If you want to make desktop entry for pycahrm so the pycharm can be lunched 
        from luncher then follow the steps given below

        Start PyCharm.
        
        From the Tools menu, select "Create Desktop Entry..."
        
        Tick the corresponding box if you want the launcher for all users.
        
        If you selected "Create entry for all users", you will be asked for your password.
        
        A green message bubble should appear informing you that it was successful.
        
        You should then be able to find PyCharm in the Unity Dash or pin it to the launcher.

Windows OS
Install Python3 (install python 3.6.4)
Step 1: Download python form this link

Step 2: Refer this link or this link in oreder to install python

Install anaconda
Step 1: Download Anaconda 5.1 (python 3.6 version) using this link

Step 2: See the installation instruction given on this link

Note: If you have any other version of python then install anaconda which supports that particular version of python

Install dependencies using conda
nltk:             In-built installed with anaconda
numpy:            In-built installed with anaconda
scipy:            In-built installed with anaconda
scikit-learn:     In-built installed with anaconda
scikit-surprise:  $ conda install -c conda-forge scikit-surprise
Pandas:           In-built installed with anaconda
matplotlib:       In-built installed with anaconda 
seaborn:          In-built installed with anaconda
jupyter notebook: In-built installed with anaconda
                  In-built installed with anaconda
jupyter lab:      In-built installed with anaconda
textblob:         $ conda install -c conda-forge textblob 
Issues with installing surprise package
If you are facing issue for installing surprise then try the following links which can help you.
If conda is not working then try to install surprise using pip
See this installation instructions
See these links if you have any issues.
link 1
link 2
link 3
link 4
Install Pycharm IDE
Step 1: Download pycharm IDE community edition by using this link

Step 2: Install .exe file.

Code credit
Code credits for this code go to Rounak Banik I've merely created a wrapper and necessary changes to get people started.
