# 20201114

# Challenges
- Cannot running the perception and traffic light module correctly
- Cannot use command `rosbag_to_record` to transoform the bag `demo-sensor-demo-apollo-1.5.bag` to record file so that current Apollo system can read it
  - this file is what the old research used
  - have post to the Apollo issues yet
  
 # Progress
 - Figured out it is possible to perform the experiment without the LGSVL Simulator (which contradicts the point in yesterday's log)
    - Unless the file contains the data about perception and other modules that need to be teste
    - However, there is still some challenges in visualizing this data in `cyber_visualizer`. I have psot this issue to Apollo.
- Found the old data bag that used in the reserach "metamorphic testing of driverless cars". Nonthless, cannot transform it to record data. See the challenges sectioin.
