Introduction to Software Package ALW_Polar.zip

This software package includes all MATLAB source codes to reproduce the results in this paper. First, please enter 3.1415926 to decrypt the package. Then you will find 4 folders and 5 files in the root folder.
1. algorithm
This folder includes the source code to implement 4 algorithms: SW, LW, ALW1, and ALW2.
2. decoder
This folder includes the source code to implement SC and SCAN decoder for polar codes.
3. tiny
This folder includes the source code to implement 5 operations: ⊕, ⊗, ⊞, ⊠, and Ψ(x).
4. wrap
This folder includes the source code to implement some misc. operations: fusion, generation samples, initialize decoder and set L.
5. root
There are 5 files here
 examples.m can be used to run under MATLAB to obtain the experimental results with the initialized parameters.
 plot_result.m can generate Fig. 1.
 polar_enc can perform encoding polar coding.
 Polar_reliability_5G is used to select the information bits.
 test.m can receive the parameters in examples and run the whole test.
