# Expectation-Maximization Attention Networks for Semantic Segmentation

## Reference

> Xia Li, Zhisheng Zhong, Jianlong Wu, Yibo Yang, Zhouchen Lin, Hong Liu:
Expectation-Maximization Attention Networks for Semantic Segmentation. ICCV 2019: 9166-9175.

## Performance

### Cityscapes

| Model | Backbone | Resolution | Training Iters | mIoU | mIoU (flip) | mIoU (ms+flip) |Links |
|-|-|-|-|-|-|-|-|
|EMANet|ResNet50_OS8|1024x512|80000|79.05%|79.34%|80.82%|[model](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/emanet_resnet50_os8_cityscapes_1024x512_80k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/emanet_resnet50_os8_cityscapes_1024x512_80k/train.log) |
|EMANet|ResNet101_OS8|1024x512|80000|80.00%|80.23%|80.76%|[model](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/emanet_resnet101_os8_cityscapes_1024x512_80k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/emanet_resnet101_os8_cityscapes_1024x512_80k/train.log) |

### Pascal VOC 2012 + Aug

| Model | Backbone | Resolution | Training Iters | mIoU | mIoU (flip) | mIoU (ms+flip) | Links |
|-|-|-|-|-|-|-|-|
|EMANet|ResNet50_OS8|512x512|40000|78.60%|78.90%|79.55%|[model](https://bj.bcebos.com/paddleseg/dygraph/pascal_voc12/emanet_resnet50_os8_voc12aug_512x512_40k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/pascal_voc12/emanet_resnet50_os8_voc12aug_512x512_40k/train.log) |
|EMANet|ResNet101_OS8|512x512|40000|79.47%|79.97%| 80.51%|[model](https://bj.bcebos.com/paddleseg/dygraph/pascal_voc12/emanet_resnet101_os8_voc12aug_512x512_40k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/pascal_voc12/emanet_resnet101_os8_voc12aug_512x512_40k/train.log) |
