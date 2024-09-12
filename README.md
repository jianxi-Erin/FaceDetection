# 人脸识别检测程序

这是一个使用 OpenCV 实现的视频人脸检测程序。程序可以实时检测视频中的正面人脸和侧脸，并在检测到的人脸上绘制识别框和置信度。支持从本地摄像头、视频文件或网络视频流中读取视频。

## 功能

- 实时检测正面人脸（使用 `haarcascade_frontalface_alt2.xml` 分类器）
- 实时检测侧脸（使用 `haarcascade_profileface.xml` 分类器）
- 绘制检测到的人脸框，并显示置信度
- 支持从本地摄像头、视频文件或网络视频流中读取视频

## 安装

### 安装依赖

确保你已经安装了 `opencv-python` 库。如果没有，请使用以下命令安装：

```bash
pip install opencv-python
```
### 运行
```bash
python FaceDetection.py
```
