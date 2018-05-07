# vue
vue

#vue-cli安装（官网）
https://cn.vuejs.org/v2/guide/installation.html

#出现bug的安装指南（解决vue命令不存在问题   使vue init webpack my-project命令正确运行）
https://segmentfault.com/q/1010000008575608
答案：我刚好也遇到这个问题，执行命令 npm config ls 看一下prefix的指向，重新设置下prefix的指向就行了，
指向你需要安装的文件夹下就行了 执行命令为npm config set prefix /home/vue
具体方法：npm config set prefix e:/mayuncode (在根目录下，或者所创建的文件夹下面???)
#特别注意
1.查看cnpm和vue知否安装成功要在mayuncode文件下分别输入cnpm -v 和vue -V(cmd命令下，gitbash命令下不行)
2.安装vue-cli以及基于webpack的模板的新项目要在（cmd命令下，gitbash命令下不行）
3.本地代码与线上代码同步要在（gitbash命令下，cmd命令下不行）

# 本地代码与线上代码同步的git命令
git status(检查文件情况)
1.git add .
2.git commit -m 'project initialized'
3.git push


#vue-cli cnpm安装（博客）
https://www.cnblogs.com/wisewrong/p/6255817.html


