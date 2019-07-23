# Pytorch Golden Template

## Class Diagram
<img src='./doc/PytorchTemplate-initialDesgin.png'>

## Features

## Usage

Example: train a new model
```
python main.py -tc configs/template.json -sc configs/loss/cross_entropy.json
```

Example: resume from a checkpoint, inference and save outputs
```
python main.py --resume ./saved/ckpts/template_config+CrossEntropy/0723_180600/ckpt-ep1-valid_mnist_avg_loss0.2885-best.pth --mode test
```

## Folder Structure

## Authors
* Ya-Liang Chang (Allen) [amjltc295](https://github.com/amjltc295)
* Zhe Yu Liu [Nash2325138](https://github.com/Nash2325138)

