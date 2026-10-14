# 电商用户价值分层与精准营销策略

基于 1,000 名用户的公开数据，分析用户价值与行为特征，形成分层运营建议。

**[查看分析报告](分析报告.pdf)｜[查看分析代码](电商用户价值分层与精准营销策略.ipynb)**

- **方法：** 数据检查 → RFM 扩展分层 → 用户画像 → 营销方案测算。
- **产出：** 15 类用户分层，70 名核心用户、89 名候选用户的营销测试方案。

图表保存在 `rfm_analysis/`：数据分布、相关性矩阵、用户雷达图、分层人数、ROI 对比，共 5 张；Notebook 中也保留对应运行结果。

说明：R 使用登录间隔代理；营销回报为假设测算，未计毛利，非实际业绩。

数据：[Kaggle · kartikeybartwal](https://www.kaggle.com/datasets/kartikeybartwal/ecommerce-product-recommendation-collaborative)｜参考：[和鲸项目](https://www.heywhale.com/mw/project/69987eec9bb7c0d2d559ed2e)。基于参考代码复现并整理，完成本地路径与 CSV 读取适配，保留原分析流程及图表。

复现：安装 `requirements.txt` 中的依赖，从本目录启动 Jupyter，打开 Notebook 并运行全部单元格。
