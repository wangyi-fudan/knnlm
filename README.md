# knnlm
k-NN based language model

**Aim**

This is a striking simple language model based on k-NN yet providing good results. The distance measure of two prefixes is their weighted hamming distance. Distances were fed into a softmax function. The next char is sampled from softmax weighted next-char of all text prefixes.

**Install**

make

**Training**

./train COVID-19

**Generate sample**

./knnlm COVID-19 The coronavirus

**Benchmark language model**

./knnlm COVID-19 -b 1000

**Enjoy!**

By Wang Yi @ Fudan University

2020-09-23
