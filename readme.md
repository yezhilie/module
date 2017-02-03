## ZTBCMS - 模块列表

- 请在`module/`目录下仿照其他模块的格式新增、修改一个一模块信息
- 打包后静态文件放在`dist/`中可以直接独立房补dist文件


### 开发

```shell
# 安装依赖
$ npm install 

# 构建并预览
$ npm start

```

访问 http://10.1.1.247:3000 即可预览

### 发布到github-pages

```shell 
# 构建并推送到 github-pages 分支
$ make deploy
```

最后线上访问 http://mod.ztbcms.com ，数据更新可能有延时，多刷新2次即可