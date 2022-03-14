"# lab5-fat_filesystem-chien-yu-hsu" 
# Embedded_OS_Lab5_NE6091116
## Overview
**1.Implement printf**

修改printf.h使得專案可以直接使用printf輸出結果到console(uart tx)

**2.Read and write file by multi-task**

修改main.c中的task1 and task2，一個task負責寫入，一個task負責讀取。

**3.Playback the wav file to DAC**

在task3中加入函式，使wav檔可以順利播放。

## Task1

使用Q1、Q2兩個semaphore來達成互斥。

<img width="381" alt="lab5task1" src="https://user-images.githubusercontent.com/80887185/124144581-ae6db980-dabe-11eb-98cc-1dc652266167.PNG">

## Task2

<img width="382" alt="lab5 task2" src="https://user-images.githubusercontent.com/80887185/124144625-b6c5f480-dabe-11eb-8571-d5e71dba254b.PNG">

## Task3

<img width="274" alt="lab5 task3" src="https://user-images.githubusercontent.com/80887185/124144657-be859900-dabe-11eb-938e-a47118799b05.PNG">
"# FreeRTOS_Lab5" 
