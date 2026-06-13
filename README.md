# ThinkPHP 电商套件

一个基于 ThinkPHP 8 的电商系统基础框架。

## 技术栈
- ThinkPHP 8
- PHP 8.1
- MySQL 8.0
- Redis（缓存/购物车 Session）
- Vue 3 + uniapp（前端）

## 本地运行
### 后端
1. `composer install`
2. 配置 `.env` 数据库信息
3. 确保 Redis 服务已启动
4. 访问 `http://tp.local`

### 前端
1. 进入 `frontend` 目录
2. `npm install`
3. `npm run dev:h5`

## 演示地址
https://shop.yourdomain.com（待部署）

## 项目状态
- ✅ 环境搭建完成
- ⬜ 商品管理模块
- ⬜ 购物车