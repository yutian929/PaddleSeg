# U-Net: Convolutional Networks for Biomedical Image Segmentation

## Reference
> Ronneberger O, Fischer P, Brox T. U-net: Convolutional networks for biomedical image segmentation[C]//International Conference on Medical image computing and computer-assisted intervention. Springer, Cham, 2015: 234-241.

## Performance

### Cityscapes

| Model | Backbone | Resolution | Training Iters | Batch Size | mIoU | mIoU (flip) | mIoU (ms+flip) | Links |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|UNet|-|1024x512|160000|4|65.00%|66.02%|67.29%|[model](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/unet_cityscapes_1024x512_160k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/unet_cityscapes_1024x512_160k/train.log) |

### STARE
| Model | Backbone | Resolution | Training Iters | Batch Size | AUC ROC | DICE | mIoU | Links |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|UNet|-|128x128|40000|16|95.93%|90.43%|83.54%|[model](https://bj.bcebos.com/paddleseg/dygraph/stare/unet_stare_128x128_40k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/stare/unet_stare_128x128_40k/train.log) |

### DRIVE
| Model | Backbone | Resolution | Training Iters | Batch Size | AUC ROC | DICE | mIoU | Links |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|UNet|-|128x128|40000|16|95.58%|89.50%|82.12%|[model](https://bj.bcebos.com/paddleseg/dygraph/drive/unet_drive_128x128_40k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/drive/unet_drive_128x128_40k/train.log) |

### CHASE DB1
| Model | Backbone | Resolution | Training Iters | Batch Size | AUC ROC | DICE | mIoU | Links |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|UNet|-|128x128|40000|16|95.69%|88.54%|80.87%|[model](https://bj.bcebos.com/paddleseg/dygraph/chasedb1/unet_chasedb1_128x128_40k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/chasedb1/unet_chasedb1_128x128_40k/train.log) |

### HRF

| Model | Backbone | Resolution | Training Iters | Batch Size | AUC ROC | DICE | mIoU | Links |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|UNet|-|256x256|40000|16|93.39%|86.83%|78.45%|[model](https://bj.bcebos.com/paddleseg/dygraph/hrf/unet_hrf_256x256_40k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/hrf/unet_hrf_256x256_40k/train.log) |
