# lab04.5-collect_and_analyze_data_from_a_scoring_service - Collect and Analyze Data from a scoring service
This hands-on lab guides you through collecting Machine Learning scoring  data using [Azure Machine Learning Services](https://docs.microsoft.com/en-us/azure/machine-learning/preview/overview-what-is-azure-ml) with the Azure Machine Learning Workbench. 

In this workshop, you will:
- [ ] Use the Azure Machine Learning Services collection module to view scoring data from API calls
- [ ] Use Azure Storage to view the results

You'll focus on the objectives above, not Data Science, Machine Learning or a difficult scenario.  

***NOTE:*** There are several pre-requisites for this course, including an understanding and implementation of: 
  *  Programming using an Agile methodology
  *  Machine Learning and Data Science
  *  Intermediate to Advancced Python programming
  *  Microsoft Azure Storage concepts
  *  Working with the Azure Portal

There is a comprehensive Learning Path you can use to prepare for this course [located here](https://github.com/Azure/learnAnalytics-CreatingSolutionswiththeTeamDataScienceProcess-/blob/master/Instructions/Learning%20Path%20-%20Creating%20Solutions%20with%20the%20Team%20Data%20Science%20Process.md).

## Introduction and setup 

***NOTE***: These steps must be completed ***prior*** to attempting this workshop.
  *  You will need a Microsoft Azure account. You can use a production Azure account if you are able to create objects. You can also use your Microsoft Developer Network (MSDN) account (if you have one) to complete this workshop. If you don't have access to a corporate or MSDN account you can create a free account [using this process](https://azure.microsoft.com/free/).
  *  You will need an Azure Machine Learning Services account. [Open this reference](https://docs.microsoft.com/en-us/azure/machine-learning/preview/quickstart-installation), and complete only the sections marked **"Sign in to the Azure portal"** and **"Create Azure Machine Learning accounts"**. Write down the *Experimentation account name* and bring it to class.
  *  You can install the Azure Machine Learning Workbench locally:
        *  [Open this reference](https://docs.microsoft.com/en-us/azure/machine-learning/preview/quickstart-installation) and follow the sections marked **Install Azure Machine Learning Workbench on Windows** or choose your OS type from the instructions there.

  *  Or you can use a Windows Data Science Virtual Machine (DSVM) to run this lab: 
        *  [Navigate to this path](https://azuremarketplace.microsoft.com/en-us/marketplace/apps/microsoft-ads.windows-data-science-vm), and create a Windows Azure Data Science Virtual Machine (DSVM). Choose a VM size of: DS3_V2, with 4 virtual CPUs and 14-Gb RAM. When the DSVM is deployed, start it using the [Azure portal.](https://portal.azure.com)
        *  After you create and Start the DSVM, log in to it and double-click the "Install Azure Machine Learning Workbench" icon. Finish the installation by following the on-screen instructions. The installer downloads all the necessary dependent components, such as Python, Miniconda, and other related libraries. The installation might take around half an hour to finish all the components. When complete, the Azure Machine Learning Workbench is installed in the following directory: C:\\Users\\%USERNAME%\\AppData\\Local\\AmlWorkbench

We will review these articles in class: 
  1.  [Model data collection](https://docs.microsoft.com/en-us/azure/machine-learning/preview/how-to-use-model-data-collection)
  2.  [Azure Machine Learning Model Data Collection API reference](https://docs.microsoft.com/en-us/azure/machine-learning/preview/model-data-collection-api-reference)

### Lab: Collecting Model Data
In this lab you'll use Python to collect scoring data 
- [ ] Open the Azure Machine Learning Services Workbench tool locally or on your Data Science Virtual Machine. 
- [ ] [Navigate to this resource](https://docs.microsoft.com/en-us/azure/machine-learning/preview/how-to-use-model-data-collection), and complete all sections there.

## Workshop Completion
In this workshop you learned how to:
- [ ] Use the Azure Machine Learning Services collection module to view scoring data from API calls
- [ ] Use Azure Storage to view the results

You may now decommission and delete the following resources if you wish:
  * The Azure Machine Learning Services accounts and workspaces
  * Any Data Science Virtual Machines you have created. NOTE: Even if "Shutdown" in the Operating System, unless these Virtual Machines are "Stopped" using the Azure Portal you are incurring run-time charges. If you Stop them in the Azure Portal, you will be charged for the storage the Virtual Machines are consuming. 