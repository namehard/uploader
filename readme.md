# Upload 插件

HT UI 库的上传插件，通过上传按钮获取上传的文件并生成上传文件列表，并能够通过交互的方式改变列表内部

## 初始化工程(安装环境依赖)

    npm install

## 打包工程

    // 打包 debug 版本，在 build 目录中生成 ht-ui-sidebar-debug.js
    grunt default

    // 打包 release 版，在 release 目录中生成 ht-ui-sidebar.zip
    // 压缩文件内包含类库、API 文档、使用手册
    grunt release

## 目录结构

* build 临时打包目录
* src 源代码目录
* guide 使用手册
* grunt-tasks `grunt` 相关任务
* ide-support 类结构及 `API` 注释
* jsdoc 根据 `ide-support` 生成的文档
* lib 打包类库(`ht.js` 和 `ht-ui.js` 也可以复制到这里，方便运行 `guide` 目录中的例子)

## 基础功能

* 点击按钮上传
* 上传多个文件
* 有上传列表
* 列表文件淡入淡出
* 列表文件可以移除
* 移除文件有弹窗
* 有上传进度条
* 有上传百分比
* 有上传成功显示
* 有上传失败显示
* 有重新上传操作