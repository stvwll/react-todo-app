# react-todo-app

Quick Start
1. 地址：https://github.com/dwyl/learn-nightwatch

### 配置Todo-list 的环境

Cd react-todo-app

Npm install nightwatch –save-dev

Npm install selenium-server chromedriver –save-dev

创建文件 nightwatch.conf.BASIC.js

复制粘贴文件的内容：https://github.com/dwyl/learnnightwatch/blob/master/nightwatch.conf.BASIC.js

Run config file ： node nightwatch.conf.BASIC.js

修改pakeage.json 中的Script： "scripts": { "e2e": "nightwatch --confignightwatch.conf.BASIC.js" }

创建文件夹 /test/e2e 下的文件内容 ,写测试(所给的只是一个nightwatch的测试demo，不必深究，还是采用cypress为to-do-app写e2e测试)


### Todo-list 的e2e 测试
Run todo-list demo

1. clone https://github.com/MHwishes/react-todo-list.git

2. 按照 readme.md 把demo run 起来

Demo 地址：
https://github.com/MHwishes/todo-list-e2e-nightwatch
