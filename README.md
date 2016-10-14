# SystemValidationCar 
一些比较大的修改列在这里
1.关于电池组，为了稍微简化下模型，把原来的四个action改为三个，stop——provide和stop——load都改成stop，provide和load可以直接互相转换，不用经过
中间idle的状态，只有在强制停止时在用do-stop停止进入idle状态。
