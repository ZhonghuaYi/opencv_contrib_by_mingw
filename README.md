# opencv_contrib_by_mingw

This is the built version by MinGW x64 of OpenCV and its contrib. It only works on Windows.

It's built by MinGW x64 v9.0 and CMake v3.23.

## Installation

You can pull this repository directly by using command below:

```shell
$ git pull git@github.com:ZhonghuaYi/opencv_contrib_by_mingw.git
```

or download the zip file from release.

 After you pulled this repository, add `OpenCV_DIR=${repo path}/install` into your system variables, and `${repo path}` is the repository's absolute path in your computer. Then add `${repo path}/install/x64/mingw/bin` into system `Path` variable, in order to make sure all the .dll files can be found when your OpenCV project is running.
