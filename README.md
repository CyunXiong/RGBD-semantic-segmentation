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

Cityscape
|              Method           | IoU cla. | iIoU cla. | IoU cat. | iIoU cat. | Input |   Ref. from   | Published | Year |         mIoU         | pixel Acc|  AP | AP[val]| FPS |
| :---------------------------: | :------: | :-------: | :------: | :-------: | :---: | :-----------: | :-------: | :--: | :------------------: |  :-----: |:---:|:-----: |:--: |
|             **POR**           |   59.1   |   28.4    |   29.1   |           | RGBD  |               |    CVPR   | 2013 |                      |          |     |        |     |
|          **RGBD R-CNN**       |   60.3   |   35.1    |   31.3   |           | RGBD  |               |    ECCV   | 2014 |                      |          |     |        |     |
|          **DeconvNet**        |   69.9   |   56.4    |   42.7   |      56   |  RGB  |  **LSD-GF**   |    ICCV   | 2015 |                      |          |     |        |     |
|           **DeepLab**         |   68.7   |   46.9    |   36.8   |     52.5  | RGBD  |   **STD2P**   |    ICLR   | 2015 |
|           **CRF-RNN**         |   66.3   |   48.9    |   35.4   |      51   | RGBD  |   **STD2P**   |    ICCV   | 2015 |
|         **AdapNet++**         |          |           |          |           | RGBD  |               |    IJCV   | 2019 |        80.80         |          |     |        |     |
|            **[P]-HPM**        |          |           |          |           |  RGB  |               |    IEEE   | 2020 |      83.38[IoU]      |          |     |        |     |
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
|          **RFNet**            |          |           |          |           | RGBD  |               |    IEEE   | 2020 |         72.5         |          |     |        |     |
|        **BCMFP+SA-Gate**      |          |           |          |           | RGBD  |               |    ECCV   | 2020 |         82.8         |          |     |        |     |
|           **VCD**             |          |           |          |           | RGBD  |               |    IEEE   | 2020 |         82.3         |          |     |        |     | 
|           **RRL**             |          |           |          |           | RGBD  |               |    IEEE   | 2020 |                      |          | 29.7|  35.2  |     |
| **Malleable2.5D(kernels=1)**  |          |           |          |           | RGBD  |               |    CVPR   | 2020 |         80.26        |  96.40   |     |        |     |
| **Malleable2.5D(kernels=3)**  |          |           |          |           | RGBD  |               |    CVPR   | 2020 |         80.81        |  96.51   |     |        |     |
|            **SANet**          |   80.9   |   59.6    |   91.4   |    80.2   | RGBD  |               |    CVPR   | 2020 |                      |          |     |        |     |
|         **SOSD-Net**          |          |           |          |           | RGBD  |               |    CVPR   | 2021 |          68.2        |          |     |        |     |

ScaNet
|  Method |bathtub| bed |bookshelf |cabinet |chair |counter |curtain |desk |door |floor |otherfurniture |refrigerator |picture |shower curtain |sink |sofa |table |toilet |wall |window |Published|Year|mIoU|avg|Ref. from|Input|   
| :-----: | :---: |:---:| :------: | :----: | :--: | :----: | :----: | :-: | :--:| :--: |   :-------:   |   :-----:   | :---: | :------------: | :--:| :-: |:----:| :----:|:--:|:---:|:-------:|:--:|:--:|:--:|:-------:|:--:|
|**3D-SIS**|66.7|55.4|31.9|13.4|58.7|0.0|0.0|12.1|30.7| |21.0|54.1|0.6|1.0|4.5|72.8|22.4|88.9| |18.1|CVPR|2019| |36.2||RGB|
|**3D-SIS+geo+5views**|57.6|66.3|16.9|32.0|65.3|22.1|22.6|35.1|26.7| |21.1|28.6|0.0|37.2|39.6|56.4|29.4|74.9| |10.1|CVPR|2019|25|35.7||RGB|
|**AdapNet++**|68.65|60.72|52.15|46.48|58.89|32.79|37.12|39.66|55.15|80.41|31.46|54.54|26.73|54.88|54.91|55.12|58.42|81.92|71.21|37.18|IJCV|2019|52.92| |RGB|
|**MCA-Net**|53.3|75.6|74.6|59.0|33.4|50.6|67.0|58.7|50.0|90.5|36.6|35.2|60.1|50.6|66.9|64.8|50.1|83.9|76.9|51.6|IEEE|2020|59.5| |RGBD|
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


