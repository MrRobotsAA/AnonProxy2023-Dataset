# AnonProxy2023 
This is an anonymous proxy traffic dataset in Paper 《ProxyKiller: A Robust Graph Neural Network-Based Model for Anonymous Proxy Traffic Classification》. 

（1）The download links for all three datasets are as follows.

Link: 

https://pan.baidu.com/s/14zA-zdT3SOkeyuAOPHk-jQ 

Access Code: tpnd.

Specifically, the original link for the LFETT2021 dataset is as follows. 

https://github.com/HoneyPotter-Gzy/LFETT2021-dataset

（2）Model Code Usage Instructions： First, run DatasetGenerator.py to generate the dataset and then run ProxyKiller_Model.py for model training and testing.

（3）The detailed features extracted in the paper are shown in the table below. 

| ID      | Feature Name                | Directions            | Statistical Features         | Category        |
| ------- | --------------------------- | --------------------- | ---------------------------- | --------------- |
| 1       | Protocol                    | -                     | -                            | Content Features|
| 2       | IP Version                  | -                     | -                            | Content Features|
| 3-4     | Duration (ms)               | Bidirectional, Single | -                            | Temporal Features|
| 5-14    | Packets                     | Bidirectional, Single | Origin, Min, Max, Mean, Stddev| Spatial Features| 
| 15-16   | Bytes Size                  | Bidirectional, Single | -                            | Spatial Features| 
| 17-24   | Packets Interval            | Bidirectional, Single | Min, Max, Mean, Stddev       | Temporal Features|
| 25-26   | SYN Packet Number           | Bidirectional, Single | -                            | Content Features|
| 27-28   | CWR Packet Number           | Bidirectional, Single | -                            | Content Features| 
| 29-30   | ECE Packet Number           | Bidirectional, Single | -                            | Content Features|
| 31-32   | URG Packet Number           | Bidirectional, Single | -                            | Content Features| 
| 33-34   | ACK Packet Number           | Bidirectional, Single | -                            | Content Features|
| 35-36   | PSH Packet Number           | Bidirectional, Single | -                            | Content Features|
| 37-38   | RST Packet Number           | Bidirectional, Single | -                            | Content Features| 
| 39-40   | FIN Packet Number           | Bidirectional, Single | -                            | Content Features| 
| 41      | Application Name            | -                     | -                            | Content Features| 
| 42      | Application Category Name   | -                     | -                            | Content Features| 
| 43      | Application is Guessed      | -                     | -                            | Content Features| 
| 44      | Payload Size in Bytes               | -                     | -                            | Byte Features   | 
| 45-300  | Payload Bytes Content Distribution | -                 | -                            | Byte Features   | 
| 301-379 | Payload Length Distribution              | -                     | -                            | Byte Features   |  
| 380     | Bytes Average Popcount      | -                     | -                            | Byte Features   |
| 381     | Bytes Average Printable Number | -                  | -                            | Byte Features   |

