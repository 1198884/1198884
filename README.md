# Weekly Report Application

一个用于管理周报的Vue 3前端应用程序，使用本地存储保存数据。

## 项目结构

这个项目是一个纯前端应用：
- Vue 3 + TypeScript + Vite

## 运行项目

### 前提条件
- Node.js 16+ 
- npm或yarn

### 安装和运行
```bash
# 安装依赖
npm install

# 启动开发服务器
npm run dev
```

前端应用将在以下地址可用: http://localhost:5173/

## 数据存储

本应用使用浏览器的localStorage存储数据，不需要后端服务器。数据将保存在浏览器中，刷新页面后数据仍然存在，但是清除浏览器数据或使用不同浏览器会导致数据丢失。

## 功能特性

- 创建、查看、编辑和删除周报
- 按用户名和日期范围筛选报告
- 响应式设计，适应不同屏幕尺寸
