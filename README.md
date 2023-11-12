# databricks-workflow-ex

This project hosts the notebooks that were created and used in Azure Databricks. The notebooks each perform a task in the ETL pipeline for a songs dataset. These three notebooks are used in-conjunction with eachother to create a workflow, where one notebook begins to run after the last. The goal is that whenever the songs dataset is updated, the workflow will run, and properly extract the new dataset, transform it to the format that is desired, and load it into a SQL database. The workflow was succesfully setup in Azure Databricks as well. A demonstration of each notebook, and proof of a successfully setup workflow is shown below.

### Extract

Here, I extract the data from the dataset and store the raw data.

![image](https://github.com/Ninsta22/databricks-workflow-ex/assets/55768636/27664504-68fc-4ed2-96cb-a13617b91251)

### Transform

Here, I take the raw song data, and properly change trim the dataset into my desired song dataset. Then, I resave it into a new data sink.

![image](https://github.com/Ninsta22/databricks-workflow-ex/assets/55768636/e94a6a81-6e20-4066-a960-1d5a8df275a6)

### Load

Finally here, I begin loading and querying the data to make sure that all previous steps were properly created.

![image](https://github.com/Ninsta22/databricks-workflow-ex/assets/55768636/0bfa23b9-3d0d-4b15-9154-93619b2f1fa8)

### Workflow

Here, we demonstrate the created workflow, that properly is created and ran off of a Personal Cluster.

![image](https://github.com/Ninsta22/databricks-workflow-ex/assets/55768636/84d2aa72-0dff-49f3-9774-38657e9e86d5)
