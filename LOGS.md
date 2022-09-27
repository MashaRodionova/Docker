ionova@MashaRodionova Docker % java -jar db-api.jar

.   ____          _            __ _ _
/\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
\\/  ___)| |_)| | | | | || (_| |  ) ) ) )
'  |____| .__|_| |_|_| |_\__, | / / / /
=========|_|==============|___/=/_/_/_/
:: Spring Boot ::        (v2.2.1.RELEASE)

2022-09-27 15:49:26.980  INFO 41559 --- [           main] ru.netology.dbapi.DbApiApplication       : Starting DbApiApplication v0.0.1-SNAPSHOT on MashaRodionova.local with PID 41559 (/Users/masharodionova/IdeaProjects/Docker/db-api.jar started by masharodionova in /Users/masharodionova/IdeaProjects/Docker)
2022-09-27 15:49:26.985  INFO 41559 --- [           main] ru.netology.dbapi.DbApiApplication       : No active profile set, falling back to default profiles: default
2022-09-27 15:49:28.371  INFO 41559 --- [           main] .s.d.r.c.RepositoryConfigurationDelegate : Bootstrapping Spring Data repositories in DEFAULT mode.
2022-09-27 15:49:28.580  INFO 41559 --- [           main] .s.d.r.c.RepositoryConfigurationDelegate : Finished Spring Data repository scanning in 182ms. Found 1 repository interfaces.
2022-09-27 15:49:29.537  INFO 41559 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'org.springframework.transaction.annotation.ProxyTransactionManagementConfiguration' of type [org.springframework.transaction.annotation.ProxyTransactionManagementConfiguration] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2022-09-27 15:49:30.204  INFO 41559 --- [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat initialized with port(s): 9999 (http)
2022-09-27 15:49:30.231  INFO 41559 --- [           main] o.apache.catalina.core.StandardService   : Starting service [Tomcat]
2022-09-27 15:49:30.231  INFO 41559 --- [           main] org.apache.catalina.core.StandardEngine  : Starting Servlet engine: [Apache Tomcat/9.0.27]
2022-09-27 15:49:30.338  INFO 41559 --- [           main] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring embedded WebApplicationContext
2022-09-27 15:49:30.338  INFO 41559 --- [           main] o.s.web.context.ContextLoader            : Root WebApplicationContext: initialization completed in 3236 ms
2022-09-27 15:49:30.584  WARN 41559 --- [           main] ConfigServletWebServerApplicationContext : Exception encountered during context initialization - cancelling refresh attempt: org.springframework.beans.factory.UnsatisfiedDependencyException: Error creating bean with name 'org.springframework.boot.autoconfigure.orm.jpa.HibernateJpaConfiguration': Unsatisfied dependency expressed through constructor parameter 0; nested exception is org.springframework.beans.factory.BeanCreationException: Error creating bean with name 'dataSource' defined in class path resource [org/springframework/boot/autoconfigure/jdbc/DataSourceConfiguration$Hikari.class]: Bean instantiation via factory method failed; nested exception is org.springframework.beans.BeanInstantiationException: Failed to instantiate [com.zaxxer.hikari.HikariDataSource]: Factory method 'dataSource' threw exception; nested exception is org.springframework.boot.autoconfigure.jdbc.DataSourceProperties$DataSourceBeanCreationException: Failed to determine a suitable driver class
2022-09-27 15:49:30.602  INFO 41559 --- [           main] o.apache.catalina.core.StandardService   : Stopping service [Tomcat]
2022-09-27 15:49:30.657  INFO 41559 --- [           main] ConditionEvaluationReportLoggingListener :

Error starting ApplicationContext. To display the conditions report re-run your application with 'debug' enabled.
2022-09-27 15:49:30.661 ERROR 41559 --- [           main] o.s.b.d.LoggingFailureAnalysisReporter   :

***************************
APPLICATION FAILED TO START
***************************

Description:

Failed to configure a DataSource: no embedded datasource could be configured.

Reason: Failed to determine a suitable driver class


Action:

Consider the following:
If you want an embedded database (H2, HSQL or Derby), please put it on the classpath.
If you have database settings to be loaded from a particular profile you may need to activate it (no profiles are currently active).

masharodionova@MashaRodionova Docker % java -jar db-api.jar

.   ____          _            __ _ _
/\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
\\/  ___)| |_)| | | | | || (_| |  ) ) ) )
'  |____| .__|_| |_|_| |_\__, | / / / /
=========|_|==============|___/=/_/_/_/
:: Spring Boot ::        (v2.2.1.RELEASE)

