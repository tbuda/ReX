ReX
====

Usage: java -jar -Xmx64g rexRand.jar 

Please adjust the maximum heap size of the JVM according to your environment.

For other inquiries, please contact teodora.buda at ucdconnect.ie

Example usage for scaling the database (-db parameter) tpch by a scaling rate of 2 (-rate parameter) using ReX_rfc (-rand parameter): java -jar -Xmx64g rexRand.jar -rand -db tpch -u user -p password -rate 2	

More help on the available parameters is available by running the jar file with -h: java -jar rexRand.jar -h
 
