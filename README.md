# Using Python to analyze ECG signals

Author: Chun-Chia Yang

## Introduction

This notebook is tring to analyze the changes of ECG signals in different states. The data comes from CEBS database. The reason why I choose the data from CEBS is because it contains multi parameters and the data of subjects being in three different states. I downloaded three files containing ECG signals in three different states of the same subject respectively.

HRV(heart rate variability) is the physiological phenomenon of variation in the time interval between heartbeats. HRV can be traced back to our autonomic nervous system.The autonomic nervous system regulates very important systems in our body, including heart and respiration rate and digestion. The autonomic nervous system has a parasympathetic (rest) and a sympathetic (activation) branch. Heart rate variability is an indicator that both branches are functioning – the parasympathetic in particular.

By calculating the PSD (power spectral density) of HRV,we can learn a lot of information about our physiological state.Therefore,I will try to compute it of the ECG dataset and show figures about the analysis result.

## NBViwer  
[http://nbviewer.jupyter.org/github/ChunChiaYang/ECG-Analysis/blob/master/ECG-Analysis.ipynb](http://nbviewer.jupyter.org/github/ChunChiaYang/ECG-Analysis/blob/master/ECG-Analysis.ipynb)
