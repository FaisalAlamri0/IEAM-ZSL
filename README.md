# Low_Short_Learning


 Implicit and Explicit Attention For Zero-Shot Learning 


Explicit +  Implicit Attention
As provided in [Explicit and Implicit_Attention](Explicit_Implicit_Attention):
Explicit +  Implicit Attention as depicted below is implmeneted using: <br />
i) ResNet101 as in [Resnet101_Explicit+ImplicitAttention](Explicit_Implicit_Attention/Explicit_AND_Implicit_Attention--ResNet101.ipynb)<br />
ii) ViT as in [ViT_Explicit+ImplicitAttention](Explicit_Implicit_Attention/Explicit_AND_Implicit_Attention--ViT.ipynb)

![](figs/Explicit_Implicit__Attention.jpg)



## Usage:
#### 1) Download the datasets
Follow the instructions provided in [data/Dataset_Instruction.txt](data/Datasets_Instruction.txt)


#### 2) Create a conda environment:
Refer to: [Conda Environment](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) for more information. 
```
# conda create -n {ENVNAME} python=3.6
conda create -n ViT_ZSL python=3.6

# Activate the environment: conda activate {ENVNAME}
conda activate ViT_ZSL
```
#### 3) Required libraries :
This is a [PyTorch](https://pytorch.org/get-started/locally/) implementation
```
pip install -r requirements.txt 

# PyTorch
conda install pytorch torchvision torchaudio cudatoolkit=11.1 -c pytorch -c nvidia
```
#### 4) Train (and test) the model
open jupyter notebook(s) provided in [Explicit_Attention](Explicit_Attention), and [Explicit and Implicit_Attention](Explicit_Implicit_Attention)
```
jupyter notebook {NAME-of-jupyter notebook}.ipynb
```


## External sources:

- [Timm](https://pypi.org/project/timm/)
- [Transformer](https://github.com/huggingface/transformers)
- [ViT](https://github.com/google-research/vision_transformer)
- [Vision_Transformer_Tutorial](https://colab.research.google.com/github/hirotomusiker/schwert_colab_data_storage/blob/master/notebook/Vision_Transformer_Tutorial.ipynb#scrollTo=3f7gQ89cvAnv)

