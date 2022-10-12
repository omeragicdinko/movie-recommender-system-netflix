# movie-recommender-system-netflix

- Important Notes:

1. If you already have some steps from the list below done, please skip those steps

2. If you are unfamiliar with Jupyter Notebook, please refer to the following link: 
   https://www.codecademy.com/article/how-to-use-jupyter-notebooks

3. The results may be slightly different than the ones shown in the research paper due to the random split of data set into training
   and testing sets and/or other possible parameter changes.

4. I have submitted the data set, which I used, together with other files on LMS, but you can download it from the source as 
   well: https://www.kaggle.com/shivamb/netflix-shows (If the version on Kaggle is newer than mine, the results might be different or
   an error might occur)


- Since the scripts are written in Python in Jupyter Notebook, you will have to do some preparations:

1. Install Python 3 (https://www.python.org/downloads/) 

2. Install pip3 (https://monsterhost.com/what-is-pip-and-how-to-install-pip3/)

3. Install Jupyter Notebook (https://jupyter.org/install)

4. Open the script file in Jupyter Notebook and install all python libraries that are not installed on your machine, but
   are imported in the first block of the script (https://packaging.python.org/en/latest/tutorials/installing-packages/)

5. Restart the Jupyter Notebook and open the script file again in case you have installed new python libraries

6. Download the data set and place it in the same folder with the script (If you are using Linux or Mac, please change the path to the
   data set file in the function 'pd.read_csv' accordingly -- the function is called multiple times in the script, so please change it
   in all occurences)

7. To run all code blocks, you can either click on the 'Run' button to run each block individually, or you can click on the 
   'Restart the kernel, then re-run the whole Notebook' button (Code blocks should be run in the order in which they
   appear in the script file)
