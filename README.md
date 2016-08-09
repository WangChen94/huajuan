# 花卷

> Cloudinsight 技术博客使用的 Ghost 主题。

![截图](https://cloud.githubusercontent.com/assets/171947/17508392/560a9392-5e47-11e6-9c94-1004828e0ddd.png)

## 怎么使用

下载最新的主题压缩包：

https://github.com/cloudinsight/huajuan/archive/v2.0.1.zip

解压到 `themes` 目录下（一般在 `/var/lib/ghost/themes`），然后在 Ghost 的网站设置里选用新的主题。

## 怎么开发

**方法1**

开发之前，先把 `ghost` 博客跑起来，然后把项目克隆到 `themes` 下，以默认的 `development` 模式启动，对文件的修改立刻可见。

**方法2**

在本地装好 `docker` 环境，并装上 `docker-compose` 工具，然后执行 `npm start`，访问 `127.0.0.1:2368` 即可。

## 参考文档

寻找主题灵感 http://marketplace.ghost.org/

Ghost 主题开发的文档 http://themes.ghost.org/

## 开源协议

[License](./LICENSE)
