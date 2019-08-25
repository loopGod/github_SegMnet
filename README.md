# github_SegMnet

### MySegLSTMCRF MySegCNNCRF   这里面的CRF是py文件手写进去的
### LSTM_CRFofKeras CNN_CRFofKeras  这里面的CRF是keras-contril里面的
### 上面两个训练完都不能转成pd格式，无法识别CRF层
### 所以要把CRF分割开来，如下文件：
### MySegCNN_defCRF这个先训练CNN分类，然后加了一个转移矩阵来分词
### h5_2_pd是用来转pd的
