指令
#下載專案
git clone https://github.com/benson610287/ros2_ws.git
#進入docker資料夾
cd ros2_ws/docker_template/
#賦予檔案權限
sudo chmod 777 ./build.sh ./run.sh  (這行需要輸入ubuntu密碼)
#建立 Docker 映像檔
./build.sh
#執行 Docker 容器
./run.sh
能開一個新的terminal就是成功，那個terminal就有ROS2-humble的基本功能



