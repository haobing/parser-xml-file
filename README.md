直接通过apt-get安装，非常方便



#sudo apt-get install libxml2



#sudo apt-get install libxml2-dev



默认是安装在/usr/include/libxml2  



如果需要编译一个.c文件，命令如下



gcc  obj.c -o obj -I /usr/include/libxml2 -L /usr/lib/ -lxml2
