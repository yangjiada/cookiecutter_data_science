{{cookiecutter.project_name}}
==============================

{{cookiecutter.description}}

项目结构
------------

    ├── LICENSE
    ├── Makefile           <- 使用命令make data或make train生成文件
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- 来自第三方的数据。
    │   ├── interim        <- 已转换的中间数据。
    │   ├── processed      <- 最后，用于建模的规范数据集。
    │   └── raw            <- 原始的、不可变的数据转储。
    │
    ├── docs               <- 默认的Sphinx项目;详情请参阅sphinx-doc.org
    │
    ├── models             <- 训练和序列化的模型、模型预测或模型总结
    │
    ├── notebooks          <- Jupyter笔记本。命名约定是一个数字(用于排序)，
    │                         创作者的首字母，以及用“-”分隔的简短描述，例如:
    │                         “1.0 -jqp-initial-data-exploration”。
    │
    ├── references         <- 数据字典、手册和所有其他解释性材料。
    │
    ├── reports            <- 生成分析如HTML, PDF, LaTeX等。
    │   └── figures        <- 生成用于报告的图形和数字
    │
    ├── requirements.txt   <- 再现分析环境的需求文件，例如。
    │                         使用' pip freeze > requirements.txt '生成
    │
    ├── setup.py           <- 使项目PIP可安装(PIP install -e .)，以便SRC可以导入
    ├── src                <- 在这个项目中使用的源代码。
    │   ├── __init__.py    <- 使src成为Python模块
    │   │
    │   ├── data           <- 用于下载或生成数据的脚本
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- 将原始数据转换为建模特性的脚本
    │   │   └── build_features.py
    │   │
    │   ├── models         <- 脚本训练模型，然后使用训练模型进行预测
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- 用于创建探索性和面向结果的可视化的脚本
    │       └── visualize.py
    │
    └── tox.ini            <- 毒理文件与设置运行毒理;看到tox.readthedocs.io

