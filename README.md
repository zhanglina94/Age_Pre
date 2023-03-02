# Age_Pre 🚀
利用不同的模型进行年龄预测，并优化网络


### Dataset

##### 1.自己的数据集
数据集样本不均衡，且对年龄分为不同类
  - 8 kind of ages
  - 79 kind of ages
 
##### 2.UTKFace


### Model
- STAP:利用swin transformer 进行年龄预测
- CNAP:利用ConvNeXt 进行年龄预测
- RNAP:利用ResNet34 进行年龄预测(17/1/2023)
  - 修改CELoss->FocalLoss(2/22/2023)
- RNFT:利用ResNet50 进行年龄预测，并添加注意力机制CBAM。

### Train
Traindata:6670images valdata:702images
