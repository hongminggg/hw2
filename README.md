1. 執行server kkk.py by following command line

python kkk.py
2.先建立一個 mbed-os-example-socket

3.把 main.cpp 放入mbed studio ,要把BSP sensor import進來，像是
#include "stm32l475e_iot01_tsensor.h"
#include "stm32l475e_iot01_hsensor.h"
#include "stm32l475e_iot01_psensor.h"
#include "stm32l475e_iot01_magneto.h"
#include "stm32l475e_iot01_gyro.h"
#include "stm32l475e_iot01_accelero.h"
然後接到wifi , run 程式

4.python檔會output 3D ACCELERO 的值和輸出圖表
