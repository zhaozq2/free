# 贪吃蛇游戏项目

一个简单的贪吃蛇游戏实现，包含游戏页面和测试用例。

## 项目结构

```
free/
├── index.html          # 贪吃蛇游戏主页面
├── test.html           # 游戏逻辑测试页面
├── vercel.json         # Vercel 部署配置（可选）
└── README.md           # 项目说明文档
```

## 游戏功能

- 🐍 经典贪吃蛇游戏玩法
- 🎮 键盘方向键控制
- 🍎 随机食物生成
- 📊 分数计算和最高分记录
- ⏯️ 开始/暂停/重置功能
- 💾 本地存储最高分

## 测试功能

- ✅ 游戏初始化测试
- ✅ 蛇移动逻辑测试  
- ✅ 食物生成测试
- ✅ 碰撞检测测试
- ✅ 分数计算测试

## 快速开始

### 本地运行

1. 进入项目目录：
   ```bash
   cd free
   ```

2. 启动本地服务器：
   ```bash
   python3 -m http.server 8080
   ```

3. 在浏览器中打开：
   - 游戏：http://localhost:8080/index.html
   - 测试：http://localhost:8080/test.html

### 游戏控制

- **方向键**：控制蛇的移动
- **开始按钮**：开始游戏
- **暂停按钮**：暂停/继续游戏
- **重新开始按钮**：重置游戏

## 技术实现

- 纯 HTML/CSS/JavaScript 实现
- Canvas 绘图
- 本地存储（LocalStorage）
- 响应式设计

## 部署

### Vercel 部署（可选）

项目包含 `vercel.json` 配置文件，可一键部署到 Vercel：

```bash
# 安装 Vercel CLI
npm install -g vercel

# 部署
vercel --prod
```

## 测试说明

测试页面 (`test.html`) 包含 5 个核心逻辑测试用例，确保游戏基本功能正常。

## 许可证

MIT License