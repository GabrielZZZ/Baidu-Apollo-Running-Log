# Set up notes

- If the docker cannot start properly (cannot find the container apollo_dev_unnc), try:
	1. running the command to restart the docker: 
	```console
	service docker restart
	```
	2. try again

- Everytime you wants to exit the container, must do the following:
	1. enter a separate terminal window
	2. running command:
	```console
	./docker/scripts/dev_start.sh stop
	```
