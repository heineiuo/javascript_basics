# 学习Javascript

## 1. 基本语法


### 资料
* ES5 [http://www.w3school.com.cn/js/index.asp](http://www.w3school.com.cn/js/index.asp)
* ES6
    * [https://babeljs.io/docs/learn-es2015/](https://babeljs.io/docs/learn-es2015/)
    * [http://es6.ruanyifeng.com/](http://es6.ruanyifeng.com/)
* ES6+ [https://github.com](https://github.com) :)

### 对象 Object
### 函数 Function 也是对象
### 类, 实例
    * js自带的: Object, Array, Function, RegExp, Date, String, Number ...
    * 创建
        * 极简构造法
        * prototype
        * class (推荐)

## 2. 开发工具

1. webstorm
    1. 官网 [https://www.jetbrains.com/webstorm/](https://www.jetbrains.com/webstorm/)
    2. **使用最简模式**
    3. 代码跳转
    4. 命令行

2. 命令行
    * macosx
    * windows

3. npm
    * npm config
        * 国内镜像 npm config set registry https://registry.npm.taobao.org
        * 官网镜像 npm config set registry https://registry.npmjs.org
    * npm install
    * npm install -g
    * npm uninstall

4. babel
    * 文档 [https://babeljs.io/](https://babeljs.io/)
    * 在线测试 [https://babeljs.io/repl/](https://babeljs.io/repl/)
    * babel-loader
    * babel-node
    * .bablelrc


5. git

    * 服务器

    * 客户端工具 [http://www.git-scm.org/](http://www.git-scm.org/)

    * 客户端命令
        * git clone
        * git add
        * git commit
        * git push
        * git status
        * git pull --rebase
        * git branch
        * git checkout [BRANCH]
        * git checkout -b [NEW BRANCH]


## 3. node.js

    * 安装 [https://nodejs.org/](https://nodejs.org/)
    * LTS和Current版本的区别
    * 文档 [https://nodejs.org/api/](https://nodejs.org/api/)
    * 模块机制
        * require, module, module.exports
        * import, export

## 4. web

    * 略


## 异步

### callback


### Promise


### async/await
    * 本质: Promise的语法糖
    * try...catch


## 调试

### console.log()

    ** `console.log`接受的是`string`类型的参数 **

### try...catch

    ```
    try {
        throw new Error('EXCEPTION')
    } catch(e){

        // 这里的`e`究竟是什么?
        // 怎么打印出来?

    }

    ```

### 执行时间


### 内存机制


## 单元测试

    * 略