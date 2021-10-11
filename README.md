# shopmanage

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).


1. config/本地服务器配置(整个项目的后台的配置文件)
2. build/ webpack相关代码
        webpack.prod.confic 生产配置
        webpack.dev.confic 开发配置
3. eslintignore eslint排除文件
                如果某个文件不想被检查，可以将文件名写在里面
4. eslintric.js eslint配置文件
              检查代码规范文件，可以自定义规则写在里面

5. package.json 是定义了这个项目的所需要的各种模块(定义指令)
6. editorconfigure 编辑器的配置文件
7. static 生成的静态资源可以放在该文件夹底下
8. .gitignore git管理代码时的排除忽略文件


######代码规范
1. 结尾没有；
2. 必须用全等===
3. 不允许出现未使用的变量
4. 不允许出现一个以上的空行


>自定义指令：指令很长
>npm run 自定义指令名（dev)
>npm run lintfix(自动按照规范修正全部的代码，但是多余的变量不会修正)
>自动打开浏览器 dev:'xxxxx --open'
>关闭eslint build/webpack.base.conf.js 注释掉43行代码



####git版本控制
>git/svn
1.git init -> .git
2.git status
3.git add .
4.git commit -m "zhushi"
5.在代碼託管平台（github)新建遠程倉庫
6.gi tpush