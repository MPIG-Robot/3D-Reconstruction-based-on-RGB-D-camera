# 基于深度相机的三维重建

通过kinect相机获取深度数据进行处实现三维重建
## 简介
参考了**kinfu**，用cmake编译**pcl**（点云库），kinectfusion的开源实现
## 环境配置，工具准备
kinect，vs2010 x64，cmake 3.5.0，CUDA5.0或更高，OPENNI1.5.4，sensorkinect
第三方库（这里提供一套可成功运行的版本及其下载链接）
[Boost-1.49.0](http://sourceforge.net/projects/pointclouds/files/dependencies/Boost-1.49.0-vs2010-x64.exe/download)
[qhull-6.2.0.1385](http://sourceforge.net/projects/pointclouds/files/dependencies/qhull-6.2.0.1385-vs2010-x64.exe/download)
[VTK-5.8.0](http://sourceforge.net/projects/pointclouds/files/dependencies/VTK-5.8.0-msvc2010-win64_with_qt_support.exe/download)
[Qt_4.8.0](http://sourceforge.net/projects/pointclouds/files/dependencies/Qt_4.8.0_msvc2010_win64.exe/download)
[flann-1.7.1](http://sourceforge.net/projects/pointclouds/files/dependencies/flann-1.7.1-vs2010-x64.exe/download0)
[Eigen-3.0.5](http://sourceforge.net/projects/pointclouds/files/dependencies/Eigen-3.0.5.exe/download)
含有kinectfusion的pcl源码：https://github.com/yataozhong/pcl.git/
## cmake编译配置pcl
参考链接： http://pointclouds.org/documentation/tutorials/compiling_pcl_windows.php#compiling-pcl-windows
## 注意事项
1.安装openni作为kinect的数据获取，则不能使用官方的SDK，安装时不能接入kinect。
2.建议第三方库安装时选择默认路径。




 
