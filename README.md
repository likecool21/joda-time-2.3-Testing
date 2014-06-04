If compile failed with
	Failed to execute goal org.apache.maven.plugins:maven-javadoc-plugin:2.9.1:jar
stuff, then ignore the javadoc compile by using 
$mvn clean install -Dmaven.javadoc.skip=true