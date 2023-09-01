# GReaT

## Requirements

* chainercv
* cityscapesscripts
* pillow
* pandas
* opencv-python
* torch
* timm
* mmcv-full
* torchvision
* cython
* numpy
* scipy
* tqdm
* argparse

## Usage

**Download dataset**

- Cityscapes

- ADE20K

**To train the model**

```
bash scripts/distrain.sh 4 ssseg/configs/GReaT/GReaT_resnet50os16_ade20k.py
```

**To test the model**

bash scripts/distest.sh 4 ssseg/configs/GReaT/GReaT_resnet50os16_ade20k.py GReaT_resnet50os16_ade20k/200.pth