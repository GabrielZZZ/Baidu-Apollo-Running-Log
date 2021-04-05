# 20201106 Running Log

## Challenges
- Seems to fnd the reason why Apollo cannot practice correcting routing function sometimes: It happens when I reset the position in the LGSVL simulator by pressing F12 key on the keyboard.
  - Since Apollo believes it is controlling the real car, simply reset the position in the LGSVL simulator may not work. although the position of the car in the Apollo Dreaview also reset. That could be the reason.
  - **Current Solution: Click the "Reset Backend Data" bottom on the "Tasks" left side panel. which will close all the turning modules. Then reenable these modules. Note that it will take quite a long time for perception module to start.**

## Progress
- Seems the traffic light behaves abnormal on the Dreamview: it continues to shine between yellow and green, making ego car confused. However, the traffic light in the LGSVL Simulator behaves normal. Therefore, it could be the connection problem, although it can be seen from the Dreamview Console that the traffic light module delay is not high.
- The perception module also seems not working properly: it sometimes cannot detect the comming car and go hit it directly. Currently having no idea whether it is due to the cause of inapproriate setting or program defects (but the former is more possible...).
- The perception module and trafic light module sometimes shut down automatically. Having no idea why this happens but this could also be the reason for the phenomena mentioned above.
