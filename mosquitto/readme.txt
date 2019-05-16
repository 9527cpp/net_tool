双击安装mosquitto
在安装目录下新建 pwfile.example文件
执行 mosquitto_passwd -c pwfile USERNAME PASSWORD
USERNAME和PASSWORD可替换
copy mosquitto.conf 到安装目录下
在安装目录下执行 mosquitto -c mosquitto.conf -p 1883 即启动了mosquitto服务代理