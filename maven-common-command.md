mvn compile 编译源代码

mvn test-compile 编译测试代码

mvn test 运行测试

mvn package 打包，根据pom.xml打成war或jar
> 如果pom.xml中设置 war，则此命令相当于mvn war:war  
> 如果pom.xml中设置 jar，则此命令相当于mvn jar:jar

mvn install 在本地Repository中安装jar

mvn clean 清除产生的项目

mvn clean deploy -Dmaven.test.skip=true

mvn eclipse:eclipse 生成eclipse项目

mvn idea:idea 生成idea项目

mvn eclipse:clean 清除eclipse的一些系统设置

mvn dependency:sources 下载源码

mvn versions:set -DnewVersion=1.0.2


-DskipTests，不执行测试用例，但编译测试用例类生成相应的class文件至target/test-classes下。

-Dmaven.test.skip=true，不执行测试用例，也不编译测试用例类。
