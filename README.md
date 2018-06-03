# laser_filters
Assorted filters designed to operate on 2D planar laser scanners, which use the sensor_msgs/LaserScan type.
 在scan_to_cloud_filter_chain.cpp中添加了滤波，先将scan转化为pointcloud，使用pcl滤出孤立点,
 再配合pointcloud-to-scan转化为scan，解决了激光雷达存在孤立噪点的问题

