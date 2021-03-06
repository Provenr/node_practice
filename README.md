# node_practice


## 如何开始做题

```bash
# 首先clone代码 或 fork代码后再开始
# 切换答题分支
git checkout -b answer

# 全局安装jest
npm i jest -g

# 启动测试程序开始做题
# 例如： 做第一题

# 启动单元测试
jest ex01 -watch

# 直到完成测试案例
```


## 如何获取答案
- 答案为加密状态保存 需要秘钥
- 首先添加根目录下.env文件
```
KEY=XXXX(秘钥请联系作者)
```
- 执行
```bash
npm run encrypt
```
## 具体题目
### 01 自动生成代码模板
编写一个自动生成路由配置的方法 
要求:
- 不可以使用模板库
- 可以使用fs函数的readdirSync
- 可以使用ES6的模板字符串组装
- 使用模板字符串的迭代方法可以大幅较少代码行数

### 02 洋葱圈中间件实现原理
编写一个compose函数实现洋葱圈功能

### 03 文件流接收转化JSON
为了更好的理解bodyparser原理，编写一个解析JSON文件流的函数
- 提供一个异步函数
- 使用fs异步函数
- 需要Promise封装

### 04 sequelize + sqllite3 实现多对多更新

### 05 eventloop实现原理
### 06 jwt原理解析 反篡改 过期检测
### 07 loader实现原理 自动加载模块
### 08 企业级实现 统一异常处理
### 09 TS装饰器 装饰器原理解析
### 10 Cluster 思维脑图
