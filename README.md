### Nosql-challenge

## Eat Safe, Love - Food Hygiene Ratings Analysis

### Overview

This repository contains the code and analysis for the Eat Safe, Love project, where we analyze food hygiene ratings data provided by the UK Food Standards Agency. The analysis aims to assist the editors of Eat Safe, Love magazine in identifying establishments for future articles.

### Dependencies
To run the code in this project, you will need to have the following dependencies installed:
- PyMongo: Used to interact with MongoDB from Python.
- Pandas: Used for data manipulation and analysis.
- pprint: Used for pretty-printing MongoDB documents.

You can install these dependencies using the following conda command:

```bash
conda install -c anaconda pymongo pandas
```

### Project Structure

- **Notebooks:**
  - `NoSQL_setup_starter.ipynb`: Setup of MongoDB database and data loading.
  - `NoSQL_analysis_starter.ipynb`: Exploratory analysis and queries on the database.
- **Data:**
  - `establishments.json`: JSON file containing establishments data.
- **README.md**: Documentation summarizing project setup, analysis tasks, and deployment instructions.

### Work Completed

- **Part 1: Database and Jupyter Notebook Set Up:**
  - Imported the establishments data from `establishments.json` into MongoDB.
  - Created the `uk_food` database and the `establishments` collection.
  - Confirmed database and collection creation, and displayed one document using `find_one()`.
  - Assigned the `establishments` collection to a variable for further analysis.

- **Part 2: Update the Database:**
  - Added information about the new halal restaurant, "Penang Flavours," to the database.
  - Found and updated the BusinessTypeID for "Restaurant/Cafe/Canteen" for the new restaurant.
  - Removed establishments within the Dover Local Authority from the database.
  - Converted string values of latitude, longitude, and RatingValue to numeric types.

- **Part 3: Exploratory Analysis:**
  - Answered specific questions posed by Eat Safe, Love using MongoDB queries.
  - Conducted analysis to identify establishments meeting certain criteria.
  - Displayed results using `count_documents()`, `pprint`, and Pandas DataFrame.

### Deployment and Submission
  - Cloned the repository to the local machine.
  - Added and committed all necessary files to the repository.
  - Submitted the GitHub repository link for grading.

### Comments
- All code files are well-commented to aid understanding.
- Followed the instructions provided in the assignment for each part.
- Completed all tasks outlined in the assignment prompt.

### References
- https://git.bootcampcontent.com/University-of-Adelaide/UADEL-VIRT-DATA-PT-12-2023-U-LOLC
- https://pandas.pydata.org/docs/index.html
- https://docs.python.org/3/library/pprint.html
- https://www.mongodb.com/docs/manual/reference/sql-comparison/
- https://www.mongodb.com/docs/
- https://www.mongodb.com/docs/manual/reference/operator/query-comparison/
- https://www.mongodb.com/docs/manual/reference/method/db.collection.aggregate/
- https://pymongo.readthedocs.io/en/stable/index.html
- https://www.mongodb.com/atlas
- https://www.mongodb.com/docs/atlas/getting-started/