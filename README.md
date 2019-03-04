# tensorcatgpu
Nvidia driver + depdenencies GPU compiled tensorflow (NDGPUTF) on Ubuntu is really challenging. Is this difficulty itself a kind of intelligence test? 

What are Neural Networks good for anyway? 

Can tensorflow CPU (CPUTF) be used to assist in installing / compiling Nvidia GPU (CUDNN) supported tensorflow?

Can you use tensorflow CPU to bootstrap a fault-tolerant Nvidia GPU (CUDNN) supported tensorflow build?
Can you use tensorflow CPU to bootstrap a fault-tolerant AMD GPU (RocM) supported tensorflow build?


Assume you are trying to install on an Ubuntu 18 OS with following system specs: 

OS: Ubuntu 18.10 cosmic                                                                                              
 Kernel: x86_64 Linux 4.18.0-15-generic                    
 Uptime: 6h 43m
 Packages: 2412
 Shell: bash 4.4.19
 Resolution: 2560x1080
 DE: LXDE
 WM: OpenBox
 CPU: AMD Ryzen 5 1600X Six-Core @ 12x 4GHz [36.6°C]
 GPU: GeForce GTX 1050
 RAM: 8732MiB / 16034MiB


Yes, you do need a developer account with nvidia to get the necessary files like: libcudnn7-dev_7.4.2.24-1+cuda10.0_amd64.deb

To DO: see further readings from cat tf_env.txt file. 

Install TensorFlow CPU 
https://www.tensorflow.org/install/pip
