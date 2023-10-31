
### Data description
* It contains 100004 ratings and 1296 tag applications across 9125 movies. These data were created by 671 users between January 09, 1995 and October 16, 2016. This dataset was generated on October 17, 2016.

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
 


### List of other dataset

* MovieLens - Movie Recommendation Data Sets [link](https://grouplens.org/datasets/movielens/)


## Dependencies

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


## Install dependencies


#### Linux OS (Ubuntu 16.04 LTS / Ubuntu 17.10)


##### Commands for installing pip package manager for `python3`
```
Step 1: $ sudo apt-get -y install python3-pip
Step 2: $ sudo pip3 install --upgrade pip
Step 3: $ pip3 --version

```
##### Commands for installing pip package manager for `python2`
```
Step 1: $ sudo apt-get -y install python-pip
Step 2: $ sudo pip2 install --upgrade pip 
               OR 
        $ sudo pip install --upgrade pip

Step 3: $ pip2 --version
              OR
        $ pip --version

```

##### Commands for installing all dependencies are given below. 

```
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
```                  

##### Commands for installing pycharm
```
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

```

#### Windows OS


##### Install Python3 (install python 3.6.4)

* Step 1: Download python form [this link](https://www.python.org/downloads/)

* Step 2: Refer [this link](http://www.openbookproject.net/courses/webappdev/units/softwaredesign/resources/install_python_win7.html) or [this link](https://www.youtube.com/watch?v=V_ACbv4329E) in oreder to install python


##### Install anaconda
* Step 1: Download Anaconda 5.1 
(python 3.6 version) using [this link](https://www.anaconda.com/download/#windows)

* Step 2: See the installation instruction given on [this link](https://conda.io/docs/user-guide/install/windows.html#install-win-silent)

Note: If you have any other version of python then install anaconda which supports that particular version of python 


##### Install dependencies using conda

```
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
```       
##### Issues with installing surprise package
* If you are facing issue for installing surprise then try the following links which can help you.
* If conda is not working then try to install surprise using pip
* See this [installation instructions](https://github.com/NicolasHug/Surprise#installation--usage)
* See these links if you have any issues.
    * [link 1](https://github.com/NicolasHug/Surprise/issues/89)
    * [link 2](https://github.com/NicolasHug/Surprise/issues/99)
    * [link 3](https://github.com/NicolasHug/Surprise/issues/21)
    * [link 4](https://groups.google.com/a/continuum.io/forum/#!topic/anaconda/yLH46ilPQeo)


##### Install Pycharm IDE


* Step 1: Download pycharm IDE community edition by using [this link](https://www.jetbrains.com/pycharm-edu/download/#section=windows)

* Step 2: Install `.exe` file.

## Code credit

Code credits for this code go to [Rounak Banik](https://github.com/rounakbanik) I've merely created a wrapper and necessary changes to get people started.
