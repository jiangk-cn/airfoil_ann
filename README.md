# airfoil_ann
根据[XFOIL计算得到的CLARK-Y翼型性能数据](https://github.com/jiangk-cn/airfoil_performance)，训练得到一个还不错的神经网络模型，可以用于翼型性能预测


## ANN model
![alt text](output/netron-cnn8.png)

## Benchmark Output
### Reynolds Number = 48542
![alt text](output/MaxAbsScaler_model_re_48542_mach_0.00.svg)
![alt text](output/MaxAbsScaler_model_re_48542_mach_0.10.svg)
![alt text](output/MaxAbsScaler_model_re_48542_mach_0.20.svg)
![alt text](output/MaxAbsScaler_model_re_48542_mach_0.30.svg)
![alt text](output/MaxAbsScaler_model_re_48542_mach_0.40.svg)
![alt text](output/MaxAbsScaler_model_re_48542_mach_0.50.svg)
![alt text](output/MaxAbsScaler_model_re_48542_mach_0.60.svg)
![alt text](output/MaxAbsScaler_model_re_48542_mach_0.70.svg)

### Reynolds Number = 775862
![alt text](output/MaxAbsScaler_model_re_775862_mach_0.00.svg)
![alt text](output/MaxAbsScaler_model_re_775862_mach_0.10.svg)
![alt text](output/MaxAbsScaler_model_re_775862_mach_0.20.svg)
![alt text](output/MaxAbsScaler_model_re_775862_mach_0.30.svg)
![alt text](output/MaxAbsScaler_model_re_775862_mach_0.40.svg)
![alt text](output/MaxAbsScaler_model_re_775862_mach_0.50.svg)
![alt text](output/MaxAbsScaler_model_re_775862_mach_0.60.svg)
![alt text](output/MaxAbsScaler_model_re_775862_mach_0.70.svg)

## TODO
根据与数据库中没有的0.0马赫数据库的对比，还存在一些点的预测效果不好，但是目前的模型基本可用，用法可以参考[load_ann_model.ipynb](load_ann_model.ipynb)
![alt text](benchmark/benchmark_model_re_50000_mach_0.00.svg)