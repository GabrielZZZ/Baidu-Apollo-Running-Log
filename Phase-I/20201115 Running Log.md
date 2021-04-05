# 20201115

## Challenges
- Cannot extract .pcd file from a record, which is the first step in the old experiment (![issues #12999](https://github.com/ApolloAuto/apollo/issues/12999))

## Progress
- Fix the tranform issue that transform a rosbag file to `.record` version, which mentioned in the Challenges section in yesterday's log.
  - Using Apollo 5.0 that includes the tool `rosbag_to_record`. Apollo 6.0 excludes it from the folder.
  - Now the demo_1.5 record can be used, which is the same file the old experiment used two years ago.
