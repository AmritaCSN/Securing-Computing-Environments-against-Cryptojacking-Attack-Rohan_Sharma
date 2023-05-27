# Securing-Computing-Environments-against-Cryptojacking-Attack-Rohan_Sharma


The main goal of this research project is to detection and analysis of "Cryptomining Malware" using machine learning. Attackers constantly come up with new strategies to exploit mining systems as cryptocurrency's popularity increases, leading to an increase in illicit mining activity. This vectorised cyber attack is called Cryptojacking, in the recent past this has gained popularity. In order to build a comprehensive model that improves our capacity to precisely anticipate the presence of cryptomining malware, we used a different datasets in our study.

## Table of Contents

- [Introduction](#introduction)
- [Methodology](#Methodology)
- [Architectural_Diagram](#Architectural_Diagram)
- [Datasets](#dataset)
- [Installation](#installation)
- [Approach](#approach)
- [Results](#results)
## Introduction

Cryptomining malware, also known as cryptojacking malware, is a type of malicious file which uses the computational resources of infected machines to mine cryptocurrencies. Unlike in-browser cryptojacking, which operates within web browsers, this project focuses on detecting cryptomining malware that runs as standalone processes on compromised systems, because the severity of cryptomining malware is much higher than in-browser based cryptojacking.

The main objective of this project is to build a detection system capable of identifying the presence of cryptomining malware on target machines. By using machine learning techniques and multiple datasets for extra validation and precise prediction, we aim to develop an accurate and efficient method for identifying and mitigating cryptojacking attacks.

## Methodology

![meth](https://github.com/AmritaCSN/Securing-Computing-Environments-against-Cryptojacking-Attack-Rohan_Sharma/assets/26691240/9204beb9-eb8a-4a0b-85fc-62842839b891)


## Architectural Diagram

![Cryptojacking_ML_Model_Architectural_Block_diagram](https://github.com/AmritaCSN/Securing-Computing-Environments-against-Cryptojacking-Attack-Rohan_Sharma/assets/26691240/8f120327-eb52-4171-ba74-bcff3a118e01)

## Dataset

To train and testing our detection system, we have utilized multiple datasets consisting of known samples of cryptomining malware. The datasets include various stats of CPU usage, Memory Usage and network etc all the various factors which can help us in detecting cryptoming malware. The combined use of these datasets enables us to enhance the accuracy and robustness of our detection approach.
Datasets can be downloaded from this same repository, Please refer to the data folder for further instance.

## Installation

To install and set up the project, follow these steps:

1. Clone the project repository
2. Navigate to the project directory
3. From the source code directory, directly run the ipynb file.
Note: The datasets should be in the same directory.

## Approach

Our approach to detecting cryptomining malware involves leveraging machine learning algorithms and employing multiple datasets for enhanced validation. The key steps in our approach include:

1. We preprocess the datasets to extract relevant features and transform the data into a suitable format for machine learning algorithms.
2. Then we’ll choose the models on which we will train.
3. Check for the best-performing model amongst all the models.
4. Best performing models, performance metric has to be analyzed and on that basis we will select the best performing model.
3. Then at the end we’ll be combining both the models from different datasets and get the more validated prediction.  

## Results

The cryptomining malware detection system achieved promising results during our evaluations. The model demonstrated high accuracy and robustness, effectively identifying cryptomining malware.

## Future Work 
Since Android smartphones are equally capable today but considerably more vulnerable due to their exposed environments, this project can be expanded on for android devices. Thus, this is the future scope in this area of research..
