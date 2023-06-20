# Home-based-care Privacy (HbcP)

## 面向居家养老的云边协同-联邦深度学习系统

### 背景

社会老龄化趋势下，独居老人越来越多。独居老人面临诸多意外风险，安全防护缺失。

### 应用场景

系统通过边端设备，实时监测老人体征、情绪等各项指标，建立“预警、预测、预防”体系，7×24发现和响应体征、环境、行为异常。

### 解决方案：CB-FLDL

在端云场景中，CB-FLDL算法被切割为4个子网络，前级子网络Embedding和末级子网络Head部署在参与方A边端网络内，Backbone、Neck子网络部署在参与方B云端网格域内。参与方A和B交换的是特征张量和梯度张量，在交换过程中采用隐私安全机制和加密算法进行处理。