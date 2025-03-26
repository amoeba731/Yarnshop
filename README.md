Yarnshop Overview
With another craft store closing announced in the news, my desire to support my local yarnshop (often refered to as LYS in the crafting world) is increasing.  Unfortunately, my budget does not always allow for "free range" shopping at the store.  Finding craft patterns that are available for free, allows me to have more room in the budget for craft supplies.


Features: 
1. Loading Data
    For this project I used two sets of data, the first set is a csv created by webscraping my LYS, ReBelle, for a list of the yarn they carry as stock.  My second set of data is a csv file I created by taking the ReBelle stock list and making API requests for each yarn from the API for Ravelry.com. The code I used to make those API requests can be found in the ravelry_api_code.ipynb file included with the project.

2. Clean and operate on the data while combining them.
    I cleanded and combined my two datasets by using a pandas merge on them. In my project I also calculate value counts on some of the data and merge them together to create a new dataframe.

3. Visualize / Present your data. 
    Data visualization is presented at the end of the notebook with a pie plot, a stacked bar plot and a scatter plot.

4. Best practices
    These include annotations in every code block to provide insight, as well as creating a virtual environment to work in . 

To run project:
    1. Make a personal copy of the project file by cloning it from https://github.com/amoeba731/Yarnshop 
    2. Using Gitbash/Terminal go to the location where the project clone was saved on personal machine 
    3. Create virtual environment, using Gitbash/Terminal
    for a Windows computer: 
        create the environment using <python -m venv venv>,
        activite the environment with <venv/Scripts/activate>,
        load the requirements file for the project with     <pip install -r requirements.txt>, and explore the project in the yarnshop.ipynb file.
        close the virtual environment when done with <deactivate>
     for a Mac/Linux computer:
        create the environment using <python3 -m venv venv>,
        activite the environment with <venv/bin/activate>,
        load the requirements file for the project with     <pip install -r requirements.txt>, and explore the project in the yarnshop.ipynb file.
        close the virtual environment when done with <deactivate>
    
