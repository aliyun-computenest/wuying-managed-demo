# 代码仓库结构

文档目录说明：
```
├── README.md                                       - README
├── docs                                            - 服务文档相关文件
│   └── index.md
├── resources                                       - 服务资源文件
│   ├── icons
│   │   └── service_logo.png                                - 服务logo
│   └── artifact_resources                          - 部署物相关资源文件
│       └── file                                    - 文件部署物目录
│           ├── epel-release-latest-7.noarch.rpm    - epel安装包
│           ├── remi-release-7.rpm                  - remi安装包
│           └── wordpress-6.2-zh_CN.tar.gz          - wordpress文件部署物
├── ros_templates                                   - 服务ROS模板，可以有多个
│   └── cluster.yaml                                - 集群版ROS模板
│   └── template.yaml                               - 单机版ROS模板
├── config.yaml                                     - 服务配置文件
├── preset_parameters.yaml                          - 服务商预设参数，如VpcId，VSwitchId等，该ros模板内容会渲染为表单方便服务商填写
```