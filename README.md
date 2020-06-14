# detection_object_on_own_data
the easiest way to train your own dataset

#第一步当你拿到标注的数据格式是voc格式时，即
--VOC2007
   --Annotations
   --ImageSets
     --Main
     --Layout
     --Segmentation
   --JPEGImages
   --SegmentationClass  ##这是分割信息，不是必须的
   --SegmentationObject ##分割信息，不是必须的
   
   这时候需要做的是对根据将样本信息整合生成如下的格式：
   0 D:\pycharm\project\yolo_test\data/my_data/VOC2028/JPEGImages/000000.jpg 947 1421 0 60 66 910 1108 ...
   
   
