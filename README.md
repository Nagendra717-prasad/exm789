# exm789


cd Desktop

mvn archetype:generate ^
-DgroupId=com.demo ^
-DartifactId=MyMavenApp ^
-DarchetypeArtifactId=maven-archetype-quickstart ^
-DinteractiveMode=false

cd MyMavenApp

mvn compile

mvn exec:java -Dexec.mainClass="com.demo.App"


cd Desktop 

mkdir pro and cd pro 

gradle init 

gradle build 

gradle run 
