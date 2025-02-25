# Detection Model Zoo

## YOLOX

Pretrained on COCO2017 dataset.

| Algorithm  | Config                                                       | mAP<sup>val<br/><sub>0.5:0.95</sub> | AP<sup>val<br/><sub>50</sub> | Download                                                     |
| ---------- | ------------------------------------------------------------ | ------------------------ | --------------- | ------------------------------------------------------------ |
| YOLOX-s    | [yolox_s_8xb16_300e_coco](https://github.com/alibaba/EasyCV/tree/master/configs/detection/yolox/yolox_s_8xb16_300e_coco.py) | 40.0                   | 58.9          | [model](http://pai-vision-data-hz.oss-cn-zhangjiakou.aliyuncs.com/EasyCV/modelzoo/detection/yolox/yolox_s_bs16_lr002/epoch_300.pth) - [log](http://pai-vision-data-hz.oss-cn-zhangjiakou.aliyuncs.com/EasyCV/modelzoo/detection/yolox/yolox_s_bs16_lr002/log.txt) |
| YOLOX-m    | [yolox_m_8xb16_300e_coco](https://github.com/alibaba/EasyCV/tree/master/configs/detection/yolox/yolox_m_8xb16_300e_coco.py) | 46.3                   | 64.9          | [model](http://pai-vision-data-hz.oss-cn-zhangjiakou.aliyuncs.com/EasyCV/modelzoo/detection/yolox/yolox_m_bs16_lr002/epoch_300.pth) - [log](http://pai-vision-data-hz.oss-cn-zhangjiakou.aliyuncs.com/EasyCV/modelzoo/detection/yolox/yolox_m_bs16_lr002/log.txt) |
| YOLOX-l    | [yolox_l_8xb8_300e_coco](https://github.com/alibaba/EasyCV/tree/master/configs/detection/yolox/yolox_m_8xb8_300e_coco.py) | 48.9                  | 67.5        | [model](http://pai-vision-data-hz.oss-cn-zhangjiakou.aliyuncs.com/EasyCV/modelzoo/detection/yolox/yolox_l_bs8_lr001/epoch_290.pth) - [log](http://pai-vision-data-hz.oss-cn-zhangjiakou.aliyuncs.com/EasyCV/modelzoo/detection/yolox/yolox_l_bs8_lr001/log.txt) |
| YOLOX-x    | [yolox_x_8xb8_300e_coco](https://github.com/alibaba/EasyCV/tree/master/configs/detection/yolox/yolox_x_8xb8_300e_coco.py) | 50.9                   | 69.2          | [model](http://pai-vision-data-hz.oss-cn-zhangjiakou.aliyuncs.com/EasyCV/modelzoo/detection/yolox/yolox_x_bs8_lr001/epoch_290.pth) - [log](http://pai-vision-data-hz.oss-cn-zhangjiakou.aliyuncs.com/EasyCV/modelzoo/detection/yolox/yolox_x_bs8_lr001/log.txt) |
| YOLOX-tiny | [yolox_tiny_8xb16_300e_coco](https://github.com/alibaba/EasyCV/tree/master/configs/detection/yolox/yolox_tiny_8xb16_300e_coco.py) | 31.5                   | 49.2          | [model](http://pai-vision-data-hz.oss-cn-zhangjiakou.aliyuncs.com/EasyCV/modelzoo/detection/yolox/yolox_tiny_bs16_lr002/epoch_300.pth) - [log](http://pai-vision-data-hz.oss-cn-zhangjiakou.aliyuncs.com/EasyCV/modelzoo/detection/yolox/yolox_tiny_bs16_lr002/log.txt) |
| YOLOX-nano | [yolox_nano_8xb16_300e_coco](https://github.com/alibaba/EasyCV/tree/master/configs/detection/yolox/yolox_tiny_8xb16_300e_coco.py) | 26.5                   | 42.6          | [model](http://pai-vision-data-hz.oss-cn-zhangjiakou.aliyuncs.com/EasyCV/modelzoo/detection/yolox/yolox_nano_bs16_lr002/epoch_300.pth) - [log](http://pai-vision-data-hz.oss-cn-zhangjiakou.aliyuncs.com/EasyCV/modelzoo/detection/yolox/yolox_nano_bs16_lr002/log.txt) |

## ViTDet

| Algorithm  | Config                                                       | bbox_mAP<sup>val<br/><sub>0.5:0.95</sub> | mask_mAP<sup>val<br/><sub>0.5:0.95</sub> | Download                                                     |
| ---------- | ------------------------------------------------------------ | ------------------------ | --------------- | ------------------------------------------------------------ |
| ViTDet_MaskRCNN    | [vitdet_maskrcnn](https://github.com/alibaba/EasyCV/tree/master/configs/detection/vitdet/vitdet_100e.py) | 50.57                   | 44.96          | [model](https://pai-vision-data-hz.oss-cn-zhangjiakou.aliyuncs.com/EasyCV/modelzoo/detection/vitdet/vit_base/vitdet_maskrcnn.pth) - [log](https://pai-vision-data-hz.oss-cn-zhangjiakou.aliyuncs.com/EasyCV/modelzoo/detection/vitdet/vit_base/vitdet_maskrcnn.log.json) |

## FCOS

| Algorithm  | Config                                                       | mAP<sup>val<br/><sub>0.5:0.95</sub> | AP<sup>val<br/><sub>50</sub> | Download                                                     |
| ---------- | ------------------------------------------------------------ | ------------------------ | --------------- | ------------------------------------------------------------ |
| FCOS-r50    | [fcos-r50](https://github.com/alibaba/EasyCV/tree/master/configs/detection/fcos/fcos_center-normbbox-centeronreg-giou_r50_caffe_fpn_gn-head_1x_coco.py) | 38.58                   | 57.18          | [model](https://pai-vision-data-hz.oss-cn-zhangjiakou.aliyuncs.com/EasyCV/modelzoo/detection/fcos/epoch_12.pth) - [log](https://pai-vision-data-hz.oss-cn-zhangjiakou.aliyuncs.com/EasyCV/modelzoo/detection/fcos/20220621_121315.log.json) |
## DETR

| Algorithm  | Config                                                       | bbox_mAP<sup>val<br/><sub>0.5:0.95</sub> | AP<sup>val<br/><sub>50</sub> | Download                                                     |
| ---------- | ------------------------------------------------------------ | ------------------------ | --------------- | ------------------------------------------------------------ |
| DETR-r50    | [detr-r50](https://github.com/alibaba/EasyCV/tree/master/configs/detection/detr/detr_r50_8x2_150e_coco.py) | 39.92                   | 60.52          | [model](https://pai-vision-data-hz.oss-cn-zhangjiakou.aliyuncs.com/EasyCV/modelzoo/detection/detr/epoch_150.pth) - [log](https://pai-vision-data-hz.oss-cn-zhangjiakou.aliyuncs.com/EasyCV/modelzoo/detection/detr/20220609_101243.log.json) |
| DAB-DETR-r50    | [dab-detr-r50](https://github.com/alibaba/EasyCV/tree/master/configs/detection/dab_detr/dab_detr_r50_8x2_50e_coco.py) | 42.52                   | 63.03          | [model](https://pai-vision-data-hz.oss-cn-zhangjiakou.aliyuncs.com/EasyCV/modelzoo/detection/dab_detr/epoch_50.pth) - [log](https://pai-vision-data-hz.oss-cn-zhangjiakou.aliyuncs.com/EasyCV/modelzoo/detection/dab_detr/20220610_122811.log.json) |
