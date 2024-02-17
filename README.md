# SoH-Estimation-Using-GRU-model
Machine Learning based Project 

Difference between SOC and SOH

![image](https://github.com/pooja8748/SoH-Estimation-Using-GRU-model/assets/130728514/872b0634-af77-41e4-a8bf-cdc1dc46492d)

## GRU Model For SOH Estimation

![image](https://github.com/pooja8748/SoH-Estimation-Using-GRU-model/assets/130728514/8f9c184b-c65e-49c1-a092-01f31a2a547f)

The inclusion of the update gate and reset gate in the GRU architecture serves several purposes, such as mitigating the issue of gradient dispersion, enhancing the model’s long- term memory capacity, and reducing computational complexity.
The reset gate (rt) ensures that the information from the previous time step is retained in the candidate hidden state of the current time step. 
On the other hand, the update gate (Zt) quant ifies the likelihood of preserving the information from the previous time step in the current time step. 
The learning rate has a significant role in the learning and generalization performance of the GRU network in the context of battery SOH estimation

![MAE](https://github.com/pooja8748/SoH-Estimation-Using-GRU-model/assets/130728514/3b4b375d-25e0-4e99-8364-1e984a36510d)
![mAp](https://github.com/pooja8748/SoH-Estimation-Using-GRU-model/assets/130728514/f73ebb5f-0004-44ce-973f-535bda966bf7)
![RMSE](https://github.com/pooja8748/SoH-Estimation-Using-GRU-model/assets/130728514/71c1d5f7-1d66-4652-bc8a-172af3732938)
