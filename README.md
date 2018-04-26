# 说明

open-dev是一个开源的前端开发环境搭建指南，每一个程序员的习惯可能都不同，每一个换一个企业可能开发环境又得重新搭建，于是我幻想如果可以设计一种开源的开发环境指南，大家都遵循这个标准来做，是否能够解决一部分问题。

这是一个探索的过程，目前只有一个简单开发环境的指南

# 目的



下面是基于requireJs+jquery+node+gulp+less+nginx的技术架构开发环境的指南

## 文档不太完善，安装过程中有任何问题随时问我，微信：redisio

### Windows平台

#### 下载使用IDEA

下载地址：https://www.jetbrains.com/idea/

破解地址：http://idea.lanyus.com/

#### 搭建NodeJS环境  - 官方下载安装包后，命令行识别node命令即为安装成功.

下载地址：https://nodejs.org/en/

#### 安装Gulp

安装指南：http://www.gulpjs.com.cn/docs/getting-started/



## 安装idea插件

  1.安装gitlab相关插件
  2.复制gitlab->account对应的token跟IDEA关联
  2.checkout from version control ->gitlab
  

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



### Nginx注意事项

1.必须以管理员权限运行nginx.exe

2.关闭防火墙

3.本地保证443端口不被占用

4.host配置不要重复



