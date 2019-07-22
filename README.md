# cicd_install_blog
该项目用于博客的cicd平台搭建
https://www.jianshu.com/p/4237ed1277ce

三、执行安装    mkdir /home/jenkins    chmod +777 /home/jenkins    cd ~    https://github.com/hqh546020152/cicd_install_blog.git    cd cicd_install_blog    vi +53 docker-compose-gitlab.yml    该53行的IP修改为本机IP    部署Jenkins        docker-compose -f "docker-compose-jenkins.yml" up -d         部署gitlab(预计5分钟完成)        docker-compose -f "docker-compose-gitlab.yml" up -d    验证：        访问Jenkins：http://HOST:8080





        访问GitLab：http://HOST:10080

作者：天夭夭
链接：https://www.jianshu.com/p/4237ed1277ce
来源：简书
简书著作权归作者所有，任何形式的转载都请联系作者获得授权并注明出处。
