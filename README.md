# open-dev
open sources dev

## 文档不太完善，安装过程中有任何问题随时问


### Windows平台

#### 下载使用IDEA

下载地址：https://www.jetbrains.com/idea/

破解地址：http://idea.lanyus.com/

#### 搭建NodeJS环境  - 官方下载安装包后，命令行识别node命令即为安装成功.

下载地址：https://nodejs.org/en/

#### 安装Gulp

安装指南：http://www.gulpjs.com.cn/docs/getting-started/



#### Nginx安装及配置

首先：

1.下载安装nginx

2.把前端项目统一放在D:\workspace\front-end\目录下面，开发组人统一的路径，减少配置修改。

3.注意日志文件不存在的问题，可以新建logs目录

4.需要在git上下载改版的gulp-version-append,https://github.com/lixiaodong/gulp-version-append
  放在NODE_PATH 目录下，用于支持@version@和@prefix@的变量替换。
  
  NODE_PATH = C:\Users\Administrator\AppData\Roaming\npm\node_modules
  
  上面的路径需要配置在环境变量中，才能在系统各处使用gulp命令
  
#### 下载项目开始编译->运行


1.在根目录运行gulp,如果报错，请安装相关的gulp模块，使用npm install -g gulp-less

2.请参考注意事项



### 注意事项

1.必须以管理员权限运行nginx.exe

2.关闭防火墙

3.本地保证443端口不被占用

4.host配置不要重复



