# Docker Image - Postgresql with Zhparser (Full Text Search for Chinese)

一个简单的 docker image。运行 postgresql 数据库，并安装有 Zhparser 中文搜索扩展。

目前 hardcode 了 postgresql 版本，并且依赖于 CPU 架构（amd64 vs arm64）

如果需要其他的 postgresql 版本，或者其他平台。请提交 PR 或者 Issue

## Docker Hub

[https://hub.docker.com/r/fengzhichao/postgres_zhparser](https://hub.docker.com/r/fengzhichao/postgres_zhparser)
