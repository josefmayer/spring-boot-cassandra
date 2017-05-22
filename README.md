## Cassandra, Spring Boot
Cassandra database example with Spring Boot <br />



### Technologies
Cassandra, CQL, Spring Boot <br />


### Steps:
#### Start Cassandra 
cd /etc/init.d/ <br />
cassandra start <br /> 


#### Create keyspace and table
cqlsh < src/test/resources/create_keyspace.cql <br />
cqlsh < src/test/resources/setup.cql <br />


#### Compile and Run Spring Boot Appliation
*mvn clean compile* <br />
*mvn spring-boot:run* <br />
 


### Info:
https://github.com/spring-projects/spring-boot/tree/master/spring-boot-samples/spring-boot-sample-data-cassandra




