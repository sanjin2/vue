#### vue
vue

#### vue-cli安装（官网）
https://cn.vuejs.org/v2/guide/installation.html

#### vue-cli cnpm安装（博客）
https://www.cnblogs.com/wisewrong/p/6255817.html

#### 出现bug的安装指南（解决vue命令不存在问题   使vue init webpack my-project命令正确运行）
https://segmentfault.com/q/1010000008575608
答案：我刚好也遇到这个问题，执行命令 npm config ls 看一下prefix的指向，重新设置下prefix的指向就行了，
指向你需要安装的文件夹下就行了 执行命令为npm config set prefix /home/vue
具体方法：npm config set prefix e:/mayuncode (在根目录下，或者所创建的文件夹下面???)

解决vue命令不存在问题 方法二： 删除E:\mayuncode 下node_modules 重新下载
npm install --global vue-cli
npm install -g vue 

#### 特别注意
1.查看cnpm和vue知否安装成功要在mayuncode文件下分别输入cnpm -v 和vue -V(cmd命令下，gitbash命令下不行)
2.安装vue-cli以及基于webpack的模板的新项目要在（cmd命令下，gitbash命令下不行）
3.本地代码与线上代码同步要在（gitbash命令下，cmd命令下不行）
4.保证符合eslint规范，可以看见正确的端口号
/git/记得merge，不然新建的分支，只会拉取master上面的内容 (git merge index-recommend)


#### 去除本次更改
1.git checkout .
使本地分支与线上分支保持一致







