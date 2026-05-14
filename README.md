# Quantitative-strategy-backtesting-framework-AI-assisted-factor-research
# This strategy designs an event-driven stock index trading strategy by constructing effective factors such as momentum gap and volatility sentiment ratio.

# 股指事件驱动策略回测

## 策略逻辑
- 动量缺口因子（momentum = feature3 - feature1）
- 波动情绪比（volatility_ratio = feature2/(feature1+1)）
- 做多条件：momentum > 40 且 volatility_ratio > 2
- 做空条件：feature_cross < 200 且 feature1 > 50

## 回测结果（705个交易日）
- 总收益：+65.57%
- 年化收益：19.78%
- 夏普比率：2.11
- 最大回撤：-4.56%

## 文件说明
- 完整回测代码（含数据清洗、信号生成、风控、可视化）
- 策略绩效分析报告

## 备注
这是一个学习性质的项目，主要用于理解因子策略的开发流程。
