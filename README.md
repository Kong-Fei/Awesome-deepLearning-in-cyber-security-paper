<!--
 * @Author: fei 714848822@qq.com
 * @Date: 2023-04-26 15:18:12
 * @LastEditors: fei 714848822@qq.com
 * @LastEditTime: 2023-05-04 21:36:57
 * @FilePath: \undefinedd:\recent\Awesome-DeepLearning-In-Cybersecurity-Paper\README.md
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
# Awesome-DeepLearning-In-Cyber-Security-Paper
在网络安全领域，应用DeepLearning方法的重要paper

## 1.Survey/Guide

| DeepLearning Method                    | Title                                                        |Introduction                                                 |
| -------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------| 
|            Guide                       | [(USENIX 2022)Dos and Don'ts of Machine Learning in Computer Security](https://www.usenix.org/conference/usenixsecurity22/presentation/arp)) | 回顾了过去10年四大安全顶会的深度学习应用文章，由此总结了机器学习应用于安全领域需要注意的事项（该做/不该做的事项）|

## 2.Network Intrusion Detection
| DeepLearning Method                    | Title                                                        |Introduction                                                 |
| -------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------| 
|            Guide                       | [(IEEE S&P 2010) Outside the Closed World: On Using Machine Learning for Network Intrusion Detection](https://ieeexplore.ieee.org/abstract/document/5504793) | S&P时间检验奖，介绍了机器/深度学习方法应用到网络流量异常检测乃至网络安全领域的困境 |
|            Autoencoder   Ensemble      | [(NDSS 2018) Kitsune: An ensemble of autoencoders for online network intrusion detection](https://arxiv.org/abs/1802.09089)   |  基于自编码器集群学习正常流量的数据特征分布，检测异常流量，轻量级无监督NIDS      |



## 3.Network Alert Analysis
| DeepLearning Method                    | Title                                                        |Introduction                                                 |
| -------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------| 
|            Guide                       | [(CSS 2017) DeepLog: Anomaly Detection and Diagnosis from System Logs through Deep Learning](https://dl.acm.org/doi/abs/10.1145/3133956.3134015) | TODO |

## 4.Host Log Analysis
| DeepLearning Method                    | Title                                                        |Introduction                                                 |
| -------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------| 
|            Attention&RNN/GRU      | [(IEEE S&P 2022) DEEPCASE: Semi-Supervised Contextual Analysis of Security Events](https://ieeexplore.ieee.org/abstract/document/9833671/)   |  针对一条日志$e_i$，基于GRU构建同一主机的日志事件序列向量，然后使用Attention计算序列中其他日志与$e_i$的关联性，通过这两部分获得告警事件的总向量，聚类对对应事件进行解释|  