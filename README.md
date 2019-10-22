# gmapping_whd
ros封装的源码包为slam_gmapping;open_gmapping为最初源码.

主要注释内容为ros封装后的源码 ~/slamgmapping/gmapping/src/gmapping_slam.cpp

主要关于黑盒参数的意义

### 更新10-22

发现问题:openslam_gmapping包下载错误,openslam.org上的github源码并不兼容ros

通过

```
rospack find openslam_gmapping
```

可以发现其地址并不是git后的地址而在kinetic下

故应该在roswiki上下载相应包

[https://github.com/ros-perception/openslam_gmapping.git](https://github.com/ros-perception/openslam_gmapping)

安装成功后如图编译完如图所示

![](/home/sparta/桌面/成功截图.png)