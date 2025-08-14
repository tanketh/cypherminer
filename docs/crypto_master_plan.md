# 加密矿工总体计划（Crypto Master Plan）

## 目标
- 建立个人可控的加密资产获取与管理体系
- 从技术、市场、数据三个维度构建持续产出的能力
- 形成可验证的执行记录与版本历史

## 阶段规划
### Day 1：环境与工具
- 安装 Homebrew 并配置镜像
- 安装 Git、Node.js、Python3
- 熟悉终端基本命令（cd, ls, pwd, mkdir, rm, nano 等）
- 配置 GitHub 仓库（HTTPS / SSH）
- 首次推送测试（README.md）

### Day 2：安全与工作流
- 创建并替换 GitHub Token（PAT）
- 解决 HTTP/2 framing layer 问题（切换 HTTP/1.1）
- 清理测试文件
- 创建一键推送脚本 `gitpush.sh`

### Day 3：项目骨架搭建
- 创建目录结构：docs, scripts, data, config
- 放置第一个占位脚本 `scripts/fetch_data.py`
- 初始化项目计划文件 `docs/plan.md`

### Day 4：数据抓取基础
- 安装 Python 包管理工具（uv/pipx）
- 选择数据源（CoinGecko API / 交易所 / 区块链浏览器）
- 编写并运行第一个数据抓取脚本

### Day 5~7：数据处理与分析
- 存储数据到本地/数据库
- 使用 Pandas 处理数据
- 绘制价格走势、交易量等可视化图表

### Day 8+：自动化与扩展
- 定时任务（cron/job）
- 扩展数据源与脚本
- 集成到投资决策与执行流程

## 长期方向
- 多链数据采集
- 智能合约交互
- 策略回测与自动交易
