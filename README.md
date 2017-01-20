# hexo-theme-twilight

> Ported Theme of [Twilight](https://github.com/linzhenzhen/linzhenzhen.github.io.git), <br/>
  Thank [Huxpro](https://github.com/Huxpro) for designing such a flawless theme. <br/>
  Thank [Huxblog](https://github.com/Kaijun) for designing such a flawless theme.

###[Demo &rarr;](https://linzhenzhen.github.io/)


![Blog Demo](https://linzhenzhen.github.io/img/blog-desktop.png)

## 前言

此博客, 只为了自己整理一些平常学习到的内容.

## 搭建方法

`如果是自己搭建Hexo博客的话, 可查看个人博客写的操作详细步骤` [点击跳转] (https://linzhenzhen.github.io/2017/01/01/hello-2017/)

`如果想直接复制全部代码的话, 请按照下面步骤操作`

##### 1.Init

```
git clone https://github.com/linzhenzhen/linzhenzhen.github.io.git
cd linzhenzhen.github.io.git
npm install
```

##### 2.Modify
修改 `_config.yml`.

```
deploy:
  type: git
  repo: https://github.com/linzhenzhen/linzhenzhen.github.io.git
  branch: master
```

##### 3.Serve / Deploy

```
hexo serve      // 开启本地服务
hexo deploy     // Hexo 会把静态文件推送到你master分支上, 如远程没有分支, 会自动生成
```

##### 4.Thanks !
如果喜欢这个代码库, 请点个 [*Star*](https://github.com/linzhenzhen/linzhenzhen.github.io/stargazers).
