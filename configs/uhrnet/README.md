# U-HRNet: Delving into Improving Semantic Representation of High Resolution Network for Dense Prediction

## Reference
> Jian Wang, Xiang Long, Guowei Chen, Zewu Wu, Zeyu Chen, Errui Ding et al. "U-HRNet: Delving into Improving Semantic Representation of High Resolution Network for Dense Prediction" arXiv preprint arXiv:2210.07140 (2022).

## Performance

### Cityscapes

| Model | Backbone | Resolution | Training Iters | mIoU | mIoU (flip) | mIoU (ms+flip) | Links |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|FCN|UHRNet_W18_small|1024x512|80000|77.66%|78.26%|78.79%|[model](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/fcn_uhrnetw18_small_cityscapes_1024x512_80k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/fcn_uhrnetw18_small_cityscapes_1024x512_80k/train.log) |
|FCN|UHRNet_W18_small|1024x512|120000|78.39%|79.09%|79.35%|[model](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/fcn_uhrnetw18_small_cityscapes_1024x512_120k_bs3/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/fcn_uhrnetw18_small_cityscapes_1024x512_120k_bs3/train.log)|
|FCN|UHRNet_W48|1024x512|80000|81.28%|81.76%|81.91%|[model](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/fcn_uhrnetw48_cityscapes_1024x512_80k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/fcn_uhrnetw48_cityscapes_1024x512_80k/train.log) |
|FCN|UHRNet_W48|1024x512|120000|81.91%|82.39%|82.71%|[model](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/fcn_uhrnetw48_cityscapes_1024x512_120k_bs3/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/fcn_uhrnetw48_cityscapes_1024x512_120k_bs3/train.log) |
