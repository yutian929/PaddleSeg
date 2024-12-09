# GINet: Graph Interaction Network for Scene Parsing

## Reference

> Wu, Tianyi, Yu Lu, Yu Zhu, Chuang Zhang, Ming Wu, Zhanyu Ma, and Guodong Guo. "GINet: Graph interaction network for scene parsing." In European Conference on Computer Vision, pp. 34-51. Springer, Cham, 2020.


## Performance

### Cityscapes

| Model | Backbone | Resolution | Training Iters | mIoU | mIoU (flip) | mIoU (ms+flip) | Links |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|GINet|ResNet50_OS8|1024x512|80000|78.66%|79.07%|79.61%|[model](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/ginet_resnet50_os8_cityscapes_1024x512_80k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/ginet_resnet50_os8_cityscapes_1024x512_80k/train.log) |
|GINet|ResNet101_OS8|1024x512|80000|78.4%|78.72%|79.26%|[model](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/ginet_resnet101_os8_cityscapes_1024x512_80k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/ginet_resnet101_os8_cityscapes_1024x512_80k/train.log) |

### Pascal VOC 2012 + Aug

| Model | Backbone | Resolution | Training Iters | mIoU | mIoU (flip) | mIoU (ms+flip) | Links |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|GINet|ResNet50_OS8|512x512|40000|81.97%|82.02%|82.34%|[model](https://bj.bcebos.com/paddleseg/dygraph/pascal_voc12/ginet_resnet50_os8_voc12aug_512x512_40k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/pascal_voc12/ginet_resnet50_os8_voc12aug_512x512_40k/train.log) |
|GINet|ResNet101_OS8|512x512|40000|79.79%|79.99%|80.66%|[model](https://bj.bcebos.com/paddleseg/dygraph/pascal_voc12/ginet_resnet101_os8_voc12aug_512x512_40k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/pascal_voc12/ginet_resnet101_os8_voc12aug_512x512_40k/train.log) |

### ADE20K

| Model | Backbone | Resolution | Training Iters | mIoU | mIoU (flip) | mIoU (ms+flip) | Links |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|GINet|ResNet50_OS8|520x520|150000|43.45%|43.98%|44.42%|[model](https://paddleseg.bj.bcebos.com/dygraph/ade20k/ginet_resnet50_os8_ade20k_520x520_150k/model.pdparams) \| [log](https://paddleseg.bj.bcebos.com/dygraph/ade20k/ginet_resnet50_os8_ade20k_520x520_150k/train.log) |
|GINet|ResNet101_OS8|520x520|150000|45.79%|45.94%|46.56%|[model](https://paddleseg.bj.bcebos.com/dygraph/ade20k/ginet_resnet101_os8_ade20k_520x520_150k/model.pdparams) \| [log](https://paddleseg.bj.bcebos.com/dygraph/ade20k/ginet_resnet101_os8_ade20k_520x520_150k/train.log) |
