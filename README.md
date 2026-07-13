
My Quant Trading Scripts (个人量化交易脚本库)
本仓库包含了我日常交易与研究中编写的部分 Python 脚本，主要涉及加密货币市场的数据获取、微观结构分析及策略回测。

目录结构
binance_funding_rate_monitor.py: 基于 Binance REST API，实时获取并分析全网资金费率，捕捉期现套利/资金费率套利机会。利用 Pandas 进行数据清洗与排序。
backtrader_sma_atr_strategy.py: 基于 Backtrader 框架构建的趋势跟踪策略。亮点：引入了 ATR（真实波动幅度）指标，严格执行凯利公式与固定风险比例，实现单笔交易风险动态调整（仓位管理）。
