# **奶牛数据集（彩色+红外）**
目前，畜禽养殖技术正逐步向设施化、智能化和规模化方向迈进，畜禽养殖的健康状况和行为饮食信息等从高度依赖人工经验发展为智能化养殖模式。为了满足畜禽养殖过程中的动物监测跟踪等任务，训练深度目标检测模型以预测畜禽的定位和类别信息，在牛场中通过双目异构相机进行视频跟踪采集，分别建立了彩色和红外牛群目标检测数据集，格式为Pascal VOC，并通过kmeans聚类算法对xml标注文件进行聚类得到九个尺寸的anchor box。基于红外及彩色牛场数据，可用于相应家畜、家禽目标检测与识别算法设计及训练，从而帮助畜禽识别检测工作，后续我们将会不断扩展其他类别的家畜、家禽，进行实地采集并上传数据集。
## 数据集下载链接
彩色及红外数据集已上传到百度网盘，以下提供下载链接。  
彩色牛群数据集总体为9个G左右，分为三个压缩包上传，共包括包括3974张图片（JPEGImages文件夹中）及其.xml格式标注信息文件（Annotations文件夹中），标注类别分为三类：cow（奶牛整体）、head（牛头）、tail（牛尾），以下为下载链接：   
rgb1：https://pan.baidu.com/s/1ApcLSp4bNlYS9r7M0yO1YA  提取码：m100   
rgb2：https://pan.baidu.com/s/1t2FoIT7kpvrHoi-hwE5koQ 提取码：68ly   
rgb3：链接：https://pan.baidu.com/s/1BNsYqD2epLj_3JKFRWnFiA  提取码：1z4l   

红外牛群数据集总体为449MB，共一个压缩包，包括4119张图片（JPEGImages文件夹中）及其.xml格式标注信息文件（Annotations文件夹中），标注类别同分为三类：cow（奶牛整体）、head（牛头）、tail（牛尾），以下为下载链接：
https://pan.baidu.com/s/1CNV18B5Ws77IDS15KM70bQ  提取码：cff7 
## 数据集奶牛标注示例图
<img src="https://github.com/luowenji/cow/blob/main/example/inf1.jpg" width="600" height="400" alt="红外示例"/>
<img src="https://github.com/luowenji/cow/blob/main/example/rgb1.jpg" width="600" height="400" alt="彩色示例"/>

## Kmeans聚类所得anchor box
    红外：23,43  47,77  55,169  89,103  114,162  129,280  178,140  216，283  343,318

    彩色：7,24  17,33  29,44  51,63  19,89  54,117  82,92  105,170  172,254

