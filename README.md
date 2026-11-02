# TypeScript 贪吃蛇


## 主要功能

- 方向键控制蛇的移动
- 随机生成食物，吃到食物后增长身体
- 分数累计、等级提升与移动加速
- 撞墙和撞到自身时结束游戏

## 本地运行

需要先安装 Node.js 和 npm。在项目目录执行：

```bash
npm ci
npm start
```

生成打包文件：

```bash
npm run build
```

## 项目结构

- `src/modules/Snake.ts`：蛇的移动、增长与碰撞检查
- `src/modules/Food.ts`：食物位置管理
- `src/modules/ScorePanel.ts`：分数和等级管理
- `src/modules/GameControl.ts`：键盘事件与游戏流程控制
- `src/style/index.less`：页面样式
- `src/index.ts`：程序入口

## 学习说明

本项目用于 TypeScript 和面向对象编程练习，参考尚硅谷 TypeScript 教程，记录了类与对象、构造函数、访问器、事件回调及异常处理等知识的实践过程。