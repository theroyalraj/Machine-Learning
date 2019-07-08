# Machine-Learning
##Project:Applying Machine Learning technique to recommend movies.

Install

This project requires Python 2.x or Python 3.x and the following Python libraries installed:

    NumPy
    Pandas
    MatplotLib
    Seaborn
    Surprise
    Sklearn

You will also need to have software installed to run and execute a Jupyter Notebook.


If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included. Make sure that you select the Python 3.7 installer and not the Python 2.x installer. Surprise can then be installed using one of the following commands:

With pip (you'll need numpy, and a C compiler. Windows users might prefer using conda):

$ pip install numpy
$ pip install scikit-surprise

With conda:

$ conda install -c conda-forge scikit-surprise

For the latest version, you can also clone the repo and build the source (you'll first need Cython and numpy):

$ pip install numpy cython
$ git clone https://github.com/NicolasHug/surprise.git
$ cd surprise
$ python setup.py install


Code:

A template notebook is provided as NF-Recommnedation-System.ipynb. All the code is included in the notebook, you will be required to use the notebook to implement the basic functionality of the project and get the movies recommended.

Run:

In a terminal or command window, navigate to the top-level project directory Machine-Learning/ (that contains this README) and run one of the following commands:

ipython notebook NF-Recommnedation-System.ipynb

or

jupyter notebook NF-Recommnedation-System.ipynb

This will open the Jupyter Notebook software and notebook file in your browser.

Data:

While no dataset is directly provided with the project, you will be required to download and use the Netflix Prize data
(Dataset from Netflix's competition to improve their reccommendation algorithm) from the given link.

link:-https://www.kaggle.com/netflix-inc/netflix-prize-data (682mb)

In this Project only combined_data_1.txt and movie_titles.csv is used as this prize dataset is too huge to handle. Altough in the project codes the code to add the other 3 dataset is written but commented out.
