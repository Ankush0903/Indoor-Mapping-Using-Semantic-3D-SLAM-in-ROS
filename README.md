This project implements a Semantic 3D SLAM (Simultaneous Localization and Mapping) system in ROS for indoor mapping. It integrates semantic segmentation with 3D mapping to create rich, meaningful maps of indoor environments using RGB-D cameras or LiDAR. The system leverages ORB-SLAM2, PSPNet to fuse geometric and semantic information, enabling applications in autonomous navigation and robotic perception.

## Key Features ##
- Real-time 3D semantic mapping
- Integration with ROS (Robot Operating System)
- Support for RGB-D cameras (e.g., Intel RealSense, Kinect) or LiDAR
- Visualization of semantic maps in Open3D.

## Prerequisites ##
- Operating System: Ubuntu 18.04/20.04 (ROS Melodic/Noetic recommended)
- ROS Version: Melodic or Noetic
- ## Dependencies: ##
  - ROS packages: `ros-<distro>-navigation`, `ros-<distro>-open3d`, `ros-<distro>-tf`
  - OpenCV: >= 3.2
  - Eigen3: >= 3.1.0
  - PCL (Point Cloud Library): >= 1.8
  - Python: >= 3.6 (with packages like `numpy`, `scipy`, `tensorflow-gpu')
- ## Hardware: ##
  - RGB-D camera (e.g., Intel RealSense D435, Kinect) or LiDAR (e.g., Velodyne VLP-16)
  - GPU (recommended for semantic segmentation, e.g., NVIDIA RTX 4080 Super or better)
