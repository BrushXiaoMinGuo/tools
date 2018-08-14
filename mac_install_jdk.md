1. 下载安装JDK 

  （1）进入官网：Oracle Technology Network > Java > Java SE > Downloads

  （2）点击Java Platform (JDK) 8u121上面的DOWNLOAD，跳转到下载页面

  （3）接受Accept License Agreement，找到相应的Product / File Description对应的文件，点击下载。例如：Mac OS X对应于jdk-8u121-macosx-x64.dmg

  （4）安装

2. 配置环境变量              
（1）确认本机所使用的shell是哪个：zsh/bash
    在命令行中输入echo $SHELL ，
    如果输出/bin/bash则为bash，
    如果输出结果为 /bin/zsh则为zsh。

（2）根据上面不同的结果修改不同的shell配置文件
    若为bash，则打开 ~/.bash_profile，若为zsh打开~/.zshrc。

    在相应的文件末尾添加以下内容，并保存，
        export JAVA_HOME=$(/usr/libexec/java_home)

    在~/目录，命令行执行source命令，source .bash_profile 或 source .zshrc。

（3）执行java -version出现JDK的版本信息即已配置成功。
