```sh
docker image build -t rjds/conversao-temperatura:v1 .
docker container run -d -p 8081:8080 rjds/conversao-temperatura:v1
```