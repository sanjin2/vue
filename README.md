# vue
vue

#vue-cli安装（官网）
https://cn.vuejs.org/v2/guide/installation.html

#出现bug的安装指南（解决vue命令不存在问题   使vue init webpack my-project命令正确运行）
https://segmentfault.com/q/1010000008575608
答案：我刚好也遇到这个问题，执行命令 npm config ls 看一下prefix的指向，重新设置下prefix的指向就行了，
指向你需要安装的文件夹下就行了 执行命令为npm config set prefix /home/vue

#vue-cli cnpm安装（博客）
https://www.cnblogs.com/wisewrong/p/6255817.html
