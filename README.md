Follow the steps below to calculate the information diffusion dynamics:
(1) Compile three file ("InformationDiffusion.h", "InformationDiffusion.cpp", and "Test.cpp")to generate an execuable file "Test.exe" using visual studio 2019;
(2) Execute "Test.exe" and take two input parameters (InputFilePath and OutputFilePath). where, data files (i.e., OnlineNetNode.csv and OnlineNetEdge.csv) are stored
(3) After executing "Test.exe", a series of result files would be stored in OutputFilePath.
(4) A result file would be named as "N-f.csv", where K is initial number of spreaders, f is the spreading ratio. 50000 number in the result are all the diffused population after information diffusion because we had tested 50000 times for the same number of spreaders and spreading rate. Let w = sum(S_i)/(50000 * n) be the diffused population ratio, where S_i is an arbitrary value in "N-f.csv", n is the total number of nodes on Online Network.
(5) Using a series of pair of f and w, we can draw the relation of spreading ratio and diffused population ratio.
