# airfoil_ann
根据XFOIL计算得到的CLARK-Y翼型性能数据，训练得到一个还不错的神经网络模型，可以用于翼型性能预测

## CNN model
Model: "sequential"
_________________________________________________________________
 Layer (type)                Output Shape              Param #   
=================================================================
 dense (Dense)               (None, 128)               512       
                                                                 
 dense_1 (Dense)             (None, 64)                8256      
                                                                 
 dense_2 (Dense)             (None, 32)                2080      
                                                                 
 dense_3 (Dense)             (None, 16)                528       
                                                                 
 dense_4 (Dense)             (None, 8)                 136       
                                                                 
 dense_5 (Dense)             (None, 3)                 27        
                                                                 
=================================================================
Total params: 11,539
Trainable params: 11,539
Non-trainable params: 0
_________________________________________________________________

## Benchmark Output
![alt text](plot_Re2636315_Mach0.10.svg)
![alt text](plot_Re2636315_Mach0.20.svg)
![alt text](plot_Re2636315_Mach0.30.svg)
![alt text](plot_Re2636315_Mach0.40.svg)
![alt text](plot_Re2636315_Mach0.50.svg)
![alt text](plot_Re2636315_Mach0.60.svg)
![alt text](plot_Re2636315_Mach0.70.svg)
