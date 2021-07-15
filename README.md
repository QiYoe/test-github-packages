## 简介

使用`github packages`和`docker`注册表创建包。[官方教程](https://docs.github.com/cn/packages/working-with-a-github-packages-registry/working-with-the-docker-registry)

## 官方教程bug1

按照官方教程一顿操作后，发现[使用个人访问令牌进行身份验证](https://docs.github.com/cn/packages/working-with-a-github-packages-registry/working-with-the-docker-registry#authenticating-with-a-personal-access-token)根本不能成功

## 官方教程bug2

`package.json`里面需要加上`publishConfig`选项，而且`https://npm.pkg.github.com`是有域的说法的，具体请看本项目`package.json`

