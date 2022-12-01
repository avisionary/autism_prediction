# autism_prediction
A Deep Learning Model To Predict Autism from Brain MRI Scans

## Objective Summary

Autism spectrum disorder (ASD) is a developmental disability caused by differences in the
brain. People with ASD have problems with social communication and interaction and
restricted behaviors or interests. In the current research, deep learning models are being
created to help solve the issue of predicting autism in people. In our project, we hope to do
the same – accurately predicting if a patient has autism by developing a deep neural
network model that trains on the patient’s brain MRI scans. However, our project differs
because we will use the midsagittal section of the MRI scans along the amygdala, the
orbitofrontal cortex, the cerebral cortex, and the insula sections of the brain. This
fundamental difference between our project to current research will help prepare a model
to predict autism more accurately from our selected sample data.


## Setup
Setting up the virtual environment will be the first and foremost task to do before running the scrappers. This will help in installing the required packages used in the python code. A [requirements](requirements.txt) file has been added in the root directory which includs all the dependencies that should be installed on the virtual environment. Failing to do so might result in errors in codes. Following is a way to create the virtual environment and install all requirements on it.

```console
$ python3.10 -m venv venv
$ source venv/bin/activate
$ pip install -r requirements.txt
```


