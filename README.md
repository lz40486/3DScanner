# 3DScanner
三维扫描相关算法
  
  包括多频外差相位求解、相机标定、点云后处理等相关算法

一、模块介绍
相机驱动：
Camera.h
CameraApi.h
CameraDefine.H
CameraStatus.h
标定：
CameraCalibrator.h
StereoCalib.h
点云可视化：
VtkViewer.h
VtkViewer.cpp
投影仪：
Projector.h
多频外差相位展开：
gxbUnpackPhase.h
gxbUnpackPhase.cpp
双目匹配：
gxbPhaseMatch.h
图片可视化：
CvvImage.h
CvvImage.cpp
主程序窗口：
demo0316Dlg.h
demo0316Dlg.cpp
二、环境说明
开发环境：win7 64位 、visual studio 2015 
算法包：opencv3.1.1、pcl1.8.0
运行环境：16G内存，AMD速龙Ⅱ主频3Ghz
