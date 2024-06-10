# Firmata4j_JAR
Complete JAR files for Firmata4J

While version 2.3.8 is available via Maven, 2.3.9 is not.  Unfortunately, with 2.3.8 we need to also separately include / update JSSC and SLF4J.  Instructions for this are found here: https://www.yorku.ca/professor/drsmith/2022/02/25/easy-java-arduino-with-firmata/

The June 2024 JAR file for Firmata4J is based on the GitHub source for version 2.3.9.  It was built using IntelliJ and JDK17 on macOS.  It has only been tested on macOS 14 (Sonoma) with a MacBook Pro M3 Pro.  The JAR file was built using the instructions here: https://www.jetbrains.com/help/idea/compiling-applications.html#package_into_jar

The JAR file includes:
* JSSC (io.github.java-native:jssc:2.9.4)
* JserialComm v2.6.2 (com.fazecast:jSerialComm:2.6.2)
* SLF4J-JCL v1.7.3 (org.slf4j:slf4j-jcl:1.7.3)

