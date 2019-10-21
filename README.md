# pytorch-fcn


PyTorch implementation of [Fully Convolutional Networks](https://github.com/shelhamer/fcn.berkeleyvision.org).


## Requirements

- [pytorch](https://github.com/pytorch/pytorch) >= 0.2.0
- [torchvision](https://github.com/pytorch/vision) >= 0.1.8
- [fcn](https://github.com/wkentaro/fcn) >= 6.1.5
- [Pillow](https://github.com/python-pillow/Pillow)
- [scipy](https://github.com/scipy/scipy)
- [tqdm](https://github.com/tqdm/tqdm)


## Installation

```bash
git clone https://github.com/LeaveYeah/pytorch-fcn
cd pytorch-fcn
pip install .
```
## Evaluation
```bash
cd examples/voc
python evaluate.py logs/20191020_221536.874003/fcn8s_model_best.pth.tar
```


