# README for running the code

For running any of the notebooks present in this repo one must first download the specific model. This was done this way since the zip file became too large when including all the models files. The models used where downloaded by running the code in a cell block.

## **QWEN2.5-instruct**
import kagglehub
path = kagglehub.model_download("qwen-lm/qwen2.5/transformers/0.5b-instruct")

print("Path to model files:", path)

## **QWEN3-transformer**
import kagglehub
path = kagglehub.model_download("qwen-lm/qwen-3-embedding/transformers/0.6b")

print("Path to model files:", path)

### *The printed path to model was then used to navigate to model folder. This path line can be modified to place the model where one chooses.*


