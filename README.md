# 利用libft4222实现上位机同时读取四个角度传感器数据

for linux:

----------;

run commend:
cd libft4222-linux-1.4.4.44
sudo ./instal4222.sh
cd ../spimTest
rm -rf build
mkdir build
cd build
cmake ..
make
sudo ./spimTest

---------------------;

## spimTest

    同时读取四个角度传感器的数据
