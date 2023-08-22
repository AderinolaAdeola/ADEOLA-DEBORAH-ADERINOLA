# UNICORN EXPLORATORY ANALYSIS
The exploratory analysis of private companies named UNICORN is produced by Jupyter Notebook. Numpy,Pandas, seaborn and matplotlib.pyplot are used to create both Statistical and visualize analysis. The data was obtained from Quantum Analytics. 
Steps Taken: 
The named libraries are import to the notebook repectively. 
The data are wrangle and manipulate; 
  For data wrangling-the date column changed to datetime using .datetime ,valuation and Funding (as currency)symbols are changed by .replace() 
  For data manipulate- additional columns(age join and interest(return))are added to the existing dataframe 
The data are validated and cleaned by checking the dataframe column and missed data; the missed data are check by .isnull() and the missed data are later filled by forwardfill (.ffill()) method, the duplicate data are removed and data type is changed by.astype() code. 
The insights are analysed using univariate(one feature),bivariate(two features) and multivariate (more than two features) analysis.
The key insights are used to extract data-drive recommendations.
