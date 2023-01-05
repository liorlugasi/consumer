# consumer
consumer for memphis

Hi,

To run the consumer app as docker container:
1. build the images of consumer app and nginx:
   docker-compose build
2. deploy the app:
   docker stack deploy -c docker-compose.yaml swarmnodeapp

For any issues please let me know.

Thanks,
Lior.
