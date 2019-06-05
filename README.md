# loriini-spring-cloud

HTTP Endpoints for config files

Type	    Pattern	                                        HTTP URL
Common	    /{application}/{profile}/{label}	            http://localhost:8888/user-service/dev/master
Yaml	    /{application}-{profile}.yml	                http://localhost:8888/user-service-dev.yml
Yaml	    /{label}/{application}-{profile}.yml	        http://localhost:8888/master/user-service-dev.yml
Properties	/{application}-{profile}.properties	            http://localhost:8888/user-service-dev.properties
Properties	/{label}/{application}-{profile}.properties	    http://localhost:8888/master/user-service-dev.properties

