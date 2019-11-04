# BusinessDataVisualization
Visualization of Airline performance using BTS (Bureau of Transportation Statistics) database.

#### Data 
Procure the BTS data from [here.](https://www.transtats.bts.gov/DL_SelectFields.asp?Table_ID=236&DB_Short_Name=On-Time)
Download monthly files that are needed to visualize (I have used the data that ranges from :June 2016- July2017). Utilize the lookup tables for features of the data. 

## Data Munging
Data wrangling, sometimes referred to as data munging, is the process of transforming and mapping data from one "raw" data form into another format with the intent of making it more appropriate and valuable for a variety of downstream purposes such as analytics.
Tool: Jupyter Notebook (Language: Python)

**Pandas** provide the necessary tools to perform data cleaning and munging for structured data. 

pandas can be installed via pip from [PyPI.](https://pypi.org/project/pandas/)

`
pip install pandas
`

If Anaconda distribution is installed then, install pandas as shown [here](https://docs.anaconda.com/anaconda/navigator/tutorials/pandas/)

```
We use pandas to merge all the monthly files and generate a combined .csv file, and selected a few 
airlines of interest. Pandas is used to extract the required data and finally, only the 
data required for those airlines are concatenated into a single data frame and made into a final .csv file.
```

The Jupyter Notebook can be found [here.](https://github.com/pavannaik3009/BusinessDataVisualization/blob/master/DataMunging.ipynb)

## Data Visualization
Tool: Tableau

Tableau is a Data Visualisation tool that is widely used for Business Intelligence. It helps create interactive graphs and charts in the form of dashboards and worksheets to gain business insights. 

Objective: Finding reasons and trends for Airline delays in different cities in the USA.

### Trench Analysis

It can be seen that the flight delay time is correlated with the departure delay time

<img width="300" alt="Screen Shot 2019-11-04 at 12 32 40 AM" src="https://user-images.githubusercontent.com/43712046/68103325-e06aea80-fe9b-11e9-8664-bd32b9b8c71a.png">

ExpressJet's delay from Origin (In figure below: Origin=Chicago,ORD)

<img width="995" alt="Screen Shot 2019-11-04 at 4 14 33 PM" src="https://user-images.githubusercontent.com/43712046/68162723-4b5d0580-ff1e-11e9-8206-f4fd593f4206.png">


The Tableau workbooks can be found in the repository.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
