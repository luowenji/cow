# **奶牛数据集（彩色+红外）**
目前，畜禽养殖技术正逐步向设施化、智能化和规模化方向迈进，畜禽养殖的健康状况和行为饮食信息等从高度依赖人工经验发展为智能化养殖模式。为了满足畜禽养殖过程中的动物监测跟踪等任务，训练深度目标检测模型以预测畜禽的定位和类别信息，在牛场中通过双目异构相机进行视频跟踪采集，分别建立了彩色和红外牛群目标检测数据集，格式为Pascal VOC，并通过kmeans聚类算法对xml标注文件进行聚类得到九个尺寸的anchor box。
## 数据集下载链接
彩色及红外数据集已上传到百度网盘，以下提供下载链接。  
彩色牛群数据集总体为9个G左右，分为三个压缩包上传，包括3974张图片及其标注信息，标注类别分为三类：cow（奶牛整体）、head（牛头）、tail（牛尾）。  
  
红外牛群数据集总体为449MB，包括4119张图片及其标注信息，标注类别同分为三类：cow（奶牛整体）、head（牛头）、tail（牛尾）。  

## 奶牛图片及标注示例
![数据集标注示例](https://raw.githubusercontent.com/luowenji/cow/main/example/inf1.jpg?token=AP623VM3IEPFHYZWWF64K6TACZDKW)

