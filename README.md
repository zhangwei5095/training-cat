training-cat
===================
        该文档说明了如何使用大众点评的CAT这个项目，在training-cat-simple这个模块中简单使用，training-cat-dubbo这个模块中使用了cat-dubbo集成，使用dubbo的隐式传参。



----------


 安装
-------------

### install dubbox

> **Note:**

> - ubunbu15.10(64位系统)安装jdk1.6.0_45，apache-maven-3.2.5，apache-tomcat-7.0.68，git version 2.5.0，mysql 5.6
> - git clone https://github.com/dangdangdotcom/dubbox.git 下载代码
> - mvn clean install -Dmaven.test.skip=true


### install cat
> **Note:**

> - 一定要按照我上述说的规定安装，尤其是jdk，maven
> - git clone https://github.com/dianping/cat.git 下载代码
> - 下载CAT依赖的其他文件，在https://github.com/dianping/cat这个项目下
> - mvn clean install -Dmaven.test.skip=true
> - mvn cat:install


MARKDOWN语法太麻烦，具体代码见项目，我把参考文档放上去一份，我手里有的文档，本来想使用markdown语法写文档呢，还是觉得麻烦，不过基本博客我也不用编写了，为了体现无私奉献精神，我把手头文档都放到了doc文件夹中。还有，spring-boot这个模块要求jdk最低1.7  我的意思是需要安装两个jdk，编译和安装cat时候需要1.6  使用或运行时候可以使用1.7 好啦注意事项就这么多，使用愉快。。。
