# Bank Marketing Campaign Data Cleaning
# Bank Marketing Campaign Data Cleaning

This project focuses on cleaning, reformatting, and structuring the data collected by a bank during a marketing campaign. The objective is to ensure the data conforms to specific data types and formats so it can be easily stored in a PostgreSQL database and used for analysis in future campaigns.

The project includes a Jupyter Notebook and Python scripts for data cleaning and transformation, as well as the cleaned data saved into separate CSV files for different aspects of the marketing campaign.

bank-marketing-campaign-cleaning/
│
├── data/
│   ├── bank_marketing.csv             # Raw input data file
│   ├── client.csv                    # Cleaned client data
│   ├── campaign.csv                  # Cleaned campaign data
│   └── economics.csv                 # Cleaned economics data
│
├── notebooks/
│   └── data_cleaning_notebook.ipynb  # Jupyter Notebook with the data cleaning process
│
├── scripts/
│   └── data_cleaning.py              # Python script for data cleaning (if applicable)
│
├── README.md                         # Project documentation and instructions
├── requirements.txt                  # Python dependencies list
└── .gitignore                        # Git ignore file (to exclude unnecessary files)



## Files and Directories

### `data/`
Contains the raw and cleaned data files.

- **`bank_marketing.csv`**: The raw input data file provided by the bank.
- **`client.csv`**: Cleaned client-related data, including client ID, age, job, marital status, education, credit default, and mortgage information.
- **`campaign.csv`**: Cleaned campaign-related data, including the number of contact attempts, campaign outcomes, and last contact date.
- **`economics.csv`**: Cleaned economic indicators, including the consumer price index and euribor three-month rate.

### `notebooks/`
Contains a Jupyter notebook detailing the data cleaning process.

- **`data_cleaning_notebook.ipynb`**: A Jupyter notebook outlining each step of the data cleaning process, including code and explanations for each transformation.

### `scripts/`
Contains Python scripts for data cleaning.

- **`data_cleaning.py`**: A Python script that automates the data cleaning process. It loads the raw data, performs transformations (e.g., handling missing values, changing data types), and splits the data into three cleaned CSV files (`client.csv`, `campaign.csv`, `economics.csv`).

### `requirements.txt`
Contains a list of Python dependencies required to run the project. To install them, run:
```bash
pip install -r requirements.txt
