# 无人机通信
## 环境准备
### boost 安装
1. 版本 1.81.0
2. 安装
   ```shell
   # 官网下载源码 https://boostorg.jfrog.io/artifactory/main/release/1.81.0/source/
   # 下载到指定目录解压
   cd boost_1_81_0
   ./bootstrap.sh
   sudo ./b2
   sudo ./b2 install
   # 这样 boost 就会安装的缺省路径 /user/local，也就是头文件在 /usr/local/include/，库文件（lib）在 /usr/local/lib
   ```

### websocketpp 安装

```shell
git clone https://github.com/zaphoyd/websocketpp.git
cd websocketpp #进入目录
cmake CMakeList.txt #执行cmake
sudo make
sudo make install
```



