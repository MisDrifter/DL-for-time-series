采用Autoencoder进行预测。将时间序列用线性层映成隐变量，再将隐变量按照分层生成时间序列，最后将不同层的时间序列加权得到最终的结果。