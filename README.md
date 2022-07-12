# Data Engineering - Data Exploration for M&A predictive modelling


## <a id="overview"></a>Overview
Once the data acquisition phase is complete and we have our initial feature space, the Data Exploration phase starts. This phase enables us to uncover insights from the data and/or identify areas or patterns to dive into and further explore. It allows for a deeper, more detailed, and better understanding of the data. This phase will also reveal any problems that the datasets might have, including dataset imbalance, multicolieanirity, missing values, outliers etc. After the problems with the dataset is identified the AI team can start devising strategies towards solving or smoothing them out.

This guide will walk through the exploration process of the M&A dataset we have aquired during the Data Ingestion phase in our Blueprint Data Ingestion for M&A predictive modelling. To learn more about the business incentive and data aquisition process of the analysed dataset please visit the before-mentioned guide.

## <a id="disclaimer"></a>Disclaimer
The source code presented in this project has been written by Refinitiv only for the purpose of illustrating the concepts of creating example scenarios using the Refinitiv Data Library for Python.

***Note:** To [ask questions](https://community.developers.refinitiv.com/index.html) and benefit from the learning material, I recommend you to register on the [Refinitiv Developer Community](https://developers.refinitiv.com)*

## <a name="prerequisites"></a>Prerequisites

To execute any workbook, refer to the following:

- A Refinitiv Desktop license (Refinitiv Eikon or Refinitiv Workspace) that has API access 
- Tested with Python 3.7.13
- Packages: [plotly](https://pypi.org/project/plotly/), [scipy](https://pypi.org/project/scipy/), [statsmodels] (https://pypi.org/project/statsmodels/), [refinitiv.data](https://pypi.org/project/refinitiv-data/)
- RD Library for Python installation:  '**pip install refinitiv-data**'


  
## <a id="authors"></a>Authors
* **Haykaz Aramyan**
