# jdni-ldap-server
jdni-ldap-server


修改LdapServer.java 44行OperationInterceptor的参数地址   config.addInMemoryOperationInterceptor(new OperationInterceptor(new URL("url")));

下载到同一目录
wget https://repo1.maven.org/maven2/com/unboundid/unboundid-ldapsdk/3.1.1/unboundid-ldapsdk-3.1.1.jar

编译运行
javac -Djava.ext.dirs=./ LdapServer.java
javac -Djava.ext.dirs=./ LdapServer.java 
