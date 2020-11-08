# 20201108 Log

## Challenges:
- Still having the problem of not syncing the traffic light signals between the Dreamview and LGSVL Simulator. 
- Still having the problem with the navigation function when initialize the ego car position in LGSVL Simulator.

## Progress
- Trying the function of *Modular Testing* from LGSVL Simulator, which replace the perception and traffic ligth module with ground truth perception data. The method works based on the assumption that "the perception output is 100% accurate with no errors". The results turned out that:
  - the Dreamland and LGSVL simulator become smoother with increasing FPS and faster moving cars. 
  - now the obstacles can show completely and correctly in the dreamview.
  - the traffic light and navigation modules behave correctly.
