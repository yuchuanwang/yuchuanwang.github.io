记录一些笔记和实验，毕竟据说好脑袋不如烂笔头。

---

1. 性能相关
   
   - [性能分析与测量工具集](https://github.com/yuchuanwang/perfkit)
   
   - [缓存 - 局部性](https://github.com/yuchuanwang/docs/blob/main/Performance/Locality_of_reference.md)
   
   - [缓存 - 伪共享](https://github.com/yuchuanwang/docs/blob/main/Performance/False_sharing.md)
      
   - 本机网络 Unix Domain Socket

2. 算法相关
   
   - [细胞分裂问题原创解法](https://github.com/yuchuanwang/docs/blob/main/Algorithm/Cells_count.md)

3. C++杂记

   - [C++ lambda表达式](https://github.com/yuchuanwang/docs/blob/main/Cpp/Cpp_Lambda.md)

   - [C++ const与指针](https://github.com/yuchuanwang/docs/blob/main/Cpp/Cpp_Const_Pointer.md)

   - [C++ 友元与运算符重载那些事](https://github.com/yuchuanwang/docs/blob/main/Cpp/Cpp_Friend_Operator.md)

   - [C++ 线程池](https://github.com/yuchuanwang/docs/blob/main/Cpp/Cpp_ThreadPool.md)
 
   - [Lock-free Ring Buffer Queue](https://github.com/yuchuanwang/RingBuffer)


4. 网络相关

   - [Docker容器网络的七种武器](https://github.com/yuchuanwang/docs/blob/main/Network/Docker_Network.md)
 
   - [基于Ubuntu安装Kubernetes集群指南](https://github.com/yuchuanwang/docs/blob/main/Network/Kubernetes_Installation.md)

   - [Kubernetes网络模型分析](https://github.com/yuchuanwang/docs/blob/main/Network/Kubernetes_Network.md)

   - [Kubernetes CNI之Flannel网络模型分析](https://github.com/yuchuanwang/docs/blob/main/Network/Kubernetes_Flannel_Network.md)


5. 高并发高可用

   - [负载均衡](https://github.com/yuchuanwang/docs/blob/main/Cpp/Cpp_Load_Balance.md)


6. eBPF相关

7. [PCPP](https://github.com/yuchuanwang/pcpp) - **P**ython like **CPP**
   
   顾名思义，计划试着开发一个类似于Python功能的C++代码库。
   
   工作以来，大部分的时间都是用C++在写代码，后面一段时间，接触了Python并用它开发了一些功能。感叹Python各种各样的库实在很方便，往往import一个库，然后几行代码就解决了C++要自己写很多代码才能实现的功能。极大的提高了开发效率，然后牺牲了运行效率。
   
   相比之下，C++的各种代码库虽然也很多，但很难把它们整合到一个项目里面。各种头文件、类型重复定义、接口各种各样、link时各种错误等等等等；而完整一些的比如boost又是那么庞大。
   
   所以大胆的想试着开发一个精简又包括一些常见功能的代码库，功能模仿Python。
   
   具体怎么做，尚在构思中，而且最近也确实没时间没精力……
