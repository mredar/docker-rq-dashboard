====================
How to run in docker
====================
docker run -p 9181:9181 --env="REDIS_PSWD=${REDIS_PSWD}
# to make available from other machines: --env="REDIS_HOST=<ip>"
# need to add stunnel with an ADD <certificate files> in the Dockerfile
# to make is secure to other machines
