# Azure-MLOps Template Hub for Manufacturing

**ML development lifecycle**

![ml-lifecycle](https://github.com/microsoft/MLOpsPython/raw/master/docs/images/ml-lifecycle.png)

**DevOps for Machine Learning (MLOps)**

![MLOps](MLOps.PNG)

[Azure ML services](https://azure.microsoft.com/en-us/services/machine-learning/) and [Azure MLOps](https://azure.microsoft.com/en-us/services/machine-learning/mlops/) provide solutions of ML/AL lifecycle. And [MLOpsPython](https://github.com/microsoft/MLOpsPython) is a template of code and pipeline definitions for a Azure machine learning project that show how to automate an end to end ML/AI workflow.

## CLI Tool
This hub offers a [CLI](https://github.com/MFG-Azure-MLOps-Hub/CLI) tool to simplify the deployment the template into Azure ML services and Azure DevOps. Here is a [document in MLOpsPython repository](https://github.com/microsoft/MLOpsPython/blob/master/docs/getting_started.md) to teach how to create the Azure DevOps project by manual, The [CLI](https://github.com/MFG-Azure-MLOps-Hub/CLI) tool provide a command to build it automatically. see [CLI readme] (https://github.com/MFG-Azure-MLOps-Hub/CLI).

```
python hub_install.py  --org_url https://dev.azure.com/your_org 
                        --project_name mlopsproj 
                         --source_repo_url https://github.com/MFG-Azure-MLOps-Hub/MLOpsImgClass.git
```

## Template
As a hub to provide templates for industrial solution, the templates are orginized in multiple layers and tempates can reused as **base template** to make the template can focus on AI/ML algorithmn, data and business scenario.

#### Root Template
The Root Template is [MLOpsPython](https://github.com/microsoft/MLOpsPython). All the templates in this hub are extended from it.

#### Algorithmn Templates
* [Image Classification](https://github.com/MFG-Azure-MLOps-Hub/MLOpsImgClass)
* [Object Detection](https://github.com/MFG-Azure-MLOps-Hub/MLOpsObjectDetection_ssd_resnet50_v1_fpn)
* XGBoost for Classification/Regression
* SKLearn for Classification/Regression
* Anormaly detection

#### Industrial Templates [TODO]
* Quality assurance - Printed circuit board 
* Safety - Helmet Detection
* Supply Chain Forecast
* Defect dectection/classification
