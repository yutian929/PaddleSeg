# Pyramid Scene Parsing Network

## Reference

> Zhao, Hengshuang, Jianping Shi, Xiaojuan Qi, Xiaogang Wang, and Jiaya Jia. "Pyramid scene parsing network." In Proceedings of the IEEE conference on computer vision and pattern recognition, pp. 2881-2890. 2017.

## Performance

### Cityscapes

| Model | Backbone | Resolution | Training Iters | mIoU | mIoU (flip) | mIoU (ms+flip) | Links |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|PSPNet|ResNet50_OS8|1024x512|80000|78.83%|79.03%|79.66%|[model](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/pspnet_resnet50_os8_cityscapes_1024x512_80k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/pspnet_resnet50_os8_cityscapes_1024x512_80k/train.log) |
|PSPNet|ResNet101_OS8|1024x512|80000|80.48%|80.74%|81.29%|[model](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/pspnet_resnet101_os8_cityscapes_1024x512_80k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/pspnet_resnet101_os8_cityscapes_1024x512_80k/train.log) |

### Pascal VOC 2012 + Aug

| Model | Backbone | Resolution | Training Iters | mIoU | mIoU (flip) | mIoU (ms+flip) | Links |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|PSPNet|ResNet50_OS8|512x512|40000|80.76%|80.92%|81.18%|[model](https://bj.bcebos.com/paddleseg/dygraph/pascal_voc12/pspnet_resnet50_os8_voc12aug_512x512_40k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/pascal_voc12/pspnet_resnet50_os8_voc12aug_512x512_40k/train.log)|
|PSPNet|ResNet101_OS8|512x512|40000|80.22%|80.48%|80.68%|[model](https://bj.bcebos.com/paddleseg/dygraph/pascal_voc12/pspnet_resnet101_os8_voc12aug_512x512_40k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/pascal_voc12/pspnet_resnet101_os8_voc12aug_512x512_40k/train.log)|
