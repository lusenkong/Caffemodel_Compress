# Caffemodel_Compress# <<Deep Compression: Compressing Deep Neural Networks with Pruning, Trained Quantization and Huffman Coding>>

Song Han, Huizi Mao, William J. Dally
(Submitted on 1 Oct 2015 (v1), last revised 15 Feb 2016 (this version, v5))

A c++ project what performing CNN channel pruning
It's an idea I've had floating around for a while , You can perform channel pruning on your trained caffemodel by using this tool, A XML file you should recollocate first,irrespective of whether depthwise or convolution layer, when convolution layer which need to prune has been setting, a reciprocal arrangement of channel pruning also has been setting during processing of progress implicitly, then do a little path change in main.cpp ,and build it with your local IDE.


updated 18/6/25 Already supported to eltwise pruning
mac...
