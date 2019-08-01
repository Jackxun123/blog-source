---
title: uPic image hosting configuration - Github
date: 2019-07-01 21:03:43
toc: true
widgets:
  - type: toc
    position: right
sidebar:
  left:
    sticky: true
  right:
    sticky: true
---

<hr>

![Github configuration](https://gitee.com/gee1k/oss/raw/master/tutorials/github-host.png)

## 📝 Configuration item

- `Owner`: Github username.Example:My Github main page[https://github.com/gee1k](https://github.com/gee1k),my username is`gee1k`
- `Repo`: The name of repo which you want to upload files.Example:my Repo's URL=[https://github.com/gee1k/oss](https://github.com/gee1k/oss),and `oss` is the name of Reop.
- `Branch`: `master` is the name of Branch by default,if you want to upload to others,please establish first.
- `Token`: Github personal access tokens.
- `Domain`: You can't set domian name by default and will use your Github default URL.When you make the Rpeo's function of `pages` available and set up custom domain,you can use your own domain now.
- `Other configuration`: At the end of `Domain`,click "gear" button will pop up detailed configuration of the URL which control file access.You can set up the path of file folders or the naming rule of files.

![扩展配置](https://gitee.com/gee1k/oss/raw/master/tutorials/githug-host-extension.png)

## 🔑 Token - How can I get it

- 1.进入[Github Token 创建页面](https://github.com/settings/tokens/new)
- 2.勾选 `repo` 访问权限。然后滚动页面到底部，点击`Generate token`按钮来生成 token
  ![创建 Token](https://gitee.com/gee1k/oss/raw/master/tutorials/github-token-2.png)
- 3.复制生成好的 Token 值到 uPic token 输入框
  **Attention：this Token shows one time only!Keep it carefully,otherwise you need reset one~ **
  ![Copy Token](https://gitee.com/gee1k/oss/raw/master/tutorials/github-token-3.png)

## 🌝 Almost there!

**保存一下，在菜单栏-图床栏选中刚刚配置好的 Github 图床，上传一张图片试试吧~**
**上传成功后，Github 仓库就会出现你刚上传的文件啦**
**Save and choose the image hosting you configurate before on menu bar——image hosting bar,try to upload a image~**
**After successful upload,file/image will shows on your Github Repo**
![result](https://gitee.com/gee1k/oss/raw/master/tutorials/github-result.png)

<hr>

## Wechat chatting group
  <small> ↓scan the QR code below and join in the group!↓ </small>
	<img src="https://raw.githubusercontent.com/gee1k/oss/master/personal/geee1k.JPG" height="200" style="height:200px">

<hr>
