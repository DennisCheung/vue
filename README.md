# vue
learn vue about some my notes
<br>
npm install -g vue-cli
vue init <template-name> <project-name>	vue-cli脚手架的使用
ps:vue init webpack my-project
npm install     安装的依赖代码库
npm run dev		项目运行
npm install --production	安装生产环境

# 项目文件介绍——一级目录
build目录、cofig目录	webpack配置相关
node_modules	npm install 安装的依赖代码库
src				存放项目源码，开发的所有代码都在此
static			存放第三方静态资源
——.gitkeep		此文件代表目录为空也提交到git代码仓库（通常一个目录为空，.git会忽略该目录，不提交到代码仓库）
.babelrc		是babel的编译的配置，项目通常是es6代码，需要babel编译
.editorconfig	编辑器的配置
.eslintignore	忽略语法检查的目录文件
.eslintrc.js	eslint的配置文件
.gitignore		忽略的文件以及目录，不提交到git代码仓库
index.html		入口文件
package.json	项目的配置文件：一般用来描述一个项目，vue-cli填的一些信息；script可以配置一些脚本，执行命令；dependencies项目的依赖；devDependcies编译的依赖，这些代码在打包上线后是不存在的

webstorm的自动格式化  control + alt + L 
