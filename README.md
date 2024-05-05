
# My Paper Title

This repository is the official implementation of [Learning the Graphical Structure of Electronic
Health Records with Graph Convolutional Transformer](https://arxiv.org/abs/1906.04716). 

## Requirements

To install requirements:

```setup
pip install -r requirements.txt
```

By installing the requirements.txt you will have a virtualenv called venv_gnn that has Python 2.7 and the compatible scikitlearn & tensorflow.

Follow the information in Project.ipynb to gain access to the data.

## Training

To train the model(s) in the paper, run this command:

```train
python train.py --input-data <path_to_data> --alpha 10 --beta 20
```

For more details on how the training of the model works, please reference Project.ipynb

## Evaluation

To evaluate my model, run:

```eval
python train.py <path to TFRecords> <output path>
```

More details on evaluation can be found in Project.ipynb

## Results

More details on results can be found in Project.ipynb

## References

Learning the Graphical Structure of Electronic Health Records with Graph Convolutional Transformer
Edward Choi, Zhen Xu, Yujia Li, Michael W. Dusenberry, Gerardo Flores, Yuan Xue, Andrew M. Dai  
AAAI 2020
