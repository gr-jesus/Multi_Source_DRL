# Multi-Source Transfer Learning for Deep Reinforcement Learning
Code of the paper "Multi-Source Transfer Learning for Deep Reinforcement Learning"

## Abstract:
Deep reinforcement learning has obtained impressive performance in challenging tasks in recent years. Nevertheless, it has important limitations such as long training times and the number instances that are needed to achieve acceptable performance. Transfer learning offers an alternative to alleviate these limitations. In this paper, we propose a novel method for transferring knowledge from more than one source tasks. First, we select the best source tasks using a regressor that predicts the performance of a pre-trained model in the target task. Then, we apply a selection of relevant convolutional kernels for the target task in order to find a target model with similar number of parameters compared to the source ones. According to the results, our approach outperforms the accumulated reward obtained when learning from scratch in 20.62\% using lower parameters (about 56\% of the total, depending on the specific game).

## Code:
In order to share our code with the community we share it as colab notebooks. According to the process of the proposed method the pre-trained models (weights) for the thirty games in numpy array format can be downloaded in the next link, this files are used for load the weigths in the tensorflow models. 

## Files:
We share the necessary files for run the code:

- Experience Replay for evaluate in the pre-trained models: [Link](https://www.google.com/url?q=https%3A%2F%2Fmega.nz%2Ffile%2FpldVXILK%23uIV1WwbCLqX5cRXGurPQUvPsyGn-_6UMGsXx7neCwXQ&sa=D)
- Weights of the pre-trained models: [Link](https://www.google.com/url?q=https%3A%2F%2Fmega.nz%2Ffile%2FYwFxRCoS%230NShbFwSujwRZ_EfgfiUfooM2-32FFcvMT9Mk8YRj0Y&sa=D)
- Files for evaluate the regression model: [Link](https://www.google.com/url?q=https%3A%2F%2Fmega.nz%2Ffile%2FpoMXES6D%23L-HOrf59YOHKQAtTTUnfecXP4t9slRpo6MCRGnX9SO8&sa=D)
- Regression model: [Link](https://www.google.com/url?q=https%3A%2F%2Fmega.nz%2Ffile%2Fg8FjhSoL%23mZDdAaRdk84W-c8tLxvHiIwfrEEy54bOVYwRuSQRUvo&sa=D)
- Full results for each game: [Link](https://www.google.com/url?q=https%3A%2F%2Fmega.nz%2Ffile%2FFxVn0CjD%23VFdun2a66X17oeYpmU9hjs1C5arvA_ekCkFhDQUBSHQ&sa=D)

## Aknowledgements
The authors thankfully acknowledge computer resources, technical advice and support provided by Laboratorio Nacional de Superc\'omputo del Sureste de M\'exico (LNS), a member of CONACYT national laboratories with projects No. 201901047C and 202002030c. We also want to acknowledge the Laboratorio Nacional de Supercómputo del Bajio with project No. 2020.1.  Jes\'us Garc\'ia-Ram\'irez acknowledges CONACYT for the scholarship that supports his PhD studies associated to CVU number 701191. 
