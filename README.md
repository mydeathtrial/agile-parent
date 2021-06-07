# agile-parent

#### 介绍
agile父级工程，通过git子模块方式管理各个agile组件

#### 软件架构
通过git submodule统一管理所有agile系列组件，统一发布版本、分支，便于维护


#### 安装教程

1.  clone本项目idea中会自动拉取子模块代码
2.  手动拉取代码git submodule foreach git pull gitee master

#### 使用说明

1.  推送 git submodule foreach git push
2.  拉取 git submodule foreach git pull
3.  创建分支 git submodule foreach git branch checkout -b <--branch name-->

