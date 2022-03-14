# companion-webrtc

to setup:

login into the pi (host) and run
`sudo docker run -d --net=host -v /root/.config/companion:/root/.config --name=companion-webrtc --restart=unless-stopped williangalvani/companion-webrtc`
Setup an UDP h264 stream to 127.0.0.1:8004

View the stream in http://companion.local:8001/
