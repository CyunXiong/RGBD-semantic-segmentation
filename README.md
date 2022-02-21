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

Cityscape
|              Method           | IoU cla. | iIoU cla. | IoU cat. | iIoU cat. | Input |   Ref. from   | Published | Year |         mIoU         | pixel Acc|  AP | AP[val]| FPS |
| :---------------------------: | :------: | :-------: | :------: | :-------: | :---: | :-----------: | :-------: | :--: | :------------------: |  :-----: |:---:|:-----: |:--: |
|             **POR**           |   59.1   |   28.4    |   29.1   |           | RGBD  |               |    CVPR   | 2013 |                      |          |     |        |     |
|          **RGBD R-CNN**       |   60.3   |   35.1    |   31.3   |           | RGBD  |               |    ECCV   | 2014 |                      |          |     |        |     |
|          **DeconvNet**        |   69.9   |   56.4    |   42.7   |      56   |  RGB  |  **LSD-GF**   |    ICCV   | 2015 |                      |          |     |        |     |
|           **DeepLab**         |   68.7   |   46.9    |   36.8   |     52.5  | RGBD  |   **STD2P**   |    ICLR   | 2015 |
|           **CRF-RNN**         |   66.3   |   48.9    |   35.4   |      51   | RGBD  |   **STD2P**   |    ICCV   | 2015 |
|      **Multi-Scale  CNN**     |   65.6   |   45.1    |   34.1   |     51.4  |  RGB  |**LCSF-Deconv**|    ICCV   | 2015 |
|             **FCN**           |          |   46.1    |    34    |     49.5  | RGBD  |**LCSF-Deconv**|    CVPR   | 2015 |                      |          |     |        |     |
|      **RefineNet-Res101**     |          |           |          |           |  RGB  |               |   TPAMI   | 2020 |      73.6[IoU]       |          |     |        |     |
|**ESANeT-R18-NBt1D[1024x512]** |          |           |          |           |  RGB  |               |    ICRA   | 2020 |     71.48[Val]       |          |     |        |37.2 |
|**ESANeT-R34-NBt1D[1024x512]** |          |           |          |           |  RGB  |               |    ICRA   | 2020 |72.70[Val] 72.87[Test]|          |     |        |32.3 |
|   **ESANeT-R50[1024x512]**    |          |           |          |           |  RGB  |               |    ICRA   | 2020 |      73.88[Val]      |          |     |        |24.9 |
|**ESANeT-R18-NBt1D[2048x1024]**|          |           |          |           | RGBD  |               |    ICRA   | 2020 |      77.95[Val]      |          |     |        | 9.8 |
|**ESANeT-R34-NBt1D[2048x1024]**|          |           |          |           | RGBD  |               |    ICRA   | 2020 |78.47[Val] 77.56[Test]|          |     |        | 8.3 |
|   **ESANeT-R50[2048x1024]**   |          |           |          |           | RGBD  |               |    ICRA   | 2020 |      79.23[Val]      |          |     |        | 6.5 |
|**ESANeT-R18-NBt1D[1024x512]** |          |           |          |           |  RGB  |               |    ICRA   | 2020 |      74.65[Val]      |          |     |        |28.9 |
|**ESANeT-R34-NBt1D[1024x512]** |          |           |          |           |  RGB  |               |    ICRA   | 2020 |75.22[Val] 75.65[Test]|          |     |        |23.4 |
|  **ESANeT-R50[1024x512]**     |          |           |          |           |  RGB  |               |    ICRA   | 2020 |      75.66[Val]      |          |     |        |16.9 |
|**ESANeT-R18-NBt1D[2048x1024]**|          |           |          |           | RGBD  |               |    ICRA   | 2020 |      79.25[Val]      |          |     |        | 7.6 |
|**ESANeT-R34-NBt1D[2048x1024]**|          |           |          |           | RGBD  |               |    ICRA   | 2020 |80.09[Val] 78.42[Test]|          |     |        | 6.2 |
|  **ESANeT-R50[2048x1024]**    |          |           |          |           | RGBD  |               |    ICRA   | 2020 |      79.97[Val]      |          |     |        | 4.0 |
|          **RFNet**            |          |           |          |           | RGBD  |               |    IEEE   | 2020 |         72.5         |          |     |        |     |
|        **BCMFP+SA-Gate**      |          |           |          |           | RGBD  |               |    ECCV   | 2020 |         82.8         |          |     |        |     |
|           **VCD**             |          |           |          |           | RGBD  |               |    IEEE   | 2020 |         82.3         |          |     |        |     | 
|           **RRL**             |          |           |          |           | RGBD  |               |    IEEE   | 2020 |                      |          | 29.7|  35.2  |     |
| **Malleable2.5D(kernels=1)**  |          |           |          |           | RGBD  |               |    CVPR   | 2020 |         80.26        |  96.40   |     |        |     |
| **Malleable2.5D(kernels=3)**  |          |           |          |           | RGBD  |               |    CVPR   | 2020 |         80.81        |  96.51   |     |        |     |
|            **SANet**          |   80.9   |   59.6    |   91.4   |    80.2   | RGBD  |               |    CVPR   | 2020 |                      |          |     |        |     |
|         **SOSD-Net**          |          |           |          |           | RGBD  |               |    CVPR   | 2021 |          68.2        |          |     |        |     |

ScaNet
|  Method |bathtub| bed |bookshelf |cabinet |chair |counter |curtain |desk |door |floor |otherfurniture |refrigerator |picture |shower curtain |sink |sofa |table |toilet |wall |window |Published|Year|mIoU| 
| :-----: | :---: |:---:| :------: | :----: | :--: | :----: | :----: | :-: | :--:| :--: |   :-------:   |   :-----:   | :---: | :------------: | :--:| :-: |:----:| :----:|:--:|:---:|:-------:|:--:|:--:|
|**MCA-Net**|0.533|**0.756**|**0.746**|**0.590**|0.334|**0.506**|0.670|**0.587**|0.500|**0.905**|**0.366**|0.352|0.601|**0.506**|0.669|**0.648**|**0.501**|0.839|0.769|0.516|IEEE Transactions|2020|**0.595**|
|  bookshelf |
|     cabinet    |
|     chair      |
|     counter    |
|     curtain    |
|     desk       |
|     door       |
|     floor       |
| otherfurniture |
|   refrigerator |
|     shower     |
|     curtain    |
|     sink       |
|     sofa       |
|     table      |
|     toilet     |
|     wall       |
|     window     |
|    59.1     |    28.4     |    29.1    |             | RGBD  |                 |    CVPR     | 2013 |


