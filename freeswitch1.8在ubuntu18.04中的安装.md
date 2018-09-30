# freeswitch在ubuntu18.04中的安装
默认情况下，bootstrap.sh后，会找不到lua.h，安装liblua5.2-dev后，情况依然，
解决办法：增加软连接，
 
sudo ln -sf /usr/include/lua5.2/* /usr/include/

sudo ln -s /usr/lib/x86_64-linux-gnu/liblua5.2.so.0 /usr/lib/liblua.so
 
