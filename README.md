# databricks-workflow-ex

This project hosts the notebooks that were created and used in Azure Databricks. The notebooks each perform a task in the ETL pipeline for a songs dataset. These three notebooks are used in-conjunction with eachother to create a workflow, where one notebook begins to run after the last. The goal is that whenever the songs dataset is updated, the workflow will run, and properly extract the new dataset, transform it to the format that is desired, and load it into a SQL database. The workflow was succesfully setup in Azure Databricks as well. A demonstration of each notebook, and proof of a successfully setup workflow is shown below.

### Extract

