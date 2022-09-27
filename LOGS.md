masharodionova@MashaRodionova Docker % java -jar db-api.jar

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

masharodionova@MashaRodionova Docker % 
