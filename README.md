# `Rectified Max Pooling implementation in Keras`

## Paper 
Please cite our papers if you find it useful for your research.


## Installation
* Install `Keras 2.2.4`, `tensorflow 1.12.0`, `scipy`, `numpy` and `opencv3`.
* Or use our prepared gpu env `env.yaml`
```
conda env create -f env.yaml
```
* Clone this repo.
```
git clone https://github.com/snowzm/Rectified-Max-Pooling
```

## Notice
* The corresponding codes will be uploaded after the publication of our paper.
* If you have any question, email to me (mengxue_zhang@outlook.com).

## Usage
* Firstly, Run `generate_samples.py` to generate the meta data.
* Then, Run `main.py` (default as SOC).
* Tip: RMPNets model is implemented in `model.py`.


## Result
* About approximate 100 Epoch, you will see the similar results like the following.
[==============================] - 3s 123ms/step - loss: 0.0057 - acc: 0.9989 - val_loss: 0.0161 - val_acc: 0.9969
* Other experimental scripts also can be found in the `main.py`.
