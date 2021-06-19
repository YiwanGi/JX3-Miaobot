# JX3-Miaobot（该项目仍在筹备中）

- 开箱即用
- 功能完善
- 维护方便
- 网页控制面板
- 数据接口独立
- 经历商业检验

## 安装使用
要求 `PHP >= 8.0` `Swoole >= 4.6` `Mysql` `Redis`
```shell
composer create-project yiwangi/jx3-miaobot robot #构建项目
cd robot #进入目录
# 启动框架前请先修改配置文件 config/global.php 【1.修改Mysql配置 2.修改Redis配置 3.将框架开到公网IP】
vendor/bin/start server #启动框架
```

#### [GO-CQHTTP 下载（v1.0.0-beta4）](https://github.com/Mrs4s/go-cqhttp/releases/tag/v1.0.0-beta4)

JX3-Miaobot is released under the MIT License. See [`LICENSE`](LICENSE) for details.
