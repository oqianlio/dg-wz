# 游戏代练交流平台

一个基于React + TypeScript + Vite开发的游戏代练交流平台，为玩家提供安全、可靠、高效的游戏代练服务。

## 功能特点

- 多游戏支持：英雄联盟、王者荣耀、和平精英等多款热门游戏
- 多样服务类型：排位代练、组队开黑、装备代刷等
- 安全保障：
  - 违禁词检测
  - SQL注入防护
  - XSS攻击防护
  - 用户隐私保护
- 用户友好的界面设计
- 完善的订单管理系统

## 技术栈

- React 19
- TypeScript
- Vite 6
- ESLint

## 快速开始

### 环境要求

#### 本地开发环境
- Node.js >= 18.0.0
- npm >= 9.0.0

#### Docker部署环境
- Docker >= 20.10.0
- Docker Compose >= 2.0.0

### 安装

```bash
# 克隆项目
git clone https://github.com/yourusername/dg-wz.git

# 进入项目目录
cd dg-wz

# 安装依赖
npm install
```

### 开发

```bash
# 启动开发服务器
npm run dev
```

### 构建

```bash
# 构建生产版本
npm run build
```

## 项目结构

```
src/
├── assets/        # 静态资源
├── components/    # 组件
├── contexts/      # Context
├── types/         # TypeScript类型定义
├── utils/         # 工具函数
├── App.tsx        # 应用入口
└── main.tsx       # 主入口
```

## 贡献指南

1. Fork 本仓库
2. 创建你的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交你的改动 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启一个 Pull Request

### 代码规范

- 遵循 ESLint 配置的代码规范
- 组件使用 TypeScript 编写
- 保持代码简洁清晰，添加必要的注释
- 提交信息要清晰明了

## 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情

## 联系我们

如果你有任何问题或建议，欢迎提出 Issue 或 Pull Request。

---

感谢使用游戏代练交流平台！
