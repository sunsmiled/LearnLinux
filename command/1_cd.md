# cd
===

切换用户当前工作目录

# 1. 命令格式：

cd [目录名]

# 2. 命令功能：

切换当前目录至dirName

# 3. 实例  

```
cd    进入用户主目录；
cd ~  进入用户主目录；
cd -  返回进入此目录之前所在的目录；
cd ..  返回上级目录（若当前目录为“/“，则执行完后还在“/"；".."为上级目录的意思）；
cd ../..  返回上两级目录；
cd !$  把上个命令的参数作为cd参数使用。
```