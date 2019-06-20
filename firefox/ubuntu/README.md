Image built on Ubuntu:latest

container created using following command:
docker run -d --name="firefox" -e DISPLAY=$DISPLAY -v /tmp/.X11-unix:/tmp/.X11-unix stumueller/firefox

for running on windows host have X windows client installed (VcXsrv)