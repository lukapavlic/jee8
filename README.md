# Java/Jakarta EE8
Celovite platfome (Windows Zip)

Datoteke, ki so na voljo:
- [javaee8.zip](http://164.8.250.220/jee8/javaee8.zip) ~970MB [Info](#javaee8)
- [jee8_complete.zip](http://164.8.250.220/jee8/jee8_complete.zip) ~1.21GB [Info](#jee8_complete)
- [jee8_eclipse_wildfly.zip](http://164.8.250.220/jee8/jee8_eclipse_wildfly.zip) ~955MB [Info](#jee8_eclipse_wildfly)
- [jee8_eclipse_wildfly_mysql.zip](http://164.8.250.220/jee8/jee8_eclipse_wildfly_mysql.zip) ~1.02GB [Info](#jee8_eclipse_wildfly_mysql)
- [jee8_eclipse_wildfly_pqsql.zip](http://164.8.250.220/jee8/jee8_eclipse_wildfly_pqsql.zip) ~1.02GB [Info](#jee8_eclipse_wildfly_pqsql)
- [wildfly-19.0.0.Final.standalone.zip](http://164.8.250.220/jee8/wildfly-19.0.0.Final.standalone.zip) ~3MB [Info](#wildfly19_update)



# javaee8
[download](http://164.8.250.220/jee8/javaee8.zip) ~970MB [Info](#link)

### Vsebina paketa:
- JDK 1.8.0
- Apache Maven 3.6.1
- Eclipse 2019-12
- Wildfly 16.0.0
- Postgresql 11.2.2
- PgAdmin 4

### Navodila:

- Razpakirati v **C:\javaee8**
- WildFly admin: u:user, p:user
- Wildfly app user: u:guest, p:guest; role: guest
- Postgresql: u:postgres, p:postgres
- DS JNDI: java:jboss/datasources/knjiznica --> postgresql
- DS JNDI: java:jboss/datasources/database --> mysql (127.0.0.1:13306/database; u:root, p:root)
- Postgresql: u: postgres, p:postgres



# jee8_complete
[download](http://164.8.250.220/jee8/jee8_complete.zip) ~1.21GB

### Vsebina paketa:
- JDK 1.8.0
- Eclipse 2020.03
- Wildfly 19.0.0
- Postgresql 12.2
- PgAdmin 4
- MySql 8
- Demo projekt (Eclipse - run, IntelliJ - testirano na IntelliJIdea2019.3.4 Ultimate - open-run)

### Navodila:

- Razpakirati v **C:\jee8**
- WildFly port: 28080
- WildFly admin: u:user, p:user
- Wildfly app user: u:guest, p:guest; role: guest
- Postgresql: u:postgres, p:postgres
- Mysql: u:root, p:root
- DS JNDI: java:jboss/datasources/mysqlds --> mysql (testdb)
- DS JNDI: java:jboss/datasources/postgresds --> postgresql (testdb)
- Queue JNDI: jms/queue/test
- Topic JNDI: jms/topic/test



# jee8_eclipse_wildfly
[download](http://164.8.250.220/jee8/jee8_eclipse_wildfly.zip) ~955MB

### Vsebina paketa:
- JDK 1.8.0
- Eclipse 2020.03
- Wildfly 19.0.0 (JDBC: MySql, Postgresql)
- Demo projekt (Eclipse - run, IntelliJ - testirano na IntelliJIdea2019.3.4 Ultimate - open-run)

### Navodila:

- Razpakirati v **C:\jee8**
- WildFly port: 28080
- WildFly admin: u:user, p:user
- Wildfly app user: u:guest, p:guest; role: guest
- DS JNDI: java:jboss/datasources/mysqlds --> mysql (127.0.0.1:3306/testdb; u:root, p:root)
- DS JNDI: java:jboss/datasources/postgresds --> postgresql (127.0.0.1:5432/testdb; u:postgres, p:postgres)
- Queue JNDI: jms/queue/test
- Topic JNDI: jms/topic/test



# jee8_eclipse_wildfly_mysql
[download](http://164.8.250.220/jee8/jee8_eclipse_wildfly_mysql.zip) ~1.02GB

### Vsebina paketa:
- JDK 1.8.0
- Eclipse 2020.03
- Wildfly 19.0.0
- MySql 8
- Demo projekt (Eclipse - run, IntelliJ - testirano na IntelliJIdea2019.3.4 Ultimate - open-run)

### Navodila:

- Razpakirati v **C:\jee8**
- WildFly port: 28080
- WildFly admin: u:user, p:user
- Wildfly app user: u:guest, p:guest; role: guest
- Mysql: u:root, p:root
- DS JNDI: java:jboss/datasources/mysqlds --> mysql (testdb)
- DS JNDI: java:jboss/datasources/postgresds --> postgresql (127.0.0.1:5432/testdb; u:postgres, p:postgres)
- Queue JNDI: jms/queue/test
- Topic JNDI: jms/topic/test



# jee8_eclipse_wildfly_pqsql
[download](http://164.8.250.220/jee8/jee8_eclipse_wildfly_pqsql.zip) ~1.02GB

### Vsebina paketa:
- JDK 1.8.0
- Eclipse 2020.03
- Wildfly 19.0.0
- Postgresql 12.2
- PgAdmin 4
- Demo projekt (Eclipse - run, IntelliJ - testirano na IntelliJIdea2019.3.4 Ultimate - open-run)

### Navodila:

- Razpakirati v **C:\jee8**
- WildFly port: 28080
- WildFly admin: u:user, p:user
- Wildfly app user: u:guest, p:guest; role: guest
- Postgresql: u:postgres, p:postgres
- DS JNDI: java:jboss/datasources/mysqlds --> mysql (127.0.0.1:3306/testdb; u:root, p:root)
- DS JNDI: java:jboss/datasources/postgresds --> postgresql (testdb)
- Queue JNDI: jms/queue/test
- Topic JNDI: jms/topic/test



# wildfly19_update
[download](http://164.8.250.220/jee8/wildfly-19.0.0.Final.standalone.zip) ~3MB

Navodila:














## Build log
