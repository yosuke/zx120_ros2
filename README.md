```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/yosuke/zx120_ros2/jammy-humble-amd64/ ./" | sudo tee /etc/apt/sources.list.d/yosuke_zx120_ros2.list
echo "yaml https://github.com/yosuke/zx120_ros2/raw/jammy-humble-amd64/local.yaml humble" | sudo tee /etc/ros/rosdep/sources.list.d/1-yosuke_zx120_ros2.list
```
