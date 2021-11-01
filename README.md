# fuse-mtls-demo

Example of Mutual Client Authorization with Fuse and Spring Boot

## Running the example

### Generate keystores

	cd fuse-mtls-demo/bin
	sh -x ./gen-non-prod-key.sh

### Run the server

	cd ../springboot-server
	mvn spring-boot:run


###  Run the Fuse client

in another terminal

	cd fuse-mtls-demo/fuse-springboot-client
	mvn spring-boot:run

### Testing

	curl http://localhost:8080/v1/fuse-server	  
