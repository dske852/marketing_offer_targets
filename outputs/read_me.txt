Files:
Subfolder: Outputs
Technical Report.pdf - Technical Report about steps and processes done during modeling
executive_summary.pdf - Executive summary with summarizations of results
targeted_sinal_selection.csv - the final list of clients to be targeted based
targets_and_details.csv - same as 'targeted_sinal_selection.csv' but with all available data columns about clients included

Subfolder: Models_jupyter
Jupyter notebooks for:
Data preparation - data_preparation.ipynb
CL, CC, MF models - CC_model.ipynb, CL_model.ipynb, MF_model.ipynb
Final selection of 100 clients to be targeted - final_selector.ipynb

Should be run in the same order, however, there is really no need to re-run it again as all outputs arealready printed in jupyter notebooks

Subfolder: data
data_preparation - data provided in your Excel, just separated to CSVs for more convenient load into Jupyter, needed to run file 'data_preparation.ipynb'
final_selector - data needed to run script for final selection of clients to be targeted, 'final_selector.ipynb'
models - train and test datasets after edits and adjustments, needed to load for running Jupyter notebooks related to models (CC_model.ipynb, CL_model.ipynb, MF_model.ipynb)
