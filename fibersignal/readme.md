# oil pipeline abnormal events detection and automatic recognization
  ## the signals sampling rate is 750 ps, four seconds as a block in 3000 bytes, like:
## ------------------------------------|--------------------------------|----------------------------
![GitHub Logo](https://github.com/choybeen/deeplearn/blob/main/fibersignal/imgs/download%20(3).png?raw=true)|![GitHub Logo](https://github.com/choybeen/deeplearn/blob/main/fibersignal/imgs/download%20(4).png?raw=true)
* read data from files of different type, and create one-hot labels, then reshuffle those data in random order by index, divide data into training and test groups 
##create neural network:

![GitHub Logo](https://github.com/choybeen/deeplearn/blob/main/fibersignal/imgs/Capture.JPG?raw=true)
* add two dropout layers avoiding overfitting 

## the result:
![GitHub Logo](https://github.com/choybeen/deeplearn/blob/main/fibersignal/imgs/download.png?raw=true)
![GitHub Logo](https://github.com/choybeen/deeplearn/blob/main/fibersignal/imgs/download%20(1).png?raw=true)

## for application, need to communicate with remote sensors to get data for recognization in real-time
### TCPClientLabView
   connect socket to transmit data from remote machine
### TCPServerLabView
   or as a server, listen requests from remote machine
