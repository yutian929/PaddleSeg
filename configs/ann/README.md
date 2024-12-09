# Asymmetric Non-local Neural Networks for Semantic Segmentation

## Reference

> Zhu, Zhen, Mengde Xu, Song Bai, Tengteng Huang, and Xiang Bai. "Asymmetric non-local neural networks for semantic segmentation." In Proceedings of the IEEE International Conference on Computer Vision, pp. 593-602. 2019.

## Performance

### Cityscapes

| Model | Backbone | Resolution | Training Iters | mIoU | mIoU (flip) | mIoU (ms+flip) | Links |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|ANN|ResNet50_OS8|1024x512|80000|79.09%|79.31%|79.90%|[model](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/ann_resnet50_os8_cityscapes_1024x512_80k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/ann_resnet50_os8_cityscapes_1024x512_80k/train.log)  |
|ANN|ResNet101_OS8|1024x512|80000|80.61%|80.98%|81.50%|[model](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/ann_resnet101_os8_cityscapes_1024x512_80k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/ann_resnet101_os8_cityscapes_1024x512_80k/train.log) |

### Pascal VOC 2012 + Aug

| Model | Backbone | Resolution | Training Iters | mIoU | mIoU (flip) | mIoU (ms+flip) | Links |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|ANN|ResNet50_OS8|512x512|40000|80.82%|81.10%|81.67%|[model](https://bj.bcebos.com/paddleseg/dygraph/pascal_voc12/ann_resnet50_os8_voc12aug_512x512_40k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/pascal_voc12/ann_resnet50_os8_voc12aug_512x512_40k/train.log) |
|ANN|ResNet101_OS8|512x512|40000|79.62%|79.84%|80.33%|[model](https://bj.bcebos.com/paddleseg/dygraph/pascal_voc12/ann_resnet101_os8_voc12aug_512x512_40k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/pascal_voc12/ann_resnet101_os8_voc12aug_512x512_40k/train.log) |
