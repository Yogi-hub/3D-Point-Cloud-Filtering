# 3D Point Cloud Filtering

This repository contains a custom Robot Operating System (ROS) package designed to filter noisy cumulative point clouds. The package enhances the quality of 3D point cloud data by removing outliers and smoothing the dataset, which is essential for applications like 3D modeling, mapping, and object recognition.

## Features

- **Noise Reduction**: Implements a filtering node in ROS, to eliminate noise from point cloud data.
- **Outlier Removal**: Identifies and removes outlier points that do not conform to the expected structure.
- **ROS Integration**: Seamlessly integrates with ROS for real-time processing and compatibility with other ROS packages.
- **Customization**: Allows users to adjust filtering parameters to suit specific datasets and requirements.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/YokeshD99/3D_Point_Cloud_Filtering.git
   ```
2. **Navigate to the package directory**:
   ```bash
   cd 3D_Point_Cloud_Filtering
   ```
3. **Build the package**:
   ```bash
   catkin_make
   ```
4. **Source the setup file**:
   ```bash
   source devel/setup.bash
   ```

## Usage

1. **Launch the filtering node**:
   ```bash
   roslaunch point_cloud_filtering filter.launch
   ```
2. **Publish your point cloud data** to the appropriate ROS topic.
3. **Visualize the filtered point cloud** using RViz or any compatible ROS visualization tool.

## Dependencies

- [Robot Operating System (ROS)](https://www.ros.org/)
- [PCL (Point Cloud Library)](https://pointclouds.org/)

Ensure that both ROS and PCL are properly installed and configured on your system.

## Author

D. Yokesh

## License

This project is licensed under the MIT License.

