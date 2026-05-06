## UncertainGen

### Setting up the pyhon environment
You can install all the required packages by running the following commands:
```
conda create -n ENVIRONMENTAL_NAME python=3.9
conda activate ENVIRONMENTAL_NAME
pip install -r requirements.txt
```

### Datasets
We first need the ```gdown``` package to get the data. 
```
pip install gdown
```

Then, please run the following commands to download the training dataset:
```
gdown 1p59ch_MO-9DXh3LUIvorllPJGLEAwsUp
unzip dnabert-s_train.zip
```
and the evaluation datasets can be retrieved similarly.
```
gdown 1I44T2alXrtXPZrhkuca6QP3tFHxDW98c
unzip dnabert-s_eval.zip
```

### Training and Evaluation
For training and evaluation of the model, the bash scripts sh/train_model.sh and sh/evaluate.sh can be used.