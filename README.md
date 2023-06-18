# Berk_Capstone
### Analysis of Natural Gas Transmission Pipeline Incident 

**Author**
Jetinder Singh

#### Executive summary

#### Rationale
Why should anyone care about this question?
Natural gas is an important utility. Natural gas service providers typically operating at high pressure, medium pressure and low pressure system to facilitate transportation of natural gas. Although, natural gas is considered to be one of the clean and safest energy source, incident occurring in the natural gas transmission and distribution system may be significantly fatal. They are typically categories as “Low- Probability High- Consequence” incident during the risk assessment process.


#### Research Question
What are you trying to answer?
As the natural gas utility industry is highly regulated, service providers are legally required to report incident resulting in any fatality or incident cost exceeding USD50,000. The incidents reports are typically reported to PHMSA in USA and is the only publicly available incident data source.
The current data is highly biased, it is collection all the incident data collect on a yearly basis

#### Data Sources
What data will you use to answer you question?
with the application of OneClassSVM and similar methods, the objective of the analysis is to explore the suitabilty and acceptability of data to identify potential incident along with its probability. 

#### Methodology
What methods are you using to answer the question?
For the currently assessment, following methods were used: 
1. OneClassSVM
2. IsolationForest
3. LocalOutlierFactor

#### Results
What did your research find?
As the current data is highly biased, applying OneClassSVM method and similar other Anomaly Dectection methods require further investigation.
Although, OneClassSVM obtained 0.7645 accuracy score. However,due to biased data, LocalOutlinerFactor failed to execute the analysis. 

#### Next steps
What suggestions do you have for next steps?

Next Steps: 

split the data based on the pipeline function.
perahsp explore methods to generate synthetic data.
use of principal component analysis to optimise analysis of the data. 

#### Outline of project

- [[Capstone_EDA_JS](https://github.com/J51ngh/Berk_Capstone/blob/main/Capstone_EDA_JS.ipynb)] (May require download as file is too big to render)
- [[Capstone_OCSVM_JS](https://github.com/J51ngh/Berk_Capstone/blob/main/Capstone_OCSVM_JS.ipynb)] 
- [[Capstone_LOF_JS](https://github.com/J51ngh/Berk_Capstone/blob/main/Capstone_LOF_JS.ipynb)]


##### Contact and Further Information
