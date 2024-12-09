# Semantic Flow for Fast and Accurate Scene Parsing

## Reference

> Xiangtai Li, Ansheng You, Zhen Zhu, Houlong Zhao, Maoke Yang, Kuiyuan Yang, Shaohua Tan, Yunhai Tong:
Semantic Flow for Fast and Accurate Scene Parsing. ECCV (1) 2020: 775-793 .

## Performance

### Cityscapes

| Model | Backbone | Resolution | Training Iters | mIoU | mIoU (flip) | mIoU (ms+flip) | Links |
|-|-|-|-|-|-|-|-|
|SFNet|ResNet18_OS8|1024x1024|80000|78.72%|79.11%|79.49%|[model](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/sfnet_resnet18_os8_cityscapes_1024x1024_80k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/sfnet_resnet18_os8_cityscapes_1024x1024_80k/train.log) |
|SFNet|ResNet50_OS8|1024x1024|80000|81.49%|81.63%|82.10%|[model](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/sfnet_resnet50_os8_cityscapes_1024x1024_80k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/sfnet_resnet50_os8_cityscapes_1024x1024_80k/train.log) |
