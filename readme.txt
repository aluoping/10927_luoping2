创建java项目
mvn archetype:generate -DgroupId=com.hand  -DartifactId=test1  -DarchetypeArtifactId=maven-archetype-quickstart  -DinteractiveMode=false

-DartifactId=test1  表示工程名
-DgroupId=com.hand  表示包名
-DarchetypeArtifactId=maven-archetype-quickstart 以它为模板创建项目
-DinteractiveMode=false  不需要参数


maven创建Web项目

mvn archetype:generate -DgroupId=com.hand -DartifactId=webtest -DarchetypeArtifactId=maven-archetype-webapp -DinteractiveMode=false -DarchetypeCatalog=internal