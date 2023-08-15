```bash
echo "deb [trusted=yes] https://github.com/eaa3/ros-humble-packages/raw/jammy-humble/ ./" | sudo tee /etc/apt/sources.list.d/eaa3_ros-humble-packages.list
echo "yaml https://github.com/eaa3/ros-humble-packages/raw/jammy-humble/local.yaml humble" | sudo tee /etc/ros/rosdep/sources.list.d/1-eaa3_ros-humble-packages.list
```
