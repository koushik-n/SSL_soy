# Plant Phenotyping with limited aan
This repository contains the code used to run the deep active learning experiments detailed in our paper "Plant Phenotyping with Limited Annotation: Doing More with Less"
## Dependencies
In order to run our code, you'll need these main packages:

- [Python>=3.5](https://www.python.org/)
- [solo-learn>=1.03](https://github.com/vturrisi/solo-learn)
- [Pytorch>=1.9](https://pytorch.org/)

## SSL pre-trained model weights and Soybean disease images 
[Images.zip]  
[Models_and_hyperparameters.zip](https://iastate.box.com/s/hxf20a31ucnr4drsum1f3qoe2p7g6ecr)

## Running the code
We use the SSL implementations and linear classification codes from [solo-learn](https://github.com/vturrisi/solo-learn) for this work. 
We modified the [pytorch vision references](https://github.com/pytorch/vision/tree/main/references/classification) codes for the end-to-end fine-tuning.
```
