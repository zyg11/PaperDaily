# Paper:Beyond Short Snippets: Deep Networks for Video Classification,arXiv:1503.08909v2 [cs.CV] 13 Apr 2015

## Abstract

Convolutional neural networks (CNNs) have been extensively applied for image recognition problems giving stateof-the-art results on recognition, detection, segmentation
and retrieval. In this work we propose and evaluate several
deep neural network architectures to combine image information across a video over longer time periods than previously attempted. We propose two methods capable of handling full length videos. The first method explores various
convolutional temporal feature pooling architectures, examining the various design choices which need to be made
when adapting a CNN for this task. The second proposed
method explicitly models the video as an ordered sequence
of frames. For this purpose we employ a recurrent neural
network that uses Long Short-Term Memory (LSTM) cells
which are connected to the output of the underlying CNN.
Our best networks exhibit significant performance improvements over previously published results on the Sports 1 million dataset (73.1% vs. 60.9%) and the UCF-101 datasets
with (88.6% vs. 88.0%) and without additional optical flow
information (82.6% vs. 73.0%).

### Contribution
