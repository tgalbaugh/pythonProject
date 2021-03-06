This is a Google Colab Notebook [click here to open](https://colab.research.google.com/drive/1fwiQZodWSqLg7VasGCBPDztDxdvEVeFx?usp=sharing)

**This project is a simplified version of a project done for my work.   To protect proprietary company information several features that exist in the work project do not exist here include:**
- Mounting Google Drive to read/write files from Shared Drives
- Importing and Joining on BiqQuery tables via Pandas data frames
- Uploading of the completed CSV into Google BigQuery

**A one-paragraph or longer description of what your project is about. Do not skip this.**
Import a CSV containing raw warehouse productivity data and modify it to match the required schema of the BigQuery table it will be uploaded to
- Create an anonymized and randomized the CSV source file
- Import the source CSV of warehouse productivity data in a Pandas Dataframe. 
- Remove unneeded fields
- Add fields that are not in the raw CSV but needed for the BigQuery table it will be uploaded to
- Change fields to the correct data types to match the BigQuery schema
- Analyze data
- Add data visualizations
- Export data to a CSV that can be uploaded to the BigQuery table

**Relevant packages that need to be installed to run the project. This can be a requirements.txt, a config.py file, or just commands formatted neatly in markdown on your readme that say “pip install pandas” for example. But you have to specify which packages need to be installed. **

If you do not have the following installed you will need to open a code cell and run each of the following
- !pip install pandas
- !pip install numpy
- !pip install datetime
- !pip install pytz
- !pip install matplotlib

**Which 3+ features you have included from the below lists to meet the requirements**
- Read in data from a local csv, excel file, json, or any other file type. There are many ways to do this, but using Pandas read_ functions is pretty easy.
- Use custom functions or lambdas to perform specific operations to clean or manipulate your data, return those values, then use them in other parts of your project.
- Use at least 5 different built-in Python functions to find out something about your data. If you had a list for example, finding the length of that list with len(<list>) does tell us a little bit about the data. 
- Make 2 basic plots with matplotlib, seaborn, or any other kind of visualization library that you think looks interesting.
- If using some format other than a notebook, make sure your README explains your project. 
  
**Any special instructions are required for the reviewer to run your project. (For example: “run python main.py” from the command line)**
- This is a Google Colab Notebook [click here to open](https://colab.research.google.com/drive/1fwiQZodWSqLg7VasGCBPDztDxdvEVeFx?usp=sharing)
- Run the Python by clicking the "Run Cell" button or Runtime>Run All from the menu
- You will get a pop up indicating this was not created by Google.   Click Run Anyway
- A CSV is generated.  Click on the folder icon on the left of the Google Colab Notebook, look for output.csv
  
**Guide to using markdown for README.md files (https://guides.github.com/features/mastering-markdown/)**
**Describe the data used in the analysis in the README file.**
