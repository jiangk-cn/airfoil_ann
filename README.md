# airfoil_ann
根据[XFOIL计算得到的CLARK-Y翼型性能数据](https://github.com/jiangk-cn/airfoil_performance)，训练得到一个还不错的神经网络模型，可以用于翼型性能预测


## ANN model
![alt text](./output/ann_model.jpg)

## Benchmark Output
### CNN7
#### CNN7 at Re=1323157
![alt text](output/cnn7_plot_Re1323157_Mach0.10.svg)
![alt text](output/cnn7_plot_Re1323157_Mach0.20.svg)
![alt text](output/cnn7_plot_Re1323157_Mach0.30.svg)
![alt text](output/cnn7_plot_Re1323157_Mach0.40.svg)
![alt text](output/cnn7_plot_Re1323157_Mach0.50.svg)
![alt text](output/cnn7_plot_Re1323157_Mach0.60.svg)
![alt text](output/cnn7_plot_Re1323157_Mach0.70.svg)
#### CNN7 at Re=3686842
![alt text](output/cnn7_plot_Re3686842_Mach0.10.svg)
![alt text](output/cnn7_plot_Re3686842_Mach0.20.svg)
![alt text](output/cnn7_plot_Re3686842_Mach0.30.svg)
![alt text](output/cnn7_plot_Re3686842_Mach0.40.svg)
![alt text](output/cnn7_plot_Re3686842_Mach0.50.svg)
![alt text](output/cnn7_plot_Re3686842_Mach0.60.svg)
![alt text](output/cnn7_plot_Re3686842_Mach0.70.svg)

### CNN8
#### CNN8 at Re=1323157
![alt text](output/cnn8_plot_Re1323157_Mach0.10.svg)
![alt text](output/cnn8_plot_Re1323157_Mach0.20.svg)
![alt text](output/cnn8_plot_Re1323157_Mach0.30.svg)
![alt text](output/cnn8_plot_Re1323157_Mach0.40.svg)
![alt text](output/cnn8_plot_Re1323157_Mach0.50.svg)
![alt text](output/cnn8_plot_Re1323157_Mach0.60.svg)
![alt text](output/cnn8_plot_Re1323157_Mach0.70.svg)
#### CNN8 at Re=3686842
![alt text](output/cnn8_plot_Re3686842_Mach0.10.svg)
![alt text](output/cnn8_plot_Re3686842_Mach0.20.svg)
![alt text](output/cnn8_plot_Re3686842_Mach0.30.svg)
![alt text](output/cnn8_plot_Re3686842_Mach0.40.svg)
![alt text](output/cnn8_plot_Re3686842_Mach0.50.svg)
![alt text](output/cnn8_plot_Re3686842_Mach0.60.svg)
![alt text](output/cnn8_plot_Re3686842_Mach0.70.svg)


## TODO
高马赫数下模型可能会失真，可能是因为高马赫数下的数据量较少，cnn8看起来会更好一些
