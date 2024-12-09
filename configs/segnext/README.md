# SegNeXt: Rethinking Convolutional Attention Design for Semantic Segmentation

## Reference
> Meng-Hao Guo, Cheng-Ze Lu, Qibin Hou, Zheng-Ning Liu, Ming-Ming Cheng and Shi-Min Hu. "SegNeXt: Rethinking Convolutional Attention Design for Semantic Segmentation" arXiv preprint arXiv:2207.13600 (2022).

## Performance

### Cityscapes

|  Model  | Backbone | Resolution | Training Iters |  mIoU  | mIoU (flip) | mIoU (ms+flip) |             Links               |
| :-----: | :------: | :--------: | :------------: | :----: | :---------: | :------------: | :-----------------------------: |
| SegNeXt | MSCAN_T  | 1024x1024  |     160000     | 81.04% |   81.20%    |     81.43%     | [model](https://paddleseg.bj.bcebos.com/dygraph/cityscapes/segnext_mscan_t_cityscapes_1024x1024_160k/model.pdparams) \|[log](https://paddleseg.bj.bcebos.com/dygraph/cityscapes/segnext_mscan_t_cityscapes_1024x1024_160k/train.log) |
| SegNeXt | MSCAN_S  | 1024x1024  |     160000     | 81.33% |   81.44%    |     81.47%     | [model](https://paddleseg.bj.bcebos.com/dygraph/cityscapes/segnext_mscan_s_cityscapes_1024x1024_160k/model.pdparams) \| [log](https://paddleseg.bj.bcebos.com/dygraph/cityscapes/segnext_mscan_s_cityscapes_1024x1024_160k/train.log) |
| SegNeXt | MSCAN_B  | 1024x1024  |     160000     | 82.74% |   82.84%    |     83.01%     | [model](https://paddleseg.bj.bcebos.com/dygraph/cityscapes/segnext_mscan_b_cityscapes_1024x1024_160k/model.pdparams) \| [log](https://paddleseg.bj.bcebos.com/dygraph/cityscapes/segnext_mscan_b_cityscapes_1024x1024_160k/train.log) |
| SegNeXt | MSCAN_L  | 1024x1024  |     160000     | 83.32% |   83.38%    |     83.60%     | [model](https://paddleseg.bj.bcebos.com/dygraph/cityscapes/segnext_mscan_l_cityscapes_1024x1024_160k/model.pdparams) \| [log](https://paddleseg.bj.bcebos.com/dygraph/cityscapes/segnext_mscan_l_cityscapes_1024x1024_160k/train.log) |

**Note**: In the current implementation, we found some potential issues that could cause training of SegNeXt with backbone MSCAN_T (denoted as SegNeXt-MSCAN_T) to crash when using the multi-card training setup from the original paper. As a work around, we did not use different settings of learning rate and weight decay for different layers. At the same time, we amplified the global learning rate by 10 times. With this setup, we obtained the above results of SegNeXt-MSCAN_T. 
