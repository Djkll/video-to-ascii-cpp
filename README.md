# Video to ASCII Converter

## Usage

1. 下载opencv源码，[OpenCV](https://opencv.org/) (>= 4.0)，自行编译。
2. 在video文件夹内加入自己想展现的vido，并在main.cpp更改video的路径。
3. 在build.sh中更改opencv的lib动态链接库路径
4. 在terminal内运行 <br />
    ```
    ./build.sh
    ```
5. 在终端运行时请自行调整缩放大小。

Windows平台可能有bug，比如“clear”是内部或外部命令，也不是可运行的程序。请将system("clear")更改为system("cls")，或者解决本机系统环境变量问题。
Mac和Liunx完全适配。

## Dependencies
This project depends on the following libraries:

- [OpenCV](https://opencv.org/) (>= 4.0)

servetgulnaroglu's video-to-ascii-cpp

