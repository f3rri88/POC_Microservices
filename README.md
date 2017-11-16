Go to file hosts in C:/Windows/System32/drivers/etc/ and add new host:
127.0.0.1   accounts.microservices.com

Open a command line in POC_Microservices folder and execute:

docker-compose -f docker-compose.prod.yml build

docker-compose -f docker-compose.prod.yml up

Navigate either to accounts.microservices.com:81 or to https://accounts.microservices.com
Skip certificate unknown issue
ENJOY