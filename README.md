# Synology-docker-cfproxy
本代码在[cmliu](https://github.com/cmliu/CF-Workers-docker.io/blob/main/_worker.js) 的源码基础上修改得来。

## 说明

该版本针对群晖Container Manager进行了适配，解决了群晖注册表查询失败、搜索不能正常使用及拉取版本不显示的问题。

## 部署方式

- **Workers** 部署：复制 [_worker.js](https://github.com/F2xuan/Synology-docker-cfproxy/blob/main/_worker.js) 代码，`保存并部署`即可
- 注意修改workers_url为你自己的域名
## 效果

![demo](./demo.png)
# 感谢
[cmliu](https://github.com/cmliu/CF-Workers-docker.io)
