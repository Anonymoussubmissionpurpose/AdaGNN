# AdaGNN
Open-source code for ''Graph Neural Networks withAdaptive Frequency Response Filter''.

## Environment
Experiments are carried out on a Titan RTX with Cuda 10.1.

## usage
Default parameter settings are an 8-layered AdaGNN-S model.
Use as
```
python main.py
```
Pre-trained models can be found in 

```
python main.py --data cora --model SGC --nlayer 40 --missing_rate 100 --norm_mode PN --norm_scale 10
```
