# MetroFlow: Human Mobility Datasets in the Complex Metro System of Shanghai

MetroFlow is an open-sourced, city-scale metro flow dataset, covering the period of May-August 2017 and 302 metro stations in Shanghai, China.  This codebase contains jupyter notebooks utilized during dataset organization and analyses.



<img src="Overviewcut.jpg" width="100%" class="center">  



### Processing Pipeline
The project follows a sequential workflow:

1. **Step 1**: Extract trips from transaction records and label trips.  (step1_LabelUser.ipynb)
2. **Step 2**: Extract OD flow at a 10-minute temporal resolution.  (step2_ExtractOD.ipynb)
3. **Step 3**: Extract In-Out flow at a 10-minute temporal resolution. (step3_ExtractFlow.ipynb)



### Directory Structure

- **Analysis/**: Contains analysis scripts for technical validation
- **results/**: Stores analysis results
- **tool/**: Includes tool scripts for metadata acquisition and data processing
- **Data/**: Homes data files 


### Requirements

 dependencies are listed in `requirements.txt`

Install the required dependencies to get started:
```
pip install -r requirements.txt
```

