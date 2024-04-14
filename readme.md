## Objective of this project is to download a small huggingface model and load the same on local windows machine.
## In my case my windows laptop is having 16 GB ram and intel i5 processor

## make sure you have python installed on your machine 
## Install required packages using the requirements.txt
## command for the same is:
    pip install -r requirements.txt
## next step is to download the model by cloning required repo from huggingface
## command for the same : refer : https://huggingface.co/TinyLlama/TinyLlama-1.1B-Chat-v1.0/tree/main?clone=true
    git lfs install
    git clone https://huggingface.co/TinyLlama/TinyLlama-1.1B-Chat-v1.0

## Once cloning is complete update the demo.ipynb, model_name_path variable to refer the model folder
## execute the notebook interactively.


