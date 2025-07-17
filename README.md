# Data_analysis_tittanic_dataset
Data analysis of titanic dataset
# Exploratory Dta Analysis (EDA)
## Analysing the Data by visualizations
- Using cleaned titanic dataset for EDA
- - Using python libraries like Pandas, Numpy, Matplotlib.pyplot, Seaborn 
  ### info()
    -Knowing the information about missing values and datatype of the columns present in Dataset.
  ### describe()
    -Gives the count, Mean, Median, Mode, 25%, 75%, Maximum vale and minimum value of the columns in the dataset.
  ### shape
    -Give the number of columns and rows of the dataset.
  ## PLOTS
    ### Histograms
      -Gives the range of values which are widespread and distributed as bargraphs.
    ### Boxplot
      -Gives the outliers present in data. Outliers are the points which are apart from the interquartile range(IQR)
    ### Heatmap
      -Used for finding the correlation and interrealtion between the columns in the dataset(only for numerical datas). It lies betwee -1 and +1
      - -1 gives the strong negative correlation(inversely proportional)
      - +1 gives the strong positive corrletaion(directly proportional)
      - 0 (no correlation)
  ### countplot
      -bar chart that shows how many times each category appears in the data.
      - From the graph, we can draw a inference that the number of male surived is lesser than number of female survived. More number of female are survived compared to Males.
  # EDA helps in understanding:
- The structure and health of the data
- Patterns, distributions, and relationships
- Outliers and missing values
- Useful features for building ML models

