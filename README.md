#![alt text](http://farkhor.github.io/CuSha/images/CuSha-logo-small.png "CuSha")

CuSha is a CUDA-based vertex-centric graph processing framework that uses G-Shards and Concatenated Windows (CW) representations to store graphs inside the GPU global memory. G-Shards and CW consume more space compared to Compressed Sparse Row (CSR) format but on the other hand provide better performance due to GPU-friednly representations. For completeness, provided package also includes Virtual Warp-Centric (VWC) processing method for GPU and a multi-threaded CPU implementation, both using CSR representation. We 

[Paper](http://dx.doi.org/10.1145/2600212.2600227).

[Presentation](http://www.cs.ucr.edu/~fkhor001/CuSha/CuSha_Slides.pptx).

[Requirements and Usage](http://farkhor.github.io/CuSha/)

###Acknowledgements###

This work is supported by National Science Foundation grants CCF-1157377 and CCF-0905509 to UC Riverside.
