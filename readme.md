This is a program about point cloud library to test.

Contains RGB maps and corresponding depth maps.

The pose data of the camera is in the pose.txt file.

The generated map.pcd file, through 'PCL' provided by the visualization program pcl_viewer can view the generated point cloud data.

```
mkdir build && cd build
cmake ..
make 
cd ..
build/joinMap
pcl_viewer map.pcd
```

