舵机用的pca9685 IIC控制，还有几个没用的文件，我没有删。

$ gcc -o plotclock plotclock.c pca9685.c -pthread -lwiringPi -lm -lrt -lcrypt -llirc_client
