# Using AI OpenScale to check accuracy of Keras Neural Network, classifying images

The purpose of these Notebooks is to demonstrate how to use AI OpenScale for testing accuracy on Keras-based model that is classifying images (in this example, with handwritten digists from MNIST data).  

In order to use AI OpenScale, the trained model is deployed on Watson Machine Learning.  

## Pre-requisities
In order to be able to run and complete this notebook, you'll need to have:
- IBM Cloud account at https://cloud.ibm.com
- Watson Studio account at https://dataplatform.ibm.com
- V2 notebook from this repo, loaded in Jupyter Notebook in Watson Studio, with kernel "Python 3.5 with Spark".
- IBM Cloud Object Storage (COS), deployed in IBM Cloud. If not done already, deploy from [Catalog](https://cloud.ibm.com/catalog/services/cloud-object-storage)
- IBM AI OpenScale (AIOS), deployed in IBM Cloud.  If not done already, deploy from [Catalog](https://cloud.ibm.com/catalog/services/watson-openscale)

## Instructions
1. Go to Watson Studio at https://dataplatform.ibm.com
2. Either create a new project or open an existing project
3. Press **[Add to Project]** and select "**Notebook**"
4. In the New notebook page, select "**From URL**" and set the following values:  
Notebook URL: https://github.com/jruponen/AIOS-keras-WML-model/raw/master/Sample%20WML-Keras%20for%20AIOS%20v2%20(published).ipynb  
Select runtime: Default Spark Python 3.5 XS  
Name: Sample-Keras-WML-AIOS  
5. Press **[Create Notebook]**  

Follow instructions on the Notebook.  


## NOTE: THESE NOTEBOOKS ARE STILL WORK IN PROGRESS.  
Use v2 Notebook for end-to-end sample scenario.  
