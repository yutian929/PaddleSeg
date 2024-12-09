# GCNet: Non-local networks meet squeeze-excitation networks and beyond

## Reference

> Cao, Yue, Jiarui Xu, Stephen Lin, Fangyun Wei, and Han Hu. "GCNet: Non-local networks meet squeeze-excitation networks and beyond." In Proceedings of the IEEE International Conference on Computer Vision Workshops, pp. 0-0. 2019.

## Performance

### Cityscapes

| Model | Backbone | Resolution | Training Iters | mIoU | mIoU (flip) | mIoU (ms+flip) | Links |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|GCNet|ResNet50_OS8|1024x512|80000|79.50%|79.77%|80.16%|[model](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/gcnet_resnet50_os8_cityscapes_1024x512_80k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/gcnet_resnet50_os8_cityscapes_1024x512_80k/train.log) |
|GCNet|ResNet101_OS8|1024x512|80000|81.01%|81.30%|81.85%|[model](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/gcnet_resnet101_os8_cityscapes_1024x512_80k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/gcnet_resnet101_os8_cityscapes_1024x512_80k/train.log) |

### Pascal VOC 2012 + Aug

| Model | Backbone | Resolution | Training Iters | mIoU | mIoU (flip) | mIoU (ms+flip) | Links |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|GCNet|ResNet50_OS8|512x512|40000|80.32%|80.39%|80.94%|[model](https://bj.bcebos.com/paddleseg/dygraph/pascal_voc12/gcnet_resnet50_os8_voc12aug_512x512_40k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/pascal_voc12/gcnet_resnet50_os8_voc12aug_512x512_40k/train.log) |
|GCNet|ResNet101_OS8|512x512|40000|79.64%|79.59%|80.25%|[model](https://bj.bcebos.com/paddleseg/dygraph/pascal_voc12/gcnet_resnet101_os8_voc12aug_512x512_40k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/pascal_voc12/gcnet_resnet101_os8_voc12aug_512x512_40k/train.log) |
