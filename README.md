# Demo

## 项目简介
**基于`kratos`构建的土拨鼠社区基础服务**
## Build & Run
1. 命令行:
    ```shell script
    cd kratos-demo/cmd
    go build
    ./cmd -conf ../configs
    ```
2. GoLand:

    在`Program arguments`中加入`-conf configs`
## 注意事项
- 配置环境变量
  - GO111MODULE=on
  - GOPROXY=https://goproxy.io
- 开发工具:[GoLand](https://www.jetbrains.com/go/)