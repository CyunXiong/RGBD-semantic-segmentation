# RGBD-semantic-segmentation
A paper list of RGBD semantic segmentation.


## Metrics
The papers related to metrics used mainly in RGBD semantic segmentation are as follows.

- **[IoU cla.]** intersection over union class
- **[iIoU cla.]** instance intersection over union class
- **[IoU cat.]** intersection over union class
- **[IoU cat.]** intersection over union category
- **[iIoU cat.]** instance intersection over union category
- **[mIoU]** Mean intersection over union
- **[PixAcc]**  Pixel  accuracy
- **[AP]**  Average Precision 
- **[P]** group of depth privileged segmentation methods
- **[avg]** mAP@0.5--mean Average Precision

## Cityscape
|              Method           | IoU cla. | iIoU cla. | IoU cat. | iIoU cat. | Input |   Ref. from   | Published | Year |         mIoU         | pixel Acc|  AP | AP[val]| FPS |
| :---------------------------: | :------: | :-------: | :------: | :-------: | :---: | :-----------: | :-------: | :--: | :------------------: |  :-----: |:---:|:-----: |:--: |
|      **loop2 (test-aug)**     |          |           |          |           |  RGB  |     **RSP***  |    CVPR   | 2018 |       78.2[IoU]      |          |     |        |     |
|      **PAD-Net-ResNet101**    |   80.3   |   58.8    |   90.8   |     78.5  |  RGB  |               |    CVPR   | 2018 |                      |          |     |        |     |
|      **RFBNet(ERFNetEnc)**    |          |           |          |           | RGBD  |               |  IEEE SPL | 2019 |72.0[Val]   69.7[Test]|          |     |        |     |
|      **RFBNet(AdapNet++)**    |          |           |          |           | RGBD  |               |  IEEE SPL | 2019 |76.2[Val]   74.8[Test]|          |     |        |     |
|         **AdapNet++**         |          |           |          |           | RGBD  |               |    IJCV   | 2019 |        80.80         |          |     |        |     |
|            **[P]-HPM**        |          |           |          |           |  RGB  |               |   IEEE TM | 2020 |      83.38[IoU]      |          |     |        |     |
|      **RefineNet-Res101**     |          |           |          |           |  RGB  |               |   TPAMI   | 2020 |      73.6[IoU]       |          |     |        |     |
|**ESANet-R18-NBt1D[1024x512]** |          |           |          |           |  RGB  |               |    ICRA   | 2020 |     71.48[Val]       |          |     |        |37.2 |
|**ESANet-R34-NBt1D[1024x512]** |          |           |          |           |  RGB  |               |    ICRA   | 2020 |72.70[Val] 72.87[Test]|          |     |        |32.3 |
|   **ESANet-R50[1024x512]**    |          |           |          |           |  RGB  |               |    ICRA   | 2020 |      73.88[Val]      |          |     |        |24.9 |
|**ESANet-R18-NBt1D[2048x1024]**|          |           |          |           | RGBD  |               |    ICRA   | 2020 |      77.95[Val]      |          |     |        | 9.8 |
|**ESANet-R34-NBt1D[2048x1024]**|          |           |          |           | RGBD  |               |    ICRA   | 2020 |78.47[Val] 77.56[Test]|          |     |        | 8.3 |
|   **ESANet-R50[2048x1024]**   |          |           |          |           | RGBD  |               |    ICRA   | 2020 |      79.23[Val]      |          |     |        | 6.5 |
|**ESANet-R18-NBt1D[1024x512]** |          |           |          |           |  RGB  |               |    ICRA   | 2020 |      74.65[Val]      |          |     |        |28.9 |
|**ESANet-R34-NBt1D[1024x512]** |          |           |          |           |  RGB  |               |    ICRA   | 2020 |75.22[Val] 75.65[Test]|          |     |        |23.4 |
|  **ESANet-R50[1024x512]**     |          |           |          |           |  RGB  |               |    ICRA   | 2020 |      75.66[Val]      |          |     |        |16.9 |
|**ESANet-R18-NBt1D[2048x1024]**|          |           |          |           | RGBD  |               |    ICRA   | 2020 |      79.25[Val]      |          |     |        | 7.6 |
|**ESANet-R34-NBt1D[2048x1024]**|          |           |          |           | RGBD  |               |    ICRA   | 2020 |80.09[Val] 78.42[Test]|          |     |        | 6.2 |
|  **ESANet-R50[2048x1024]**    |          |           |          |           | RGBD  |               |    ICRA   | 2020 |      79.97[Val]      |          |     |        | 4.0 |
|          **RFNet**            |          |           |          |           | RGBD  |               |  IEEE RAL | 2020 |         72.5         |          |     |        |     |
|        **BCMFP+SA-Gate**      |          |           |          |           | RGBD  |               |    ECCV   | 2020 |         82.8         |          |     |        |     |
|           **VCD**             |          |           |          |           | RGBD  |               |    CVPR   | 2020 |         82.3         |          |     |        |     | 
|           **RRL**             |          |           |          |           | RGBD  |               |     TIP   | 2020 |                      |          | 29.7|  35.2  |     |
| **Malleable2.5D(kernels=1)**  |          |           |          |           | RGBD  |               |    CVPR   | 2020 |         80.26        |  96.40   |     |        |     |
| **Malleable2.5D(kernels=3)**  |          |           |          |           | RGBD  |               |    CVPR   | 2020 |         80.81        |  96.51   |     |        |     |
|            **SANet**          |   80.9   |   59.6    |   91.4   |    80.2   | RGBD  |               |    CVPR   | 2020 |                      |          |     |        |     |
|         **SOSD-Net**          |          |           |          |           | RGBD  |               |    CVPR   | 2021 |          68.2        |          |     |        |     |

## ScanNet
http://kaldir.vc.in.tum.de/scannet_benchmark/

## 2D-3D-S


##

## Paper list


- **[SANet]** Yu, L., et al. (2020). Multi-layer Feature Aggregation for Deep Scene Parsing Models. arXiv:2011.02572. [[Paper]](https://arxiv.org/pdf/arXiv:2011.02572.pdf) [Code]
- **[RRL]** Z. Xu, et al. (2020). Outdoor RGBD Instance Segmentation With Residual Regretting Learning. IEEE Transactions on Image Processing. [[Paper]](https://ieeexplore.ieee.org/document/9016374) [Code]
- **[RFNet]** L. Sun, K. Yang, et al. (2020). Real-Time Fusion Network for RGB-D Semantic Segmentation Incorporating Unexpected Obstacle Detection for Road-Driving Images. IEEE Robotics and Automation Letters.[[Paper]](https://arxiv.org/abs/2002.10570) [Code]

