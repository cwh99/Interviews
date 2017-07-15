# Interviews
###HTML5
#####与html的一些区别
``` 
DTD声明：<!DOCTYPE html>
```
#####git的一些命令
```
初始化：git init
删除文件：rm -rf 文件名
清除本地文件夹下的Git文件:find . -name ".git" | xargs rm -Rf
github配置SSH：http://www.jianshu.com/p/49ecf53a6f3b
```
######前端项目构建
``` 
http://www.jianshu.com/p/23cc95b5fce8

1、项目开发目录设计   project:
    - components   存放模块资源，模块资源分为项目模块和公共模块，希望能从component安装一些公共组件到项目中
       - 分成两个模块  -- component_modules   存放外部模块资源
                     -- components          存放项目模块资源
    - pages        存放页面资源
    - static       存放非模块化资源
    
    调整规范：
      project：
          - component_modules 存放外部模块资源
          - components 存放项目模块资源
          - views 存放页面资源
          - public 存放非模块化资源
          
     最终调整为：
          - component_modules 存放外部模块资源
          - components 存放项目模块资源
          - views 存放页面以及非模块化资源
          
 2、部署目录设计
    一个完整的部署结果的目录结构：
       release
              -- public   
                --项目名
                    -1.0.0    1.0.0版本的静态资源构建到这里
                    -1.0.1    1.0.1版本的静态资源构建到这里
              -- view
                    -1.0.0     1.0.0版本的后端模板构建到这里
                    -1.0.1     1.0.1版本的后端模板构建到这里
                    
     由于                   还要部署一些被第三方使用的模块
        release
              --public
                -component_modules    模块化资源部署到这个目录
                  -module_a
                    -1.0.0
                      -module_a.js
                      -module_a.css
                      -module_a.png
                    -1.0.1
                    -1.0.2
                    ...
                 -项目名
                    -1.0.0  1.0.0版本的静态资源
                    -1.0.1  1.0.1版本的静态资源
                    -1.0.2  1.0.2版本的静态资源
                    ···
              --views
                -项目名
                    -1.0.0     1.0.0版本的后端模板构建到这里
                    -1.0.1     1.0.1版本的后端模板构建到这里
 #####     http://www.jianshu.com/p/6cb49271cd2a
 #####    handlebars         
 ```
            是JS的一个语义模板库
 ```
 ##本地测试环境搭建  服务器nginx
 ```
 http://www.jianshu.com/p/630e2e1ca57f
 nginx安装和配置：
    http://www.jianshu.com/p/630e2e1ca57f
 ```
                    
                    
                    
                    
                    
                    
                    
                    
                    
                    
                    
                    
                    
                    
                    
                    
                    
                    
                    
                    
```




















