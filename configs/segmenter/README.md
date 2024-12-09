# Segmenter: Transformer for Semantic Segmentation

## Reference

> Strudel, Robin, Ricardo Garcia, Ivan Laptev, and Cordelia Schmid. "Segmenter: Transformer for Semantic Segmentation." In Proceedings of the IEEE International Conference on Computer Vision, pp. 7262-7272. 2021.

## Performance

### ADE20k

| Model | Backbone | Head | Patch Size | Resolution | Training Iters | mIoU (slice) | mIoU (flip)  | Links |
| :-:   | :-:      | :-:  | :-:        | :-:        | :-:            | :-:          | :-:          | :-:  |
| Segmenter | ViT small | Linear  | 16 | 512*512 | 160000 | 45.48 | 45.69 | [model](https://paddleseg.bj.bcebos.com/dygraph/ade20k/segmenter_vit_small_linear_ade20k_512x512_160k/model.pdparams) \| [log](https://paddleseg.bj.bcebos.com/dygraph/ade20k/segmenter_vit_small_linear_ade20k_512x512_160k/train.log) |
| Segmenter | ViT small | Mask    | 16 | 512*512 | 160000 | 45.15 | 45.41 |  [model](https://paddleseg.bj.bcebos.com/dygraph/ade20k/segmenter_vit_small_mask_ade20k_512x512_160k/model.pdparams) \| [log](https://paddleseg.bj.bcebos.com/dygraph/ade20k/segmenter_vit_small_mask_ade20k_512x512_160k/train.log) |
| Segmenter | ViT base  | Linear  | 16 | 512*512 | 160000 | 48.13 | 48.31 |  [model](https://paddleseg.bj.bcebos.com/dygraph/ade20k/segmenter_vit_base_linear_ade20k_512x512_160k/model.pdparams) \| [log](https://paddleseg.bj.bcebos.com/dygraph/ade20k/segmenter_vit_base_linear_ade20k_512x512_160k/train.log) |
| Segmenter | ViT base  | Mask    | 16 | 512*512 | 160000 | 48.49 | 48.61 |  [model](https://paddleseg.bj.bcebos.com/dygraph/ade20k/segmenter_vit_base_mask_ade20k_512x512_160k/model.pdparams) \| [log](https://paddleseg.bj.bcebos.com/dygraph/ade20k/segmenter_vit_base_mask_ade20k_512x512_160k/train.log) |
