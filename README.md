# 智能车队 ROS2 工作空间

## 目录结构
- `src/` — ROS2 功能包源码
- `build/` `install/` `log/` — colcon 编译产物（已 gitignore）

## 常用命令
```bash
cd ~/ros2_ws
colcon build --symlink-install
source install/setup.bash
ros2 run <pkg> <node>
```
