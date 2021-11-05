Steps to run:

1. Go to /demok6 and run docker-compose up -d
2. Go to /demol6/k6 and run docker-compose up -d
3. In /demol6/k6 run any command related to k6
   - example: docker-compose run k6 run /k6/tests/demo02.js --out influxdb=http://localhost:8086/k6