2022-09-27 16:29:34.662  INFO 43663 --- [           main] ru.netology.dbapi.DbApiApplication       : Starting DbApiApplication v0.0.1-SNAPSHOT on MashaRodionova.local with PID 43663 (/Users/masharodionova/IdeaProjects/Docker/db-api.jar started by masharodionova in /Users/masharodionova/IdeaProjects/Docker)
2022-09-27 16:29:34.667  INFO 43663 --- [           main] ru.netology.dbapi.DbApiApplication       : No active profile set, falling back to default profiles: default
2022-09-27 16:29:36.096  INFO 43663 --- [           main] .s.d.r.c.RepositoryConfigurationDelegate : Bootstrapping Spring Data repositories in DEFAULT mode.
2022-09-27 16:29:36.308  INFO 43663 --- [           main] .s.d.r.c.RepositoryConfigurationDelegate : Finished Spring Data repository scanning in 184ms. Found 1 repository interfaces.
2022-09-27 16:29:37.288  INFO 43663 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'org.springframework.transaction.annotation.ProxyTransactionManagementConfiguration' of type [org.springframework.transaction.annotation.ProxyTransactionManagementConfiguration] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2022-09-27 16:29:37.900  INFO 43663 --- [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat initialized with port(s): 9999 (http)
2022-09-27 16:29:37.920  INFO 43663 --- [           main] o.apache.catalina.core.StandardService   : Starting service [Tomcat]
2022-09-27 16:29:37.920  INFO 43663 --- [           main] org.apache.catalina.core.StandardEngine  : Starting Servlet engine: [Apache Tomcat/9.0.27]
2022-09-27 16:29:38.026  INFO 43663 --- [           main] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring embedded WebApplicationContext
2022-09-27 16:29:38.026  INFO 43663 --- [           main] o.s.web.context.ContextLoader            : Root WebApplicationContext: initialization completed in 3236 ms
2022-09-27 16:29:38.489  INFO 43663 --- [           main] o.hibernate.jpa.internal.util.LogHelper  : HHH000204: Processing PersistenceUnitInfo [name: default]
2022-09-27 16:29:38.712  INFO 43663 --- [           main] org.hibernate.Version                    : HHH000412: Hibernate Core {5.4.8.Final}
2022-09-27 16:29:39.118  INFO 43663 --- [           main] o.hibernate.annotations.common.Version   : HCANN000001: Hibernate Commons Annotations {5.1.0.Final}
2022-09-27 16:29:39.398  INFO 43663 --- [           main] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Starting...
2022-09-27 16:29:39.592 ERROR 43663 --- [           main] com.zaxxer.hikari.pool.HikariPool        : HikariPool-1 - Exception during pool initialization.

org.postgresql.util.PSQLException: FATAL: database "db" does not exist
at org.postgresql.core.v3.QueryExecutorImpl.receiveErrorResponse(QueryExecutorImpl.java:2497) ~[postgresql-42.2.8.jar!/:42.2.8]
at org.postgresql.core.v3.QueryExecutorImpl.readStartupMessages(QueryExecutorImpl.java:2618) ~[postgresql-42.2.8.jar!/:42.2.8]
at org.postgresql.core.v3.QueryExecutorImpl.<init>(QueryExecutorImpl.java:135) ~[postgresql-42.2.8.jar!/:42.2.8]
at org.postgresql.core.v3.ConnectionFactoryImpl.openConnectionImpl(ConnectionFactoryImpl.java:250) ~[postgresql-42.2.8.jar!/:42.2.8]
at org.postgresql.core.ConnectionFactory.openConnection(ConnectionFactory.java:49) ~[postgresql-42.2.8.jar!/:42.2.8]
at org.postgresql.jdbc.PgConnection.<init>(PgConnection.java:195) ~[postgresql-42.2.8.jar!/:42.2.8]
at org.postgresql.Driver.makeConnection(Driver.java:458) ~[postgresql-42.2.8.jar!/:42.2.8]
at org.postgresql.Driver.connect(Driver.java:260) ~[postgresql-42.2.8.jar!/:42.2.8]
at com.zaxxer.hikari.util.DriverDataSource.getConnection(DriverDataSource.java:138) ~[HikariCP-3.4.1.jar!/:na]
at com.zaxxer.hikari.pool.PoolBase.newConnection(PoolBase.java:353) ~[HikariCP-3.4.1.jar!/:na]
at com.zaxxer.hikari.pool.PoolBase.newPoolEntry(PoolBase.java:201) ~[HikariCP-3.4.1.jar!/:na]
at com.zaxxer.hikari.pool.HikariPool.createPoolEntry(HikariPool.java:473) ~[HikariCP-3.4.1.jar!/:na]
at com.zaxxer.hikari.pool.HikariPool.checkFailFast(HikariPool.java:562) ~[HikariCP-3.4.1.jar!/:na]
at com.zaxxer.hikari.pool.HikariPool.<init>(HikariPool.java:115) ~[HikariCP-3.4.1.jar!/:na]
at com.zaxxer.hikari.HikariDataSource.getConnection(HikariDataSource.java:112) ~[HikariCP-3.4.1.jar!/:na]
at org.hibernate.engine.jdbc.connections.internal.DatasourceConnectionProviderImpl.getConnection(DatasourceConnectionProviderImpl.java:122) ~[hibernate-core-5.4.8.Final.jar!/:5.4.8.Final]
at org.hibernate.engine.jdbc.env.internal.JdbcEnvironmentInitiator$ConnectionProviderJdbcConnectionAccess.obtainConnection(JdbcEnvironmentInitiator.java:180) ~[hibernate-core-5.4.8.Final.jar!/:5.4.8.Final]
at org.hibernate.engine.jdbc.env.internal.JdbcEnvironmentInitiator.initiateService(JdbcEnvironmentInitiator.java:68) ~[hibernate-core-5.4.8.Final.jar!/:5.4.8.Final]
at org.hibernate.engine.jdbc.env.internal.JdbcEnvironmentInitiator.initiateService(JdbcEnvironmentInitiator.java:35) ~[hibernate-core-5.4.8.Final.jar!/:5.4.8.Final]
at org.hibernate.boot.registry.internal.StandardServiceRegistryImpl.initiateService(StandardServiceRegistryImpl.java:101) ~[hibernate-core-5.4.8.Final.jar!/:5.4.8.Final]
at org.hibernate.service.internal.AbstractServiceRegistryImpl.createService(AbstractServiceRegistryImpl.java:263) ~[hibernate-core-5.4.8.Final.jar!/:5.4.8.Final]
at org.hibernate.service.internal.AbstractServiceRegistryImpl.initializeService(AbstractServiceRegistryImpl.java:237) ~[hibernate-core-5.4.8.Final.jar!/:5.4.8.Final]
at org.hibernate.service.internal.AbstractServiceRegistryImpl.getService(AbstractServiceRegistryImpl.java:214) ~[hibernate-core-5.4.8.Final.jar!/:5.4.8.Final]
at org.hibernate.id.factory.internal.DefaultIdentifierGeneratorFactory.injectServices(DefaultIdentifierGeneratorFactory.java:152) ~[hibernate-core-5.4.8.Final.jar!/:5.4.8.Final]
at org.hibernate.service.internal.AbstractServiceRegistryImpl.injectDependencies(AbstractServiceRegistryImpl.java:286) ~[hibernate-core-5.4.8.Final.jar!/:5.4.8.Final]
at org.hibernate.service.internal.AbstractServiceRegistryImpl.initializeService(AbstractServiceRegistryImpl.java:243) ~[hibernate-core-5.4.8.Final.jar!/:5.4.8.Final]
at org.hibernate.service.internal.AbstractServiceRegistryImpl.getService(AbstractServiceRegistryImpl.java:214) ~[hibernate-core-5.4.8.Final.jar!/:5.4.8.Final]
at org.hibernate.boot.internal.InFlightMetadataCollectorImpl.<init>(InFlightMetadataCollectorImpl.java:175) ~[hibernate-core-5.4.8.Final.jar!/:5.4.8.Final]
at org.hibernate.boot.model.process.spi.MetadataBuildingProcess.complete(MetadataBuildingProcess.java:118) ~[hibernate-core-5.4.8.Final.jar!/:5.4.8.Final]
at org.hibernate.jpa.boot.internal.EntityManagerFactoryBuilderImpl.metadata(EntityManagerFactoryBuilderImpl.java:1214) ~[hibernate-core-5.4.8.Final.jar!/:5.4.8.Final]
at org.hibernate.jpa.boot.internal.EntityManagerFactoryBuilderImpl.build(EntityManagerFactoryBuilderImpl.java:1245) ~[hibernate-core-5.4.8.Final.jar!/:5.4.8.Final]
at org.springframework.orm.jpa.vendor.SpringHibernateJpaPersistenceProvider.createContainerEntityManagerFactory(SpringHibernateJpaPersistenceProvider.java:58) ~[spring-orm-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
at org.springframework.orm.jpa.LocalContainerEntityManagerFactoryBean.createNativeEntityManagerFactory(LocalContainerEntityManagerFactoryBean.java:365) ~[spring-orm-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
at org.springframework.orm.jpa.AbstractEntityManagerFactoryBean.buildNativeEntityManagerFactory(AbstractEntityManagerFactoryBean.java:391) ~[spring-orm-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
at org.springframework.orm.jpa.AbstractEntityManagerFactoryBean.afterPropertiesSet(AbstractEntityManagerFactoryBean.java:378) ~[spring-orm-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
at org.springframework.orm.jpa.LocalContainerEntityManagerFactoryBean.afterPropertiesSet(LocalContainerEntityManagerFactoryBean.java:341) ~[spring-orm-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.invokeInitMethods(AbstractAutowireCapableBeanFactory.java:1862) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.initializeBean(AbstractAutowireCapableBeanFactory.java:1799) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.doCreateBean(AbstractAutowireCapableBeanFactory.java:595) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.createBean(AbstractAutowireCapableBeanFactory.java:517) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
at org.springframework.beans.factory.support.AbstractBeanFactory.lambda$doGetBean$0(AbstractBeanFactory.java:323) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
at org.springframework.beans.factory.support.DefaultSingletonBeanRegistry.getSingleton(DefaultSingletonBeanRegistry.java:222) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
at org.springframework.beans.factory.support.AbstractBeanFactory.doGetBean(AbstractBeanFactory.java:321) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
at org.springframework.beans.factory.support.AbstractBeanFactory.getBean(AbstractBeanFactory.java:202) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
at org.springframework.context.support.AbstractApplicationContext.getBean(AbstractApplicationContext.java:1108) ~[spring-context-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
at org.springframework.context.support.AbstractApplicationContext.finishBeanFactoryInitialization(AbstractApplicationContext.java:868) ~[spring-context-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:550) ~[spring-context-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
at org.springframework.boot.web.servlet.context.ServletWebServerApplicationContext.refresh(ServletWebServerApplicationContext.java:141) ~[spring-boot-2.2.1.RELEASE.jar!/:2.2.1.RELEASE]
at org.springframework.boot.SpringApplication.refresh(SpringApplication.java:747) ~[spring-boot-2.2.1.RELEASE.jar!/:2.2.1.RELEASE]
at org.springframework.boot.SpringApplication.refreshContext(SpringApplication.java:397) ~[spring-boot-2.2.1.RELEASE.jar!/:2.2.1.RELEASE]
at org.springframework.boot.SpringApplication.run(SpringApplication.java:315) ~[spring-boot-2.2.1.RELEASE.jar!/:2.2.1.RELEASE]
at org.springframework.boot.SpringApplication.run(SpringApplication.java:1226) ~[spring-boot-2.2.1.RELEASE.jar!/:2.2.1.RELEASE]
at org.springframework.boot.SpringApplication.run(SpringApplication.java:1215) ~[spring-boot-2.2.1.RELEASE.jar!/:2.2.1.RELEASE]
at ru.netology.dbapi.DbApiApplication.main(DbApiApplication.java:16) ~[classes!/:0.0.1-SNAPSHOT]
at java.base/jdk.internal.reflect.DirectMethodHandleAccessor.invoke(DirectMethodHandleAccessor.java:104) ~[na:na]
at java.base/java.lang.reflect.Method.invoke(Method.java:577) ~[na:na]
at org.springframework.boot.loader.MainMethodRunner.run(MainMethodRunner.java:48) ~[db-api.jar:0.0.1-SNAPSHOT]
at org.springframework.boot.loader.Launcher.launch(Launcher.java:87) ~[db-api.jar:0.0.1-SNAPSHOT]
at org.springframework.boot.loader.Launcher.launch(Launcher.java:51) ~[db-api.jar:0.0.1-SNAPSHOT]
at org.springframework.boot.loader.JarLauncher.main(JarLauncher.java:52) ~[db-api.jar:0.0.1-SNAPSHOT]

2022-09-27 16:29:39.644  WARN 43663 --- [           main] o.h.e.j.e.i.JdbcEnvironmentInitiator     : HHH000342: Could not obtain connection to query metadata : FATAL: database "db" does not exist
2022-09-27 16:29:39.653  WARN 43663 --- [           main] ConfigServletWebServerApplicationContext : Exception encountered during context initialization - cancelling refresh attempt: org.springframework.beans.factory.BeanCreationException: Error creating bean with name 'entityManagerFactory' defined in class path resource [org/springframework/boot/autoconfigure/orm/jpa/HibernateJpaConfiguration.class]: Invocation of init method failed; nested exception is org.hibernate.service.spi.ServiceException: Unable to create requested service [org.hibernate.engine.jdbc.env.spi.JdbcEnvironment]
2022-09-27 16:29:39.665  INFO 43663 --- [           main] o.apache.catalina.core.StandardService   : Stopping service [Tomcat]
2022-09-27 16:29:39.776  INFO 43663 --- [           main] ConditionEvaluationReportLoggingListener :

Error starting ApplicationContext. To display the conditions report re-run your application with 'debug' enabled.
2022-09-27 16:29:39.781 ERROR 43663 --- [           main] o.s.boot.SpringApplication               : Application run failed

org.springframework.beans.factory.BeanCreationException: Error creating bean with name 'entityManagerFactory' defined in class path resource [org/springframework/boot/autoconfigure/orm/jpa/HibernateJpaConfiguration.class]: Invocation of init method failed; nested exception is org.hibernate.service.spi.ServiceException: Unable to create requested service [org.hibernate.engine.jdbc.env.spi.JdbcEnvironment]
at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.initializeBean(AbstractAutowireCapableBeanFactory.java:1803) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.doCreateBean(AbstractAutowireCapableBeanFactory.java:595) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.createBean(AbstractAutowireCapableBeanFactory.java:517) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
at org.springframework.beans.factory.support.AbstractBeanFactory.lambda$doGetBean$0(AbstractBeanFactory.java:323) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
at org.springframework.beans.factory.support.DefaultSingletonBeanRegistry.getSingleton(DefaultSingletonBeanRegistry.java:222) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
at org.springframework.beans.factory.support.AbstractBeanFactory.doGetBean(AbstractBeanFactory.java:321) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
at org.springframework.beans.factory.support.AbstractBeanFactory.getBean(AbstractBeanFactory.java:202) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
at org.springframework.context.support.AbstractApplicationContext.getBean(AbstractApplicationContext.java:1108) ~[spring-context-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
at org.springframework.context.support.AbstractApplicationContext.finishBeanFactoryInitialization(AbstractApplicationContext.java:868) ~[spring-context-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:550) ~[spring-context-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
at org.springframework.boot.web.servlet.context.ServletWebServerApplicationContext.refresh(ServletWebServerApplicationContext.java:141) ~[spring-boot-2.2.1.RELEASE.jar!/:2.2.1.RELEASE]
at org.springframework.boot.SpringApplication.refresh(SpringApplication.java:747) ~[spring-boot-2.2.1.RELEASE.jar!/:2.2.1.RELEASE]
at org.springframework.boot.SpringApplication.refreshContext(SpringApplication.java:397) ~[spring-boot-2.2.1.RELEASE.jar!/:2.2.1.RELEASE]
at org.springframework.boot.SpringApplication.run(SpringApplication.java:315) ~[spring-boot-2.2.1.RELEASE.jar!/:2.2.1.RELEASE]
at org.springframework.boot.SpringApplication.run(SpringApplication.java:1226) ~[spring-boot-2.2.1.RELEASE.jar!/:2.2.1.RELEASE]
at org.springframework.boot.SpringApplication.run(SpringApplication.java:1215) ~[spring-boot-2.2.1.RELEASE.jar!/:2.2.1.RELEASE]
at ru.netology.dbapi.DbApiApplication.main(DbApiApplication.java:16) ~[classes!/:0.0.1-SNAPSHOT]
at java.base/jdk.internal.reflect.DirectMethodHandleAccessor.invoke(DirectMethodHandleAccessor.java:104) ~[na:na]
at java.base/java.lang.reflect.Method.invoke(Method.java:577) ~[na:na]
at org.springframework.boot.loader.MainMethodRunner.run(MainMethodRunner.java:48) ~[db-api.jar:0.0.1-SNAPSHOT]
at org.springframework.boot.loader.Launcher.launch(Launcher.java:87) ~[db-api.jar:0.0.1-SNAPSHOT]
at org.springframework.boot.loader.Launcher.launch(Launcher.java:51) ~[db-api.jar:0.0.1-SNAPSHOT]
at org.springframework.boot.loader.JarLauncher.main(JarLauncher.java:52) ~[db-api.jar:0.0.1-SNAPSHOT]
Caused by: org.hibernate.service.spi.ServiceException: Unable to create requested service [org.hibernate.engine.jdbc.env.spi.JdbcEnvironment]
at org.hibernate.service.internal.AbstractServiceRegistryImpl.createService(AbstractServiceRegistryImpl.java:275) ~[hibernate-core-5.4.8.Final.jar!/:5.4.8.Final]
at org.hibernate.service.internal.AbstractServiceRegistryImpl.initializeService(AbstractServiceRegistryImpl.java:237) ~[hibernate-core-5.4.8.Final.jar!/:5.4.8.Final]
at org.hibernate.service.internal.AbstractServiceRegistryImpl.getService(AbstractServiceRegistryImpl.java:214) ~[hibernate-core-5.4.8.Final.jar!/:5.4.8.Final]
at org.hibernate.id.factory.internal.DefaultIdentifierGeneratorFactory.injectServices(DefaultIdentifierGeneratorFactory.java:152) ~[hibernate-core-5.4.8.Final.jar!/:5.4.8.Final]
at org.hibernate.service.internal.AbstractServiceRegistryImpl.injectDependencies(AbstractServiceRegistryImpl.java:286) ~[hibernate-core-5.4.8.Final.jar!/:5.4.8.Final]
at org.hibernate.service.internal.AbstractServiceRegistryImpl.initializeService(AbstractServiceRegistryImpl.java:243) ~[hibernate-core-5.4.8.Final.jar!/:5.4.8.Final]
at org.hibernate.service.internal.AbstractServiceRegistryImpl.getService(AbstractServiceRegistryImpl.java:214) ~[hibernate-core-5.4.8.Final.jar!/:5.4.8.Final]
at org.hibernate.boot.internal.InFlightMetadataCollectorImpl.<init>(InFlightMetadataCollectorImpl.java:175) ~[hibernate-core-5.4.8.Final.jar!/:5.4.8.Final]
at org.hibernate.boot.model.process.spi.MetadataBuildingProcess.complete(MetadataBuildingProcess.java:118) ~[hibernate-core-5.4.8.Final.jar!/:5.4.8.Final]
at org.hibernate.jpa.boot.internal.EntityManagerFactoryBuilderImpl.metadata(EntityManagerFactoryBuilderImpl.java:1214) ~[hibernate-core-5.4.8.Final.jar!/:5.4.8.Final]
at org.hibernate.jpa.boot.internal.EntityManagerFactoryBuilderImpl.build(EntityManagerFactoryBuilderImpl.java:1245) ~[hibernate-core-5.4.8.Final.jar!/:5.4.8.Final]
at org.springframework.orm.jpa.vendor.SpringHibernateJpaPersistenceProvider.createContainerEntityManagerFactory(SpringHibernateJpaPersistenceProvider.java:58) ~[spring-orm-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
at org.springframework.orm.jpa.LocalContainerEntityManagerFactoryBean.createNativeEntityManagerFactory(LocalContainerEntityManagerFactoryBean.java:365) ~[spring-orm-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
at org.springframework.orm.jpa.AbstractEntityManagerFactoryBean.buildNativeEntityManagerFactory(AbstractEntityManagerFactoryBean.java:391) ~[spring-orm-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
at org.springframework.orm.jpa.AbstractEntityManagerFactoryBean.afterPropertiesSet(AbstractEntityManagerFactoryBean.java:378) ~[spring-orm-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
at org.springframework.orm.jpa.LocalContainerEntityManagerFactoryBean.afterPropertiesSet(LocalContainerEntityManagerFactoryBean.java:341) ~[spring-orm-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.invokeInitMethods(AbstractAutowireCapableBeanFactory.java:1862) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.initializeBean(AbstractAutowireCapableBeanFactory.java:1799) ~[spring-beans-5.2.1.RELEASE.jar!/:5.2.1.RELEASE]
... 22 common frames omitted
Caused by: org.hibernate.HibernateException: Access to DialectResolutionInfo cannot be null when 'hibernate.dialect' not set
at org.hibernate.engine.jdbc.dialect.internal.DialectFactoryImpl.determineDialect(DialectFactoryImpl.java:100) ~[hibernate-core-5.4.8.Final.jar!/:5.4.8.Final]
at org.hibernate.engine.jdbc.dialect.internal.DialectFactoryImpl.buildDialect(DialectFactoryImpl.java:54) ~[hibernate-core-5.4.8.Final.jar!/:5.4.8.Final]
at org.hibernate.engine.jdbc.env.internal.JdbcEnvironmentInitiator.initiateService(JdbcEnvironmentInitiator.java:137) ~[hibernate-core-5.4.8.Final.jar!/:5.4.8.Final]
at org.hibernate.engine.jdbc.env.internal.JdbcEnvironmentInitiator.initiateService(JdbcEnvironmentInitiator.java:35) ~[hibernate-core-5.4.8.Final.jar!/:5.4.8.Final]
at org.hibernate.boot.registry.internal.StandardServiceRegistryImpl.initiateService(StandardServiceRegistryImpl.java:101) ~[hibernate-core-5.4.8.Final.jar!/:5.4.8.Final]
at org.hibernate.service.internal.AbstractServiceRegistryImpl.createService(AbstractServiceRegistryImpl.java:263) ~[hibernate-core-5.4.8.Final.jar!/:5.4.8.Final]
... 39 common frames omitted

masharodionova@MashaRodionova Docker % 
