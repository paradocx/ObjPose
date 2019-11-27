DenseFusion
========

(CVPR2019) DenseFusion 6D Object Pose Estimation by Iterative Dense Fusion
--------

### 准备：
* [DenseFusion](https://github.com/j96w/DenseFusion/tree/Pytorch-1.0) <br>
* [代码重译版，能调试通过](https://github.com/hoangcuongbk80/Object-RPE/tree/master/DenseFusion)<br>
* [代码调试和解析细节](https://blog.csdn.net/weixin_43013761/article/details/103053585)

### 安装：
anaconda+pytorch 建议配置顺序
 * 从anaconda配置python3.5为主体的环境开始 后面的操作都在torch环境下进行 <br>
 * 还需要install numpy scipy pyyaml cffi pyyaml matplotlib Cython Pillow <br>
 * pytorch的安装 `不建议直接使用官网的指令` ，请去查阅[历史版本](https://pytorch.org/get-started/previous-versions/) <br>
   尤其需要注意CUDA的版本 一定要是10.1

### 数据源：
* YCB（约200+G）可选择[百度网盘](https://github.com/yuxng/PoseCNN/issues/81)等途径,原地址采用google站点需要翻墙 <br>
* LineMOD（约8.4G） 可直接原地址翻墙下载即可 <br>
* Trained_checkpoints（约200+M） 原地址显示404 Not Found 联系其他人得到的数据  <br>
按照download.sh的指令细节解压并放置对应文件夹

### 调试细节：
* 由于LineMOD下载更快，先行尝试训练。解压对应文件夹放置到对应位置（参见作者一的代码）。 <br>
   1. 提示CV2的错误，安装 `opencv` （Notice：处理摄像头输入视频需要with-ffmpeg）。 <br>
