# SegFormer: Simple and Efficient Design for Semantic Segmentation with Transformers

## Reference

> Xie, Enze, Wenhai Wang, Zhiding Yu, Anima Anandkumar, Jose M. Alvarez, and Ping Luo. "SegFormer: Simple and Efficient Design for Semantic Segmentation with Transformers." arXiv preprint arXiv:2105.15203 (2021).

## Performance

### Cityscapes

| Model | Backbone | Resolution | Training Iters | mIoU(slice) | mIoU (flip) | mIoU (ms+flip) | Links |
|-|-|-|-|-|-|-|-|
|SegFormer_B0|-|1024x1024|160000|76.73%|77.16%|-|[model](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/segformer_b0_cityscapes_1024x1024_160k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/segformer_b0_cityscapes_1024x1024_160k/train.log) |
|SegFormer_B1|-|1024x1024|160000|78.35%|78.64%|-|[model](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/segformer_b1_cityscapes_1024x1024_160k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/segformer_b1_cityscapes_1024x1024_160k/train.log) |
|SegFormer_B2|-|1024x1024|160000|81.60%|81.82%|-|[model](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/segformer_b2_cityscapes_1024x1024_160k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/segformer_b2_cityscapes_1024x1024_160k/train.log) |
|SegFormer_B3|-|1024x1024|160000|82.47%|82.60%|-|[model](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/segformer_b3_cityscapes_1024x1024_160k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/segformer_b3_cityscapes_1024x1024_160k/train.log) |
|SegFormer_B4|-|1024x1024|160000|82.38%|82.59%|-|[model](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/segformer_b4_cityscapes_1024x1024_160k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/segformer_b4_cityscapes_1024x1024_160k/train.log) |
|SegFormer_B5|-|1024x1024|160000|82.58%|82.82%|-|[model](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/segformer_b5_cityscapes_1024x1024_160k/model.pdparams) \| [log](https://bj.bcebos.com/paddleseg/dygraph/cityscapes/segformer_b5_cityscapes_1024x1024_160k/train.log) |
