# Training Notes: Azure Assiciate Data Scientist (DP-100)

## General

* [AzureML Feature Requests](https://feedback.azure.com/forums/34192--general-feedback)

## Day 1 - 01.02.2021

### Module 1:

![alt text](./Azure_Machine_Learning_in_Conext.png)

![alt text](./Machine_Learning_Operationalization.png)

![alt text](./Azure_Machine_Learning_Workspace.png)

![alt text](./The_Azure_Machine_Learning_SDK_for_Python.png)

![alt text](./Azure_Machine_Learning_CLI_Extension.png)

![alt text](./Visual_Studio_Code.png)

![alt text](./Azure_Machine_Learning_Compute_Instances.png)

![alt text](./Preparations.png)

![alt text](./Lab_Create_an_Azure_Machine_Learning_Workspace.png)

### Lab 1:

* [link to MSLEARN-DP100](https://microsoftlearning.github.io/mslearn-dp100/instructions/01-create-a-workspace.html)

Basics
* Subscription: Azure Pass - Sponsorship
* Resource group: (New) rg-ml-001
* Region: West Europe
* Workspace name: ml-001
* Storage account: (new) ml0019425880163
* Key vault: (new) ml0015577166267
* Application insights: (new) ml0016839476282
* Container registry: None
* Networking: Connectivity method
* Public endpoint (all networks): Advanced
* Encryption type: Microsoft-managed keys
* Enable HBI Flag: Disabled

ssh-key:
az_training_dp_100(.pub)
passphrase: MicroBicro0148

## Module 2:

### Azure Automated Machine Learning

![alt text](./Automated_Machine_Learning.png)

### Lab 2:

* [link to MSLEARN-DP100](https://microsoftlearning.github.io/mslearn-dp100/instructions/02-automated-ml.html)


### Azure Machine Learning Designer


![alt text](./What_is_Azure_Machine_Learning_Designer.png)
![alt text](./Training_Pipelines.png)
![alt text](./Inference_Pipeline.png)
![alt text](./Publishing_a_Service_Endpoint.png)


### Lab 3:

* [link to MSLEARN-DP100](https://microsoftlearning.github.io/mslearn-dp100/instructions/02-automated-ml.html)

* Model Results:
    
        ./mslearn-dp100/labs/Lab3/DiabetesLogisticRegression_model_outputs


## Day 2 - 02.02.2021

### Introduction to Experiments

![alt text](./Publishing_a_Service_Endpoint.png)

![alt text](./Running_an_Experiment_Inline.png)

![alt text](./Running_a_Script_as_an_Experiment.png)


### Training an Resitering Models

![alt text](./Training_a_Model_in_a_Script.png)



## Datastores & Datasets

![alt text](./What_are_Datastores.png)

![alt text](./Working_with_Datastores.png)

![alt text](./What_are_Datasets.png)

![alt text](./Creating_and_Registering_Datasets.png)

![alt text](./Working_with_Tabular_Datasets.png)

![alt text](./Dataset_Versioning.png)

## Environments

![alt text](./Explicitly_Creating_Environments.png)

![alt text](./Configuring_Environment_Containers.png)

[Curated environments - Azure Machine Learning | Microsoft Docs](https://docs.microsoft.com/en-us/azure/machine-learning/resource-curated-environments)

![alt text](./Registering_and_Resuing_Environments.png)

![alt text](./Compute_Options_for_Experiment_Runs.png)

![alt text](./Create_a_Computing_Cluster.png)

![alt text](./Attaching_Azure_Databricks_Compute.png)

![alt text](./Using_Compute_Targets.png)

[Set up local compute targets](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-attach-compute-targets#local)
[Configure and submit training runs](https://docs.microsoft.com/de-de/azure/machine-learning/how-to-set-up-training-targets)

## Pipelines

![alt text](./Pipelines.png)

![alt text](./What_is_a_Pipeline.png)

![alt text](./Pipeline_Steps.png)

![alt text](./Passing_Data_Between_Steps.png)

![alt text](./Pipeline_Step_Reuse.png)

![alt text](./Pipeline_Endpoints.png)

![alt text](./Pipeline_Parameters.png)

![alt text](./Scheduling_Pipelines.png)

![alt text](./Event-Driver_Workflows.png)

![alt text](./What_is_Real_Time_Inferencing.png)

![alt text](./Deploying_a_Real_Time_Inferencing_Service.png)

![missing](./Consuming_a_Real_Time_Inferencing_Service.png)

## Inferencing

![alt text](./What_is_Batch_Inferencing.png)

![alt text](./Creating_a_Batch_Inferencing_Pipeline.png)

![alt text](./Publishing_a_Batch_Inferencing_Service.png)

![alt text](./What_is_Continuous_Integration_and_Delivery_CICD
.png)

![alt text](./Azure_Machine_Learning_and_Azure_Pipelines.png)

![alt text](./Azure_Machine_Learning_and_GitHub_Actions.png)

## Model Tuning

### Hyperparameter Tuning

![alt text](./Tuning_Hyperparameters_with_Hyperdirve.png)


### Automated Machine Learning

![alt text](./Prepare_Data_for_Automated_Machine_Learning.png)


![alt text](./Running_an_Automated_Machine_Learning_Experiment.png)


![alt text](./Monitoring_and_Reviewing_Automated_ML_Runs.png)


## Responsible Machine Learning

![alt text](./Responsible_ML_Agenda.png)

![alt text](.The_Data_Privacy_Problem/.png)

![alt text](./What_is_Differential_Privacy.png)

![alt text](./Epsilon-The_Privacy_Loss_Parameter.png)

![alt text](./Model_Interpretability_in_Machine_Learning.png)

![alt text](./Global_and_Local_Feature_Importance.png)

![alt text](./Adding_Explainations_to_Training_Experiments.png)

![alt text](./Visualizing_Model_Explainations.png)

![alt text](./Interpretibility_during_Inference.png)

![alt text](./What_is_Fairness.png)

![alt text](./Evaluating_Model_Fairness.png)

![alt text](./Mitigating_Unfairness.png)

* [Co-Designing Checklists to Understand Organizational
Challenges and Opportunities around Fairness in AI](http://www.jennwv.com/papers/checklists.pdf)



## Monitoring Models

### Application Insights

![alt text](./What_is_Application_Insights.png)

![alt text](./Enabling_Application_Insights.png)

![alt text](./Capturing_and_Viewing_Application_Insights_Data.png)

### Data Drift

![alt text](./Creating_a_Data_Drift_Monitor.png)

![alt text](./Data_Drift_Schedules_and_Alerts.png)

![alt text](./Reviewing_Data_Drift.png)

![alt text](./.png)

![alt text](./.png)

![alt text](./.png)
