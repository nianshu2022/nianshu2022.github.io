# Personal homepage

---

原作者：****無名の主页****

[GitHub - imsyy/home at v4.0.4](https://github.com/imsyy/home/tree/v4.0.4)

[【Vercel】教你部署imsyy/home个人主页_慕雪华年的博客-CSDN博客](https://blog.csdn.net/muxuen/article/details/130334312)

# 1. 配置环境

## 1.1 安装

> npm > 8.15.0
> 
> 
> node > 16.16.0
> 
> git > 2.20.0
> 

## 1.2 构建

然后以 **管理员权限** 运行 `cmd` 终端，并 `cd` 到 项目根目录

```bash
# 安装 yarn
npm install -g yarn

# 安装依赖
yarn install

# 预览
yarn dev

# 构建
yarn build
```

> 构建完成后，静态资源会在 **`dist` 目录** 中生成，可将 **`dist` 文件夹下的文件**上传至服务器
> 

# 2. 推送至Github仓库

## 2.1 创建Github仓库

- 登录Github

[GitHub: Let’s build from here](https://github.com/)

- 创建新的仓库

![2023-8-711:13:12-Untitled.png](https://gitee.com/nianshu2022/image/raw/master/2023-8-711:13:12-Untitled.png)

- 仓库名称：username.github.io

![](https://gitee.com/nianshu2022/image/raw/master/2023-8-711:16:41-Untitled1.png)

## 2.2 Git推送代码

- 用户信息

配置个人的用户名称和电子邮件地址：

```bash
git config --global user.name "runoob"
git config --global user.email test@runoob.com
```

- 远端服务器上的仓库

```bash
**git clone username@host:/path/to/repository**
```

- 查看配置信息

```bash
git config --list
```

- 初始化

```bash
git init
```

- 添加文件到暂存区

```bash
git add .
```

- 将暂存区内容添加到仓库中

```bash
git commit -m "first commit"
```

- 上传代码并合并

```bash
git push
```
