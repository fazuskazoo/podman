all: 
	echo 'build, run, compose'
build:
	podman build -t server_volume .
create:
	podman create --name server_volume localhost/server_volume
run:
	podman run -v /home/fazzzy/volume_one/:/usr/src/app/volume_one:Z -it server_volume bash 
compose:
	podman compose -f compose.yaml  up --force-recreate
	
