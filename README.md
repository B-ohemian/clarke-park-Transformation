# clarke-park-Transformation
FOC算法中clarke变换和park变换的simulink仿真验证
# 使用simulink进行仿真，系统仿真图如下
![image](https://user-images.githubusercontent.com/51984029/197202232-3d28e2a7-0a82-417e-8516-e5edb462f482.png)

如果按照书上的公式不改变AB相的相序，那么park变换后的信号可能还是交流信号，所以如果出现交流信号可以改变AB的相序。

![image](https://user-images.githubusercontent.com/51984029/197202537-9e447b1c-d961-4ceb-9f79-ba4b66018612.png)

注意theta值是一个角度，不能使用CSDN上说的只用一个斜坡信号代替，应该乘以一个2*PI,否则也会是一个交流信号。

最后变换后的结果

![image](https://user-images.githubusercontent.com/51984029/197202886-d12c5109-b9c0-43d6-8156-a860d55bb9c6.png)

