# week4_rover


# 🛠️ Setting up Gazebo + ros2_control on Ubuntu 22.04 for ROS 2 Humble 🤖

## 1️⃣ Install Gazebo
```bash
sudo apt update
sudo apt install gazebo
```

✅ Should return Gazebo 11
```bash
gazebo --version
```



## 2️⃣ Install Gazebo ↔ ROS 2 integration
```bash
sudo apt install \
  ros-humble-gazebo-ros-pkgs \
  ros-humble-gazebo-ros2-control
```

---

## 3️⃣ Install ros2_control core packages
```bash
sudo apt install \
  ros-humble-ros2-control \
  ros-humble-forward-command-controller \
  ros-humble-joint-trajectory-controller \
  ros-humble-joint-state-broadcaster
```

---

## 4️⃣ (Optional) Install helpful tools
```bash
sudo apt install \
  ros-humble-xacro \
  ros-humble-robot-state-publisher \
  ros-humble-joint-state-publisher-gui \
  ros-humble-rqt-controller-manager
```

---



**Launch the robot model in Gazebo**

   ```bash
   ros2 launch week4 gazebo_launch.py
   ```

Make sure you have gazebo installed and working before running the above part. 
