# 在线商城系统

Web期末大作业前端项目仓库
<a href="http://119.23.46.102:8081/home" target="blank">查看Demo</a>

两个分支：

- dev：开发分支，一个功能开发完后，合并到 master 分支，部署上线
- master：稳定分支，部署的分支

## 关于

期末大作业前端，一个在线商城平台。

![a](https://cdn.jsdelivr.net/gh/Hacker-C/Picture-Bed@main/javaweb/home.4cevksvgsy60.webp)



<p align="right">(<a href="#top">back to top</a>)</p>



## 技术栈

项目前端所使用的技术栈。

![前端技术栈](https://cdn.jsdelivr.net/gh/Hacker-C/Picture-Bed@main/javaweb/前端技术栈.5e37vlgqut00.webp)

<p align="right">(<a href="#top">back to top</a>)</p>

## 基本环境

项目开发环境。

- Vue: `v2.1.6`
- vue/cli: `v4.5.15`
- vue-router: `v3.2.0`
* Node.js: `v16.13.0`
* Echarts:  `v5.2.2`
* ElementUI: `v2.4.5`
* 浏览器：支持 `CSS3` 和 `ES6/ES7+` 的浏览器

## 本地运行

1. git clone

   ```git
   git clone git@github.com:Hacker-C/Mall-FrontEnd.git mall
   ```

2. npm install

   ```npm
   npm install
   ```

3. start

   ```npm
   npm run dev
   ```

4. build

   ```
   npm run build
   ```

## 功能实现

### 顾客模块

- [x] 登陆网站
- [x] 浏览网站内容
- [x] 注册成此网站会员
    - [x] 编辑自己基本信息
    - [x] 修改密码
    - [x] 重置账户金额
- [x] 将选中的商品加入购物车
    - [x] 对购物车进行管理
      - [x] 删除购物车中商品
      - [x] 将购物车商品一起购买
- [x] 购买商品（管理订单）
    - [x] 提交订单
    - [x] 对订单进行付款
    - [x] 删除订单
    - [x] 取消订单
- [x] 对购买后的商品进行评价
    - [x] 评价商品
    - [x] 删除自己的评论
- [x] 收藏夹
    - [x] 添加商品到收藏集
    - [x] 删除收藏夹中内容

<p align="right">(<a href="#top">back to top</a>)</p>

### 商家模块

- [x] 注册申请开店
- [x] 对自己的店进行管理
  - [x] 上传商品图片
  - [x] 对商品进行介绍
  - [x] 编辑商品价格、剩余量、折扣等基本信息
- [x] 统计店内商品销售情况
  - [x] 查看总体收入情况
  - [x] 查看各类商品销售量、总收入
- [x] 管理订单
  - [x] 查看订单信息
    - [x] 查看订单总金额、下单时间
    - [x] 对订单中的商品进行发货操作
  - [x] 编辑订单状态
    - [x] 取消订单
    - [x] 对订单进行发货

### 管理员模块

- [x] 对商家进行管理
  - [x] 查看、删除该商家下的所有商品
  - [x] 编辑商家和店铺的相关信息
- [x] 对系统进行维护管理
- [x] 管理所有用户
  - [x] 管理顾客、商家基本信息
  - [x] 重置顾客、商家登录密码
  - [x] 拉黑顾客、商家（拉黑后无法登录）
  - [x] 管理用户身份角色
    例如将某顾客身份改为商家，活着将其升级为管理员
  - [x] 查看所有用户组成（管理员、顾客、商家）
- [x] 管理系统
  - [x] 管理首页限时折扣倒计时时间
  - [x] 管理首页商品分类功能
    - [x] 编辑商品分类名称
    - [x] 删除商品分类
    - [x] 添加新的商品分类
  - [x] 管理系统的公告
    - [x] 编辑公告内容





