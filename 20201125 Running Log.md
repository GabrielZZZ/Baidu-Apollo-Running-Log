# 20201125

# Challenges
- Cannot run the command `/apollo/bazel-bin/modules/perception/tool/offline_visualizer_tool/offline_sequential_obstacle_perception_test` successfully since it will give the error about OpenGL (in Apollo 2.5):

  - It seems to be the driver problem of Nvidia. It may need to reinstall the older version of driver (the worst case).
  - Related Issues:
    - https://github.com/ApolloAuto/apollo/issues/2362
    - https://github.com/ApolloAuto/apollo/issues/1832
    


# Progress
- Successfully extracting pcd and pose files from demo bag by using the tool `export_sensor_data` in **Apollo 2.5**
