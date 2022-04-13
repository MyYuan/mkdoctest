# Home

## 简介

链桨是 **百度超级链** 与 **飞桨** 联合推出的首款 **产业级** 可信分布式AI开源产品。该产品基于区块链、去中心化存储、可信计算以及分布式机器学习等技术，推动实现数据采集、存储、计算、及流通全流程安全可信，打破数据孤岛，让数据发挥更大价值，[立即了解](introduction/introduction.md)。
  
## 快速入口

### 1.1 编译安装
=== "脚本快速安装"
    !!! Note "" 
        PaddleDTX提供了快速搭建测试网络的脚本，通过Docker-Compose一键拉起区块链网络、去中心化存储网络和DAI网络，支持用户本地运行测试。

        &emsp; [快速安装](quickstart/quickstart.md){ .md-button }

=== "源码编译安装"
    !!! Note "" 
        正式环境中，用户可以通过源码编译安装，按需搭建业务系统所需的服务。

        &emsp; [编译安装](quickstart/compile-install.md){ .md-button }

=== "Docker安装"
    !!! Note "" 
        PaddleDTX提供了镜像构建脚本，用户可以通过build_image.sh构建镜像，使用Docker-compose或K8s启动服务。

        &emsp; [docker安装](quickstart/docker-install.md){ .md-button }

### 1.2 基本操作
=== "客户端工具"
    !!! Note "" 

        用户安装完可信分布式AI网络后，即可操作XuperDB、DAI客户端工具进行文件上传、任务发布等。

        &emsp; [立刻体验](quickstart/client.md){ .md-button }

=== "命令行操作"
    !!! Note "" 

        针对计算需求节点、计算节点、数据持有节点、存储节点等详细命令操作，参考**教程**小节。

        &emsp; [Get Start](tutorial/dai-cmd.md){ .md-button }


### 1.3 业务集成
=== "API/GRPC API"
    !!! Note "" 

        用户可以通过**API、GRPC API**方式将业务系统集成到PaddleDTX，进行训练或预测任务的发布、数据存储、数据共享等，PaddleDTX支持底层区块网络的灵活切换。

        &emsp; [Get Start](development/api.md){ .md-button }

=== "项目案例"
    !!! Note "" 

        通过测试案例可以评估模型训练、预测的效果，PaddleDTX提供了基于波士顿房价预测的线形回归算法和基于鸢尾花的逻辑回归算法。

        &emsp; [Get Start](projectcases/linear.md){ .md-button }


## Need Help？

通过以下链接联系 PaddleDTX 团队：

<img src='../../_static/discuss.png' width = "5%" height = "5%" align="middle" />
[社区交流](https://developer.baidu.com/singleTagPage.html?tagId=269&type=QUESTION)  &emsp;
<img src='../../_static/issue.png' width = "4%" height = "4%" align="middle" />
[Github Issues](https://github.com/PaddlePaddle/PaddleDTX/issues)


<br>