# chinese-poetry-data-mining
基于85万首中国古诗词数据，构建了一套完整的文本挖掘与分析流程，涵盖数据清洗、Jieba分词、SVM多分类、朝代×题材关联度分析（偏好指数Lift + 标准化残差）及可视化呈现。旨在从数据科学视角探究诗词题材演变与历史变迁之间的量化关联。
## 数据来源
本分析使用的原始古诗词数据来自 GitHub 开源项目：[Werneror/Poetry](https://github.com/Werneror/Poetry)
该数据集收录了从先秦到现代的共计 85 万余首古诗词，按朝代分别存储在 CSV 文件中。
