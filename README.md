- $ npm install -g create-react-app                     //安装React官方脚手架
- create-react-app imooc                                //创建1个应用：imooc
- cd imooc                                              //切换到应用：imooc

- $ npm install --save redux react-redux redux-thunk    //redux相当于本地数据库，react-redux帮助完成数据订阅，redux-thunk可放置实现异步action
  $ npm install --save-dev redux-logger                 //redux-logger是redux的日志中间件

- $ npm run eject                                       //弹出配置文件，可自定义配置webpack

- 将本地一个项目传到github上：
  - cd immoc
  - git init                                                                       //初始化本地仓库
  - git add .(记得有个点哦，并且和add之间有空格)                                       //添加当前工作目录文件到index，添加管理
  - git status （若出现了很多红色文件，那么就需要再次进行2的步骤，git add .直到没有问题。） //查看一下当前目录所有没有被git管理的文件以及被git管理并且被修改但是还没有提交的文件
  - git commit -m "xxx" (xxx就是你提交文件时候的备注 )                                //提交文件，把本地仓库暂存区的文件提交到本地仓库
  - git remote add origin https://github.com/bendan321/nihao.git                   //关联远程仓库，其中origin后跟的是，远程仓库的别名
  - git push -u origin master                                                      //push文件