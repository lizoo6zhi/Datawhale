# Datawhale组队学习之数据挖掘项目实战

<b>组队学习说明：</b> 应用机器学习算法，完整地走完一个数据挖掘项目流程

<b>任务路线：</b> 数据分析→特征工程→模型构建→模型评估→模型调优→模型融合


# Task1：数据分析（2天）

<b>任务1：</b>对数据进行探索和分析

<b>说明：</b> 这份数据集是金融数据（非原始数据，已经处理过了），我们要做的是预测贷款用户是否会逾期。表格中 "status" 是结果标签：0表示未逾期，1表示逾期。

<b></b>要求：</b> 数据切分方式 - 三七分，其中测试集30%，训练集70%，随机种子设置为2018

<b>具体任务：</b>
- 数据类型的分析
- 无关特征删除
-  数据类型转换
-  缺失值处理
-  ……以及你能想到和借鉴的数据分析处理

# Task2：特征选择
<b>具体任务：</b>
- 特征衍生
- 特征挑选：分别用IV值和随机森林等进行特征选择
- ……以及你能想到特征工程处理

# Task3：跑模型
<b>具体任务：</b>
- 用逻辑回归、svm和决策树；随机森林和XGBoost进行模型构建，评分方式任意，如准确率等。（不需要考虑模型调参）

# Task4：模型评估
<b>具体任务：</b>
- 记录5个模型（逻辑回归、SVM、决策树、随机森林、XGBoost）关于accuracy、precision，recall和F1-score、auc值的评分表格，并画出ROC曲线

# Task5：调参
<b>具体任务：</b>
- 使用网格搜索法对5个模型（逻辑回归、SVM、决策树、随机森林、XGBoost）进行调优（调参时采用五折交叉验证的方式），并进行模型评估

# Task6：模型融合
<b>具体任务：</b>
- 模型融合方式任意，并结合Task5给出你的最优结果
- 例如Stacking融合，用你目前评分最高的模型作为基准模型，和其他模型进行stacking融合，得到最终模型及评分结果


