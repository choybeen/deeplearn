# deeplearn

# oil pipeline abnormal events detection and automatic recognization
  
- [x]Model: "sequential_7"|
------------------|----------------------------|-----------------
_________________________________________________________________
Layer (type)       |          Output Shape     |         Param #   
=================================================================
conv1d_19 (Conv1D) |          (None, 2996, 128)|         768       
_________________________________________________________________
max_pooling1d_13 (MaxPooling (None, 998, 128)  |        0         
_________________________________________________________________
conv1d_20 (Conv1D) |          (None, 994, 64)  |         41024     
_________________________________________________________________
max_pooling1d_14 (MaxPooling (None, 331, 64)   |        0         
_________________________________________________________________
dropout_8 (Dropout)|          (None, 331, 64)  |         0         
_________________________________________________________________
conv1d_21 (Conv1D) |          (None, 327, 32)  |         10272     
_________________________________________________________________
global_max_pooling1d_7 (Glob (None, 32)        |        0         
_________________________________________________________________
dropout_9 (Dropout)|          (None, 32)       |         0         
_________________________________________________________________
dense_7 (Dense)    |          (None, 7)        |         231       
=================================================================
Total params: 52,295
Trainable params: 52,295
Non-trainable params: 0

![GitHub Logo](https://github.com/choybeen/deeplearn/blob/main/fibersignal/imgs/download.png?raw=true)
![GitHub Logo](https://github.com/choybeen/deeplearn/blob/main/fibersignal/imgs/download%20(1).png?raw=true)


