# 20201129

# Challenges
- Cannot solve the problem encountered in previous days (i.e. the OpenGL problemm in docker)
  - due to the system and graphics card version, it is impossible to roll back to the driver version that was suggested two years ago.

# Progress
- Found out that the problem of OpenGL seems relate to the version of the Apollo system or the docker image because this problem was not enountered in the latest Apollo branch (by using the command `glxgears` to test, under normal conditions there will be an animation of gears pop up).
- Have tried using Apollo version 3.0 which was suggested under Apollo issue page, but it was not working (https://github.com/ApolloAuto/apollo/issues/13049).

