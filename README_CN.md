# opencv_contrib_by_mingw

* [English README](README.md)

这是已经用MinGW x64编译完成的OpenCV和OpenCV contrib，它只能在Windows上使用。

使用的是MinGW x64 v9.0和CMake v3.23.

## 下载

可以直接使用以下命令拉取这个仓库：

```shell
$ git pull git@github.com:ZhonghuaYi/opencv_contrib_by_mingw.git
```

或者在release里下载zip文件。

拉取完这个仓库后，将`OpenCV_DIR=${repo path}/install`加入到你的系统变量中，其中 `${repo path}`是这个仓库在你的设备上的绝对路径。之后将`${repo path}/install/x64/mingw/bin`加入到系统的`Path`变量中，这能保证在你的OpenCV项目运行时，相关的.dll文件能够被正确找到。