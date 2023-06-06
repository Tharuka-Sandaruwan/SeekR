# SeekR
Distributed Meta Search engine powered by Searx project


```
docker pull nappadocker/seekr:latest


docker run --rm \
             -d -p ${PORT}:8080 \
             -v /home/tetha/files:/usr/local/searxng/searx/ \
             -e "BASE_URL=http://localhost:$PORT/" \
             -e "INSTANCE_NAME=seekr" \
             nappadocker/seekr
             
```
