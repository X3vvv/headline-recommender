# headline-recommender
Predict the headlines of news of interest to users based on the headlines of the news users read

# How to Use
- 准备joblib格式保存的 模型 和 feature_names 的文件（已提供单独文件），将文件路径传入HeadlineRecommender实例
- 准备新闻标题数据集（已提供在ipynb末尾）
- 传入一个标题字符串，和一个被预测的标题组成的列表，使用predict方法开始预测
- 返回：一个按照和当前标题相关度排序的标题列表
