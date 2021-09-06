# Portfolio Optimization


### 1. Installing Dependencies
Can be installed using `pip install` **or** `conda install` for *Anaconda environment*

- Python 3.7 
- Libraries 
  - numpy (1.17.0)
  - pandas (0.24.2)
  - scipy (1.3.1)
  - matplotlib (3.1.1)
    
### 2. Usage Instructions
 
Steps to be followed:                                                                             
- **Data:** Current implementation is based on data obtained from Yahoo Finance. Convert your data to the specific format and place under *data* folder.
- **Baseline:** Update `BASE_LINE` in `optimizer.ipynb` to compare the portfolio's performance   
- **Stocks:** Update `SYMBOLS` in `optimizer.ipynb` to relevant stocks in the portfolio                                  
- **Allocation:** Update `allocations` in `optimizer.ipynb` to the allocation of stocks in the portfolio (must sum to 1)
- **Sampling Frequency:** Update `sampling_freq` in `optimizer.ipynb`. Currently, configured for daily, use `weekly: 52`,` monthly: 12` 
- **Risk Free Rate:** Update `risk_free_rate` (must be in percentage) in `optimizer.ipynb`. Configure it with the minimum return rate, if the amount was invested in fixed returns options such as savings account/fixed deposits etc. 
- **Start and End Date:** Update `start` and `end` date in `optimizer.ipynb`.
- **Initial Investment:** Update `initial_investment` in `optimizer.ipynb`.  