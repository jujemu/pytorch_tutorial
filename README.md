2022 7 26 ~

# Pytorch
## Quick Start
___Model classifying FashionMNIST___  
_overall modeling tutorial_  

In pytorch, we should get data into 'device', 'cuda' or 'cpu', using method '.to()'  
And define model, subclass of nn.Module, also override mothod of __init__, forward.  
It might be tough, picky.  
At now, I dont know why pytorch is getting main stream, not tensorflow.  

### For more Details

_https://velog.io/@jujemu/Getting-Started-with-Pytotorch_  
_https://colab.research.google.com/github/pytorch/tutorials/blob/gh-pages/_downloads/af0caf6d7af0dda755f4c9d7af9ccc2c/quickstart_tutorial.ipynb_   

## ResNet
_Transfer keras to pytorch_  

 - dataset : kaggle, cats_vs_dogs  
 - model : resnet 50 layers

 This task is very tough for me, especially loading dataset.  
 
 Issue in loading dataset is
  - tensorflow dataset doesnt have __getitem__, so I cant access from index
  - for kaggle dataset, I dont know why my model is so slow. I believe, the reason is location of dataset, google drive

