# advanced_algorithm
武汉大学网安学院研究生高级算法课项目:三维装箱问题。
目前已实现:
(1)在线算法
(2)严格禁止箱子悬空
(3)每个箱子摆放时间小于1s
(4)箱子的参数可以考虑到小数点后两位
(5)考虑箱子的六种摆放姿态。
(6)禁止箱子出现悬空。

我采用贪心算法以及建立数学优化模型来尽可能提高箱子的利用率，具体的实现方法以及结果可以查看report文件夹中的报告。
针对3、5、8、10、15种箱子的情况，给出了5个用例，名称分别为use_case1.py、use_case2.py、use_case3.py、use_case4.py、use_case5.py，在add_box.py于这5个文件在同一文件夹的情况下，运行其中一个use_case就能得到相应的结果。
如有疑问欢迎发送邮件到zyfhylyh at 126.com与我讨论

开发环境
（1）Windows 版本：Windows 10 专业版 
（2）处理器：Intel(R) Core(TM)i5-10400F 
（3）CPU 内存：16GB 
（4）开发工具：PyCharm Community Edition 2020.2.2 x64 
（5）编译器：python3.7

