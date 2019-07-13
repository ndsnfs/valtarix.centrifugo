# valtarix.centrifugo
docker pull centrifugo/centrifugo

docker run --ulimit nofile=65536:65536 -v /data/valtarix.centrifugo:/centrifugo -p 8000:8000 centrifugo/centrifugo centrifugo -c config.json
