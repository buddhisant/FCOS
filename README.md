# FCOS
基于pytorch的标准版FCOS，支持多卡分布式训练，完全python实现，无需安装。

**代码中有多处参考或照抄了[maskrcnn_benchmark](https://github.com/facebookresearch/maskrcnn-benchmark)和[mmdetection](https://github.com/open-mmlab/mmdetection)**

**更多目标检测代码请参见[友好型的object detection代码实现和论文解读](https://blog.csdn.net/gongyi_yf/article/details/109660890)**

**backbone网络基于resnet50**

# 使用方法：
- git clone https://github.com/buddhisant/FCOS.git
- cd FCOS
- mkdir pretrained
- cd pretrained
- wget https://download.openmmlab.com/pretrain/third_party/resnet50_caffe-788b5fa3.pth -O resnet50_caffe.pth
- cd ..
- 
