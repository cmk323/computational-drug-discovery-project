# computational-drug-discovery-project
The goal of this project is to create a linear regression model that utilizes ChEMBL bioactivity data to generate inhibitor bioactivity predictions with respect to a specified target of interest. The test case shown here uses epidermal growth factor receptor (EGFR) as a target. This protein was selected as a target of interest due to its applications in cancer drug development.

# to do
- automate the target selection process (select ChEMBL ID with the most hits for IC50 activity data from search results)
- test different regressors (random forest used as default)
- implement a third "intermediate" bioactivity classifer in addition to active or inactive
