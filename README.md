# RGBD-semantic-segmentation
A paper list of RGBD semantic segmentation.

cityscape
|           Method           |   IoU cla.  |   iIoU cla. |  IoU cat.  |  iIoU cat.  | Input |    Ref. from    |  Published  | Year |     mIoU    |   pixel Acc  |
| :------------------------: | :---------: | :---------: | :--------: | :---------: | :---: | :-------------: | :---------: | ---- |   :------:  |   :------:   |
|          **POR**           |    59.1     |    28.4     |    29.1    |             | RGBD  |                 |    CVPR     | 2013 |
|       **RGBD R-CNN**       |    60.3     |    35.1     |    31.3    |47(in LSD-GF)| RGBD  |                 |    ECCV     | 2014 |
|       **DeconvNet**        |    69.9     |    56.4     |    42.7    |        56   |  RGB  |   **LSD-GF**    |    ICCV     | 2015 |
|        **DeepLab**         |    68.7     |    46.9     |    36.8    |       52.5  | RGBD  |    **STD2P**    |    ICLR     | 2015 |
|        **CRF-RNN**         |    66.3     |    48.9     |    35.4    |        51   | RGBD  |    **STD2P**    |    ICCV     | 2015 |
|    **Multi-Scale  CNN**    |    65.6     |    45.1     |    34.1    |       51.4  |  RGB  | **LCSF-Deconv** |    ICCV     | 2015 |
|          **FCN**           |    65.4     |    46.1     |     34     |       49.5  | RGBD  | **LCSF-Deconv** |    CVPR     | 2015 |
|   **Mutex  Constraints**   |    63.8     |    31.5     |            | 48.5        | RGBD |                 |    ICCV     | 2015 |
|          **E2S2**          |    58.1     |    52.9     |     31     |       44.2  | RGBD  |    **STD2P**    |    ECCV     | 2016 |
|        **BI-3000**         |    58.9     |    39.3     |    27.7    |        43   | RGBD  |    **STD2P**    |    ECCV     | 2016 |
|        **BI-1000**         |    57.7     |    37.8     |    27.1    |       41.9  | RGBD  |    **STD2P**    |    ECCV     | 2016 |
|      **LCSF-Deconv**       |             |    47.3     |            |             | RGBD  |                 |    ECCV     | 2016 |
|        **LSTM-CF**         |             |    49.4     |            |             | RGBD  |                 |    ECCV     | 2016 |
|      **CRF+RF+RFS**        |    73.8     |             |            |             | RGBD  |                 |    IEEE     | 2020 |
|      **Malleable 2.5D**    |             |             |            |             | RGBD  |                 |    CVPR     | 2020 |  80.81（kernels=3）|     96.51     |
|        **SANet**           |     80.9    |    59.6     |    91.4    |     80.2    | RGBD  |                 |    CVPR     | 2020 |   :------:  |   :------:   |
|       **SOSD-Net**         |             |             |            |             | RGBD  |                 |    CVPR     | 2021 |     68.2    |   :------:   |

scanet
