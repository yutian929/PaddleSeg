# Gated-scnn: Gated shape cnns for semantic segmentation

## Reference

> Takikawa, Towaki, David Acuna, Varun Jampani, and Sanja Fidler. "Gated-scnn: Gated shape cnns for semantic segmentation." In Proceedings of the IEEE International Conference on Computer Vision, pp. 5229-5238. 2019.

## Performance

### Cityscapes

| Model | Backbone | Resolution | Training Iters | mIoU | mIoU (flip) | mIoU (ms+flip) | Links |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|GSCNN|ResNet50_OS8|1024x512|80000|80.67%|80.88%|81.42%|[model](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/gscnn_resnet50_os8_cityscapes_1024x512_80k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/gscnn_resnet50_os8_cityscapes_1024x512_80k/train.log) |
