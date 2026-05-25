# OpenClaw Docker Build

This repository is used to build the OpenClaw Docker image via GitHub Actions.

GitHub Actions 负责构建镜像并推送到 Docker Hub。

## 你需要做的

1. Fork 此仓库
2. 在 GitHub Secrets 中添加 `DOCKERHUB_USERNAME` 和 `DOCKERHUB_TOKEN`
3. 在 Actions 页面手动触发 workflow
4. 完成后在本地执行：`docker pull <your-username>/openclaw:latest`

## 本仓库用途

- 只存放 GitHub Actions workflow 配置
- 源码从 Gitee 自动拉取构建
