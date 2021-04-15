<p align="center">
  <img height="100px" src="./logo.png" />
</p>

# [NodeBB](https://github.com/NodeBB/NodeBB)

NodeBB是一款基于Node.js构建的论坛系统。

## 部署

本项目基于开源项目 [CloudBase Framework](https://github.com/Tencent/cloudbase-framework) 开发部署，支持一键云端部署

[![](https://main.qcloudimg.com/raw/67f5a389f1ac6f3b4d04c7256438e44f.svg)](https://console.cloud.tencent.com/tcb/env/index?action=CreateAndDeployCloudBaseProject&appUrl=https%3A%2F%2Fgithub.com%2FTencent-Cloud-Plugins%2FTencentCloudBase-NodeBB&branch=master)
### 配置
- `APP_URL`：NodeBB首页地址
- `ADMIN_USERNAME`：NodeBB管理员账号
- `ADMIN_PASSWORD`：NodeBB管理员密码

### 依赖

- CFS：使用 CFS 持久化存储数据

## 注意事项

1. 部署时，需要将服务路径设置为根路径 `/`
