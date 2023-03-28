# 小目标检测yolo_transformer_
yolov5 v6.0+自注意力机制
加入了一些列transformer机制
使用swin-transformer

环境：
    ---python 3.8.0
     |_torch 1.12.0
     |_CUDA NVIDIA GeForce RTX 4060
     |_win11
--------------------------------------------------
在盐焗鸡蛋30克视觉检测项目中，为了解决卤蛋缺陷检测过程中存在的小目标检测困难问题，主要表现为像素值过小，感受野增大时对小目标检测不友好，在yolov5 v6.0中加入了swin-transformer，

与未加入swin-transformer之前相比，map上升了5个点，precision上升了0.5个点，平均检测时间10ms，参数pt文件大小10M，对卤蛋检测有一定程度帮助。
