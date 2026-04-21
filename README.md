# 📈 黄金交叉交易策略 (Golden Cross Strategy)

这是一个基于 Python 的量化交易策略实现，用于演示**黄金交叉 (Golden Cross)** 和 **死亡交叉 (Death Cross)** 交易信号。该项目使用 `yfinance` 获取历史市场数据，并利用移动平均线 (SMA) 生成买卖信号。

> ⚠️ **免责声明：** 本项目仅供教育和学习目的使用，不构成任何投资建议。金融市场具有风险，投资需谨慎。

---

### 🛠️ 技术栈

- **Python 3.x**
- **数据分析:** Pandas, NumPy
- **数据源:** yfinance (Yahoo Finance)
- **可视化:** Matplotlib

### 📊 策略逻辑

1.  **获取数据：** 下载指定股票的历史收盘价。
2.  **计算指标：** 计算短期移动平均线 (Short SMA) 和长期移动平均线 (Long SMA)。
3.  **生成信号：**
    -   **黄金交叉 (买入):** 当短期 SMA 上穿长期 SMA 时。
    -   **死亡交叉 (卖出):** 当短期 SMA 下穿长期 SMA 时。
4.  **回测：** 模拟初始资金的组合表现并计算总回报。

### 🚀 快速开始

#### 1. 克隆仓库
```bash
git clone https://github.com/kenson49/Golden-Cross-Strategy.git
cd Golden-Cross-Strategy
