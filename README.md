DenseFusion
========

(CVPR2019) DenseFusion 6D Object Pose Estimation by Iterative Dense Fusion
--------

### 准备：
1. [DenseFusion](https://github.com/j96w/DenseFusion/tree/Pytorch-1.0) <br>
2. [代码重译版，能调试通过](https://github.com/hoangcuongbk80/Object-RPE/tree/master/DenseFusion)<br>
3. [代码调试和解析细节](https://blog.csdn.net/weixin_43013761/article/details/103053585)

### 安装：
1. anaconda+pytorch 建议配置顺序
 * 从anaconda配置python3.5为主体的环境开始 后面的操作都在torch环境下进行 <br>
 * 还需要install numpy scipy pyyaml cffi pyyaml matplotlib Cython Pillow <br>
 * pytorch的安装`不建议直接使用官网的指令`，请去查阅[历史版本](https://pytorch.org/get-started/previous-versions/)

### 数据源：
1.YCB（约200+G）可选择[百度网盘](https://github.com/yuxng/PoseCNN/issues/81)等途径,原地址（原项目Readme）采用google站点需要翻墙 <br>
2.LineMOD（约8.4G）直接原地址翻墙下载即可 <br>
3.

### 调试细节：
1.由于LineMOD下载更快，先行尝试训练。解压对应文件夹放置到对应位置（参见作者一的代码，且二不具有对应目录）。 <br>
 （1） 提示CV2的错误，安装 `opencv` （Notice：处理摄像头输入视频需要with-ffmpeg）。 <br>
