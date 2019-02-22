# 预测Rossmann未来的销售额

环境：Python3
服务器：IBMX3850，内存32G
操作系统：redhat6.5

库：import pandas as pd
    import numpy as np
    import matplotlib.pyplot as plt
    import pylab as pl
    import seaborn as sns
    from scipy import stats
    from time import time
    import datetime
    import xgboost as xgb
    from sklearn.model_selection import train_test_split

模型训练时间：1927.808652 s到2828.198497 s

kaggle结果：
    Private Score：0.12165
    Public Score：0.11031
