ReX
====

Usage: java -jar -Xmx64g rexRand.jar 

The default extrapolation technique used is ReX_main. 

Please adjust the maximum heap size of the JVM according to your environment.

For other inquiries, please contact teodora.buda at ucdconnect.ie

Example usage for scaling the database tpch (-db option) by a scaling rate of 2 (-rate option) using the extrapolation method ReX_rfc (-rand option): java -jar -Xmx64g rexRand.jar -rand -db tpch -u user -p password -rate 2	

More help on the available option is available by running the jar file with -h: java -jar rexRand.jar -h
 
