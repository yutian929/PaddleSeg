# Encoder-Decoder with Atrous Separable Convolution for Semantic Image Segmentation

## Reference

> Chen, Liang-Chieh, Yukun Zhu, George Papandreou, Florian Schroff, and Hartwig Adam. "Encoder-decoder with atrous separable convolution for semantic image segmentation." In Proceedings of the European conference on computer vision (ECCV), pp. 801-818. 2018.

## Performance

### Cityscapes

| Model | Backbone | Resolution | Training Iters | mIoU | mIoU (flip) | mIoU (ms+flip) | Links |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|DeepLabV3P|ResNet50_OS8|1024x512|80000|80.36%|80.57%|81.33%|[model](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/deeplabv3p_resnet50_os8_cityscapes_1024x512_80k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/deeplabv3p_resnet50_os8_cityscapes_1024x512_80k/train.log) |
|DeepLabV3P*|ResNet50_OS8|1024x512|80000|81.18%| 81.42% | 82.00% |[model](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/deeplabv3p_resnet50_os8_cityscapes_1024x512_80k_rmiloss/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/deeplabv3p_resnet50_os8_cityscapes_1024x512_80k_rmiloss/train.log) |
|DeepLabV3P|ResNet101_OS8|1024x512|80000|81.10%|81.38%|81.76%|[model](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/deeplabv3p_resnet101_os8_cityscapes_1024x512_80k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/deeplabv3p_resnet101_os8_cityscapes_1024x512_80k/train.log) |
|DeepLabV3P|ResNet101_OS8|769x769|80000|81.53%|81.88%|82.32%|[model](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/deeplabv3p_resnet101_os8_cityscapes_769x769_80k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/deeplabv3p_resnet101_os8_cityscapes_769x769_80k/train.log) |

DeepLabV3P* is DeepLabV3P with [RMI Loss](https://arxiv.org/abs/1910.12037), which requires paddlepaddle=2.2.

### Pascal VOC 2012 + Aug

| Model | Backbone | Resolution | Training Iters | mIoU | mIoU (flip) | mIoU (ms+flip) | Links |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|DeepLabV3P|ResNet50_OS8|512x512|40000|80.66%|81.33%|81.93%|[model](https://bj.bcebos.com/paddleseg/dygraph/pascal_voc12/deeplabv3p_resnet50_os8_voc12aug_512x512_40k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/pascal_voc12/deeplabv3p_resnet50_os8_voc12aug_512x512_40k/train.log) |
|DeepLabV3P|ResNet101_OS8|512x512|40000|80.60%|80.77%|81.22%|[model](https://bj.bcebos.com/paddleseg/dygraph/pascal_voc12/deeplabv3p_resnet101_os8_voc12aug_512x512_40k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/pascal_voc12/deeplabv3p_resnet101_os8_voc12aug_512x512_40k/train.log) |
