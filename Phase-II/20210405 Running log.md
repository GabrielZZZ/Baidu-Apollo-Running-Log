# 20210405 Running Log Phase II

This is the Phase II for the running of Apollo. In Phase I a replication experiment was carried out by using Apollo 3.0. Phase II will focus on the latest Apollo branch with LGSVL simulator anabled.
  
 ## Progress
  I have successfully running Apollo with SVL simulator (yes, it changed its name now) on a PC with RTX 3090. The performance is superisingly good compared to the PC with 2*2080Ti as SLI. I guess the Apollo can only use one GPU such that the graphics memory is not enough. It may also thanks to the optimization effort done by the development team. I will test it in the lab in these two days.
  
 ## Problem
  The only problem I encountered and I cannot solve it by myself is that the perception and traffic light bugs are still not fixed in the latest Apollo and SVL simulator, so I have to use the modular testing, which means that the perception module is unavilable to test since modular testing completely bypass the perception sensors and publish ground truth perception data to Apollo stack via CyberRT bridge. I can only test planning module or routing module at present.
