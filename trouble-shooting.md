trouble-shooting

#1.  Type javax.xml.bind.JAXBContext not present

**java.lang.TypeNotPresentException: Type javax.xml.bind.JAXBContext not present**



```
"C:\Program Files\Java\jdk-11.0.6\bin\java.exe" -XX:TieredStopAtLevel=1 -noverify -Dspring.output.ansi.enabled=always -Dcom.sun.management.jmxremote -Dspring.jmx.enabled=true -Dspring.liveBeansView.mbeanDomain -Dspring.application.admin.enabled=true "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA 2019.3.4\lib\idea_rt.jar=51826:C:\Program Files\JetBrains\IntelliJ IDEA 2019.3.4\bin" -Dfile.encoding=UTF-8 -classpath "F:\daily shell\spring-cloud-family\demo\cloud-docker\spring-cloud-docker-microservice-book-code-master\microservice-discovery-eureka\target\classes;C:\Users\will\.m2\repository\org\springframework\cloud\spring-cloud-starter-netflix-eureka-server\1.4.0.RELEASE\spring-cloud-starter-netflix-eureka-server-1.4.0.RELEASE.jar;C:\Users\will\.m2\repository\org\springframework\cloud\spring-cloud-starter\1.3.0.RELEASE\spring-cloud-starter-1.3.0.RELEASE.jar;C:\Users\will\.m2\repository\org\springframework\boot\spring-boot-starter\1.5.9.RELEASE\spring-boot-starter-1.5.9.RELEASE.jar;C:\Users\will\.m2\repository\org\springframework\boot\spring-boot\1.5.9.RELEASE\spring-boot-1.5.9.RELEASE.jar;C:\Users\will\.m2\repository\org\springframework\spring-context\4.3.13.RELEASE\spring-context-4.3.13.RELEASE.jar;C:\Users\will\.m2\repository\org\springframework\boot\spring-boot-autoconfigure\1.5.9.RELEASE\spring-boot-autoconfigure-1.5.9.RELEASE.jar;C:\Users\will\.m2\repository\org\springframework\boot\spring-boot-starter-logging\1.5.9.RELEASE\spring-boot-starter-logging-1.5.9.RELEASE.jar;C:\Users\will\.m2\repository\ch\qos\logback\logback-classic\1.1.11\logback-classic-1.1.11.jar;C:\Users\will\.m2\repository\ch\qos\logback\logback-core\1.1.11\logback-core-1.1.11.jar;C:\Users\will\.m2\repository\org\slf4j\jcl-over-slf4j\1.7.25\jcl-over-slf4j-1.7.25.jar;C:\Users\will\.m2\repository\org\slf4j\jul-to-slf4j\1.7.25\jul-to-slf4j-1.7.25.jar;C:\Users\will\.m2\repository\org\slf4j\log4j-over-slf4j\1.7.25\log4j-over-slf4j-1.7.25.jar;C:\Users\will\.m2\repository\org\springframework\spring-core\4.3.13.RELEASE\spring-core-4.3.13.RELEASE.jar;C:\Users\will\.m2\repository\org\yaml\snakeyaml\1.17\snakeyaml-1.17.jar;C:\Users\will\.m2\repository\org\springframework\cloud\spring-cloud-context\1.3.0.RELEASE\spring-cloud-context-1.3.0.RELEASE.jar;C:\Users\will\.m2\repository\org\springframework\security\spring-security-crypto\4.2.3.RELEASE\spring-security-crypto-4.2.3.RELEASE.jar;C:\Users\will\.m2\repository\org\springframework\cloud\spring-cloud-commons\1.3.0.RELEASE\spring-cloud-commons-1.3.0.RELEASE.jar;C:\Users\will\.m2\repository\org\apache\httpcomponents\httpclient\4.5.3\httpclient-4.5.3.jar;C:\Users\will\.m2\repository\org\apache\httpcomponents\httpcore\4.4.8\httpcore-4.4.8.jar;C:\Users\will\.m2\repository\commons-codec\commons-codec\1.10\commons-codec-1.10.jar;C:\Users\will\.m2\repository\org\springframework\security\spring-security-rsa\1.0.3.RELEASE\spring-security-rsa-1.0.3.RELEASE.jar;C:\Users\will\.m2\repository\org\bouncycastle\bcpkix-jdk15on\1.55\bcpkix-jdk15on-1.55.jar;C:\Users\will\.m2\repository\org\bouncycastle\bcprov-jdk15on\1.55\bcprov-jdk15on-1.55.jar;C:\Users\will\.m2\repository\org\springframework\cloud\spring-cloud-netflix-eureka-server\1.4.0.RELEASE\spring-cloud-netflix-eureka-server-1.4.0.RELEASE.jar;C:\Users\will\.m2\repository\org\springframework\boot\spring-boot-starter-web\1.5.9.RELEASE\spring-boot-starter-web-1.5.9.RELEASE.jar;C:\Users\will\.m2\repository\org\springframework\boot\spring-boot-starter-tomcat\1.5.9.RELEASE\spring-boot-starter-tomcat-1.5.9.RELEASE.jar;C:\Users\will\.m2\repository\org\apache\tomcat\embed\tomcat-embed-core\8.5.23\tomcat-embed-core-8.5.23.jar;C:\Users\will\.m2\repository\org\apache\tomcat\tomcat-annotations-api\8.5.23\tomcat-annotations-api-8.5.23.jar;C:\Users\will\.m2\repository\org\apache\tomcat\embed\tomcat-embed-el\8.5.23\tomcat-embed-el-8.5.23.jar;C:\Users\will\.m2\repository\org\apache\tomcat\embed\tomcat-embed-websocket\8.5.23\tomcat-embed-websocket-8.5.23.jar;C:\Users\will\.m2\repository\org\hibernate\hibernate-validator\5.3.6.Final\hibernate-validator-5.3.6.Final.jar;C:\Users\will\.m2\repository\javax\validation\validation-api\1.1.0.Final\validation-api-1.1.0.Final.jar;C:\Users\will\.m2\repository\org\jboss\logging\jboss-logging\3.3.1.Final\jboss-logging-3.3.1.Final.jar;C:\Users\will\.m2\repository\com\fasterxml\classmate\1.3.4\classmate-1.3.4.jar;C:\Users\will\.m2\repository\org\springframework\spring-web\4.3.13.RELEASE\spring-web-4.3.13.RELEASE.jar;C:\Users\will\.m2\repository\org\springframework\spring-aop\4.3.13.RELEASE\spring-aop-4.3.13.RELEASE.jar;C:\Users\will\.m2\repository\org\springframework\spring-beans\4.3.13.RELEASE\spring-beans-4.3.13.RELEASE.jar;C:\Users\will\.m2\repository\org\springframework\spring-webmvc\4.3.13.RELEASE\spring-webmvc-4.3.13.RELEASE.jar;C:\Users\will\.m2\repository\org\springframework\spring-expression\4.3.13.RELEASE\spring-expression-4.3.13.RELEASE.jar;C:\Users\will\.m2\repository\org\springframework\boot\spring-boot-starter-actuator\1.5.9.RELEASE\spring-boot-starter-actuator-1.5.9.RELEASE.jar;C:\Users\will\.m2\repository\org\springframework\boot\spring-boot-actuator\1.5.9.RELEASE\spring-boot-actuator-1.5.9.RELEASE.jar;C:\Users\will\.m2\repository\org\springframework\boot\spring-boot-starter-freemarker\1.5.9.RELEASE\spring-boot-starter-freemarker-1.5.9.RELEASE.jar;C:\Users\will\.m2\repository\org\freemarker\freemarker\2.3.27-incubating\freemarker-2.3.27-incubating.jar;C:\Users\will\.m2\repository\org\springframework\spring-context-support\4.3.13.RELEASE\spring-context-support-4.3.13.RELEASE.jar;C:\Users\will\.m2\repository\org\springframework\cloud\spring-cloud-netflix-core\1.4.0.RELEASE\spring-cloud-netflix-core-1.4.0.RELEASE.jar;C:\Users\will\.m2\repository\org\springframework\cloud\spring-cloud-netflix-eureka-client\1.4.0.RELEASE\spring-cloud-netflix-eureka-client-1.4.0.RELEASE.jar;C:\Users\will\.m2\repository\com\netflix\eureka\eureka-client\1.7.0\eureka-client-1.7.0.jar;C:\Users\will\.m2\repository\org\codehaus\jettison\jettison\1.3.7\jettison-1.3.7.jar;C:\Users\will\.m2\repository\stax\stax-api\1.0.1\stax-api-1.0.1.jar;C:\Users\will\.m2\repository\com\netflix\netflix-commons\netflix-eventbus\0.3.0\netflix-eventbus-0.3.0.jar;C:\Users\will\.m2\repository\com\netflix\netflix-commons\netflix-infix\0.3.0\netflix-infix-0.3.0.jar;C:\Users\will\.m2\repository\commons-jxpath\commons-jxpath\1.3\commons-jxpath-1.3.jar;C:\Users\will\.m2\repository\joda-time\joda-time\2.9.9\joda-time-2.9.9.jar;C:\Users\will\.m2\repository\org\antlr\antlr-runtime\3.4\antlr-runtime-3.4.jar;C:\Users\will\.m2\repository\org\antlr\stringtemplate\3.2.1\stringtemplate-3.2.1.jar;C:\Users\will\.m2\repository\antlr\antlr\2.7.7\antlr-2.7.7.jar;C:\Users\will\.m2\repository\com\google\code\gson\gson\2.8.2\gson-2.8.2.jar;C:\Users\will\.m2\repository\org\apache\commons\commons-math\2.2\commons-math-2.2.jar;C:\Users\will\.m2\repository\javax\ws\rs\jsr311-api\1.1.1\jsr311-api-1.1.1.jar;C:\Users\will\.m2\repository\com\netflix\servo\servo-core\0.10.1\servo-core-0.10.1.jar;C:\Users\will\.m2\repository\com\netflix\servo\servo-internal\0.10.1\servo-internal-0.10.1.jar;C:\Users\will\.m2\repository\com\sun\jersey\jersey-core\1.19.1\jersey-core-1.19.1.jar;C:\Users\will\.m2\repository\com\sun\jersey\jersey-client\1.19.1\jersey-client-1.19.1.jar;C:\Users\will\.m2\repository\com\sun\jersey\contribs\jersey-apache-client4\1.19.1\jersey-apache-client4-1.19.1.jar;C:\Users\will\.m2\repository\com\google\inject\guice\4.1.0\guice-4.1.0.jar;C:\Users\will\.m2\repository\aopalliance\aopalliance\1.0\aopalliance-1.0.jar;C:\Users\will\.m2\repository\com\sun\jersey\jersey-servlet\1.19.1\jersey-servlet-1.19.1.jar;C:\Users\will\.m2\repository\com\sun\jersey\jersey-server\1.19.1\jersey-server-1.19.1.jar;C:\Users\will\.m2\repository\com\netflix\eureka\eureka-core\1.7.0\eureka-core-1.7.0.jar;C:\Users\will\.m2\repository\org\codehaus\woodstox\woodstox-core-asl\4.4.1\woodstox-core-asl-4.4.1.jar;C:\Users\will\.m2\repository\javax\xml\stream\stax-api\1.0-2\stax-api-1.0-2.jar;C:\Users\will\.m2\repository\com\netflix\archaius\archaius-core\0.7.4\archaius-core-0.7.4.jar;C:\Users\will\.m2\repository\com\google\code\findbugs\jsr305\3.0.1\jsr305-3.0.1.jar;C:\Users\will\.m2\repository\javax\inject\javax.inject\1\javax.inject-1.jar;C:\Users\will\.m2\repository\com\fasterxml\jackson\dataformat\jackson-dataformat-xml\2.8.10\jackson-dataformat-xml-2.8.10.jar;C:\Users\will\.m2\repository\com\fasterxml\jackson\module\jackson-module-jaxb-annotations\2.8.10\jackson-module-jaxb-annotations-2.8.10.jar;C:\Users\will\.m2\repository\org\codehaus\woodstox\stax2-api\3.1.4\stax2-api-3.1.4.jar;C:\Users\will\.m2\repository\com\fasterxml\woodstox\woodstox-core\5.0.3\woodstox-core-5.0.3.jar;C:\Users\will\.m2\repository\com\thoughtworks\xstream\xstream\1.4.9\xstream-1.4.9.jar;C:\Users\will\.m2\repository\xmlpull\xmlpull\1.1.3.1\xmlpull-1.1.3.1.jar;C:\Users\will\.m2\repository\xpp3\xpp3_min\1.1.4c\xpp3_min-1.1.4c.jar;C:\Users\will\.m2\repository\org\springframework\cloud\spring-cloud-starter-netflix-archaius\1.4.0.RELEASE\spring-cloud-starter-netflix-archaius-1.4.0.RELEASE.jar;C:\Users\will\.m2\repository\commons-configuration\commons-configuration\1.8\commons-configuration-1.8.jar;C:\Users\will\.m2\repository\commons-lang\commons-lang\2.6\commons-lang-2.6.jar;C:\Users\will\.m2\repository\com\fasterxml\jackson\core\jackson-annotations\2.8.0\jackson-annotations-2.8.0.jar;C:\Users\will\.m2\repository\com\fasterxml\jackson\core\jackson-core\2.8.10\jackson-core-2.8.10.jar;C:\Users\will\.m2\repository\com\fasterxml\jackson\core\jackson-databind\2.8.10\jackson-databind-2.8.10.jar;C:\Users\will\.m2\repository\com\google\guava\guava\18.0\guava-18.0.jar;C:\Users\will\.m2\repository\org\springframework\cloud\spring-cloud-starter-netflix-ribbon\1.4.0.RELEASE\spring-cloud-starter-netflix-ribbon-1.4.0.RELEASE.jar;C:\Users\will\.m2\repository\com\netflix\ribbon\ribbon\2.2.4\ribbon-2.2.4.jar;C:\Users\will\.m2\repository\com\netflix\ribbon\ribbon-transport\2.2.4\ribbon-transport-2.2.4.jar;C:\Users\will\.m2\repository\io\reactivex\rxnetty-contexts\0.4.9\rxnetty-contexts-0.4.9.jar;C:\Users\will\.m2\repository\io\reactivex\rxnetty-servo\0.4.9\rxnetty-servo-0.4.9.jar;C:\Users\will\.m2\repository\com\netflix\hystrix\hystrix-core\1.5.12\hystrix-core-1.5.12.jar;C:\Users\will\.m2\repository\org\hdrhistogram\HdrHistogram\2.1.9\HdrHistogram-2.1.9.jar;C:\Users\will\.m2\repository\io\reactivex\rxnetty\0.4.9\rxnetty-0.4.9.jar;C:\Users\will\.m2\repository\io\netty\netty-codec-http\4.0.27.Final\netty-codec-http-4.0.27.Final.jar;C:\Users\will\.m2\repository\io\netty\netty-codec\4.0.27.Final\netty-codec-4.0.27.Final.jar;C:\Users\will\.m2\repository\io\netty\netty-handler\4.0.27.Final\netty-handler-4.0.27.Final.jar;C:\Users\will\.m2\repository\io\netty\netty-transport-native-epoll\4.0.27.Final\netty-transport-native-epoll-4.0.27.Final.jar;C:\Users\will\.m2\repository\io\netty\netty-common\4.0.27.Final\netty-common-4.0.27.Final.jar;C:\Users\will\.m2\repository\io\netty\netty-buffer\4.0.27.Final\netty-buffer-4.0.27.Final.jar;C:\Users\will\.m2\repository\io\netty\netty-transport\4.0.27.Final\netty-transport-4.0.27.Final.jar;C:\Users\will\.m2\repository\com\netflix\ribbon\ribbon-core\2.2.4\ribbon-core-2.2.4.jar;C:\Users\will\.m2\repository\com\netflix\ribbon\ribbon-httpclient\2.2.4\ribbon-httpclient-2.2.4.jar;C:\Users\will\.m2\repository\commons-collections\commons-collections\3.2.2\commons-collections-3.2.2.jar;C:\Users\will\.m2\repository\com\netflix\netflix-commons\netflix-commons-util\0.1.1\netflix-commons-util-0.1.1.jar;C:\Users\will\.m2\repository\com\netflix\ribbon\ribbon-loadbalancer\2.2.4\ribbon-loadbalancer-2.2.4.jar;C:\Users\will\.m2\repository\com\netflix\netflix-commons\netflix-statistics\0.1.1\netflix-statistics-0.1.1.jar;C:\Users\will\.m2\repository\io\reactivex\rxjava\1.2.0\rxjava-1.2.0.jar;C:\Users\will\.m2\repository\com\netflix\ribbon\ribbon-eureka\2.2.4\ribbon-eureka-2.2.4.jar;C:\Users\will\.m2\repository\org\slf4j\slf4j-api\1.7.25\slf4j-api-1.7.25.jar" com.itmuch.cloud.study.EurekaApplication
2020-04-29 09:01:03.763  INFO 21052 --- [           main] o.s.core.annotation.AnnotationUtils      : Failed to introspect annotations on [class org.springframework.cloud.netflix.eureka.config.EurekaDiscoveryClientConfigServiceBootstrapConfiguration]: java.lang.IllegalStateException: Could not obtain annotation attribute value for public abstract java.lang.Class[] org.springframework.boot.autoconfigure.condition.ConditionalOnClass.value()
2020-04-29 09:01:03.768  INFO 21052 --- [           main] s.c.a.AnnotationConfigApplicationContext : Refreshing org.springframework.context.annotation.AnnotationConfigApplicationContext@758705fa: startup date [Wed Apr 29 09:01:03 CST 2020]; root of context hierarchy
WARNING: An illegal reflective access operation has occurred
WARNING: Illegal reflective access by org.springframework.cglib.core.ReflectUtils$1 (file:/C:/Users/will/.m2/repository/org/springframework/spring-core/4.3.13.RELEASE/spring-core-4.3.13.RELEASE.jar) to method java.lang.ClassLoader.defineClass(java.lang.String,byte[],int,int,java.security.ProtectionDomain)
WARNING: Please consider reporting this to the maintainers of org.springframework.cglib.core.ReflectUtils$1
WARNING: Use --illegal-access=warn to enable warnings of further illegal reflective access operations
WARNING: All illegal access operations will be denied in a future release
2020-04-29 09:01:03.886  INFO 21052 --- [           main] f.a.AutowiredAnnotationBeanPostProcessor : JSR-330 'javax.inject.Inject' annotation found and supported for autowiring
2020-04-29 09:01:03.908  INFO 21052 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'configurationPropertiesRebinderAutoConfiguration' of type [org.springframework.cloud.autoconfigure.ConfigurationPropertiesRebinderAutoConfiguration$$EnhancerBySpringCGLIB$$e5d843b7] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)

  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/
 :: Spring Boot ::        (v1.5.9.RELEASE)

2020-04-29 09:01:04.836  INFO 21052 --- [           main] c.itmuch.cloud.study.EurekaApplication   : No active profile set, falling back to default profiles: default
2020-04-29 09:01:04.844  INFO 21052 --- [           main] ationConfigEmbeddedWebApplicationContext : Refreshing org.springframework.boot.context.embedded.AnnotationConfigEmbeddedWebApplicationContext@c27d163: startup date [Wed Apr 29 09:01:04 CST 2020]; parent: org.springframework.context.annotation.AnnotationConfigApplicationContext@758705fa
2020-04-29 09:01:05.444  INFO 21052 --- [           main] o.s.cloud.context.scope.GenericScope     : BeanFactory id=730cc2ea-ea78-3d13-9ef0-a1a43b1ad6fb
2020-04-29 09:01:05.457  INFO 21052 --- [           main] f.a.AutowiredAnnotationBeanPostProcessor : JSR-330 'javax.inject.Inject' annotation found and supported for autowiring
2020-04-29 09:01:05.495  INFO 21052 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'org.springframework.cloud.netflix.metrics.MetricsInterceptorConfiguration$MetricsRestTemplateConfiguration' of type [org.springframework.cloud.netflix.metrics.MetricsInterceptorConfiguration$MetricsRestTemplateConfiguration$$EnhancerBySpringCGLIB$$fbeae6fb] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-04-29 09:01:05.501  INFO 21052 --- [           main] trationDelegate$BeanPostProcessorChecker : Bean 'org.springframework.cloud.autoconfigure.ConfigurationPropertiesRebinderAutoConfiguration' of type [org.springframework.cloud.autoconfigure.ConfigurationPropertiesRebinderAutoConfiguration$$EnhancerBySpringCGLIB$$e5d843b7] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-04-29 09:01:05.684  INFO 21052 --- [           main] s.b.c.e.t.TomcatEmbeddedServletContainer : Tomcat initialized with port(s): 8761 (http)
2020-04-29 09:01:05.692  INFO 21052 --- [           main] o.apache.catalina.core.StandardService   : Starting service [Tomcat]
2020-04-29 09:01:05.693  INFO 21052 --- [           main] org.apache.catalina.core.StandardEngine  : Starting Servlet Engine: Apache Tomcat/8.5.23
2020-04-29 09:01:05.803  INFO 21052 --- [ost-startStop-1] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring embedded WebApplicationContext
2020-04-29 09:01:05.804  INFO 21052 --- [ost-startStop-1] o.s.web.context.ContextLoader            : Root WebApplicationContext: initialization completed in 960 ms
2020-04-29 09:01:06.327  INFO 21052 --- [ost-startStop-1] o.s.b.w.servlet.FilterRegistrationBean   : Mapping filter: 'metricsFilter' to: [/*]
2020-04-29 09:01:06.327  INFO 21052 --- [ost-startStop-1] o.s.b.w.servlet.FilterRegistrationBean   : Mapping filter: 'characterEncodingFilter' to: [/*]
2020-04-29 09:01:06.327  INFO 21052 --- [ost-startStop-1] o.s.b.w.servlet.FilterRegistrationBean   : Mapping filter: 'hiddenHttpMethodFilter' to: [/*]
2020-04-29 09:01:06.327  INFO 21052 --- [ost-startStop-1] o.s.b.w.servlet.FilterRegistrationBean   : Mapping filter: 'httpPutFormContentFilter' to: [/*]
2020-04-29 09:01:06.327  INFO 21052 --- [ost-startStop-1] o.s.b.w.servlet.FilterRegistrationBean   : Mapping filter: 'requestContextFilter' to: [/*]
2020-04-29 09:01:06.327  INFO 21052 --- [ost-startStop-1] o.s.b.w.servlet.FilterRegistrationBean   : Mapping filter: 'webRequestTraceFilter' to: [/*]
2020-04-29 09:01:06.327  INFO 21052 --- [ost-startStop-1] o.s.b.w.servlet.FilterRegistrationBean   : Mapping filter: 'servletContainer' to urls: [/eureka/*]
2020-04-29 09:01:06.327  INFO 21052 --- [ost-startStop-1] o.s.b.w.servlet.FilterRegistrationBean   : Mapping filter: 'applicationContextIdFilter' to: [/*]
2020-04-29 09:01:06.327  INFO 21052 --- [ost-startStop-1] o.s.b.w.servlet.ServletRegistrationBean  : Mapping servlet: 'dispatcherServlet' to [/]
2020-04-29 09:01:06.381  INFO 21052 --- [ost-startStop-1] c.s.j.s.i.a.WebApplicationImpl           : Initiating Jersey application, version 'Jersey: 1.19.1 03/11/2016 02:08 PM'
2020-04-29 09:01:06.436 ERROR 21052 --- [ost-startStop-1] o.a.c.c.C.[Tomcat].[localhost].[/]       : Exception starting filter [servletContainer]

java.lang.TypeNotPresentException: Type javax.xml.bind.JAXBContext not present
	at java.base/sun.reflect.generics.factory.CoreReflectionFactory.makeNamedType(CoreReflectionFactory.java:117) ~[na:na]
	at java.base/sun.reflect.generics.visitor.Reifier.visitClassTypeSignature(Reifier.java:125) ~[na:na]
	at java.base/sun.reflect.generics.tree.ClassTypeSignature.accept(ClassTypeSignature.java:49) ~[na:na]
	at java.base/sun.reflect.generics.visitor.Reifier.reifyTypeArguments(Reifier.java:68) ~[na:na]
	at java.base/sun.reflect.generics.visitor.Reifier.visitClassTypeSignature(Reifier.java:138) ~[na:na]
	at java.base/sun.reflect.generics.tree.ClassTypeSignature.accept(ClassTypeSignature.java:49) ~[na:na]
	at java.base/sun.reflect.generics.repository.ClassRepository.computeSuperInterfaces(ClassRepository.java:117) ~[na:na]
	at java.base/sun.reflect.generics.repository.ClassRepository.getSuperInterfaces(ClassRepository.java:95) ~[na:na]
	at java.base/java.lang.Class.getGenericInterfaces(Class.java:1137) ~[na:na]
	at com.sun.jersey.core.reflection.ReflectionHelper.getClass(ReflectionHelper.java:629) ~[jersey-core-1.19.1.jar:1.19.1]
	at com.sun.jersey.core.reflection.ReflectionHelper.getClass(ReflectionHelper.java:625) ~[jersey-core-1.19.1.jar:1.19.1]
	at com.sun.jersey.core.spi.factory.ContextResolverFactory.getParameterizedType(ContextResolverFactory.java:202) ~[jersey-core-1.19.1.jar:1.19.1]
	at com.sun.jersey.core.spi.factory.ContextResolverFactory.init(ContextResolverFactory.java:89) ~[jersey-core-1.19.1.jar:1.19.1]
	at com.sun.jersey.server.impl.application.WebApplicationImpl._initiate(WebApplicationImpl.java:1332) ~[jersey-server-1.19.1.jar:1.19.1]
	at com.sun.jersey.server.impl.application.WebApplicationImpl.access$700(WebApplicationImpl.java:180) ~[jersey-server-1.19.1.jar:1.19.1]
	at com.sun.jersey.server.impl.application.WebApplicationImpl$13.f(WebApplicationImpl.java:799) ~[jersey-server-1.19.1.jar:1.19.1]
	at com.sun.jersey.server.impl.application.WebApplicationImpl$13.f(WebApplicationImpl.java:795) ~[jersey-server-1.19.1.jar:1.19.1]
	at com.sun.jersey.spi.inject.Errors.processWithErrors(Errors.java:193) ~[jersey-core-1.19.1.jar:1.19.1]
	at com.sun.jersey.server.impl.application.WebApplicationImpl.initiate(WebApplicationImpl.java:795) ~[jersey-server-1.19.1.jar:1.19.1]
	at com.sun.jersey.server.impl.application.WebApplicationImpl.initiate(WebApplicationImpl.java:790) ~[jersey-server-1.19.1.jar:1.19.1]
	at com.sun.jersey.spi.container.servlet.ServletContainer.initiate(ServletContainer.java:509) ~[jersey-servlet-1.19.1.jar:1.19.1]
	at com.sun.jersey.spi.container.servlet.ServletContainer$InternalWebComponent.initiate(ServletContainer.java:339) ~[jersey-servlet-1.19.1.jar:1.19.1]
	at com.sun.jersey.spi.container.servlet.WebComponent.load(WebComponent.java:605) ~[jersey-servlet-1.19.1.jar:1.19.1]
	at com.sun.jersey.spi.container.servlet.WebComponent.init(WebComponent.java:207) ~[jersey-servlet-1.19.1.jar:1.19.1]
	at com.sun.jersey.spi.container.servlet.ServletContainer.init(ServletContainer.java:394) ~[jersey-servlet-1.19.1.jar:1.19.1]
	at com.sun.jersey.spi.container.servlet.ServletContainer.init(ServletContainer.java:744) ~[jersey-servlet-1.19.1.jar:1.19.1]
	at org.apache.catalina.core.ApplicationFilterConfig.initFilter(ApplicationFilterConfig.java:285) ~[tomcat-embed-core-8.5.23.jar:8.5.23]
	at org.apache.catalina.core.ApplicationFilterConfig.<init>(ApplicationFilterConfig.java:112) ~[tomcat-embed-core-8.5.23.jar:8.5.23]
	at org.apache.catalina.core.StandardContext.filterStart(StandardContext.java:4591) ~[tomcat-embed-core-8.5.23.jar:8.5.23]
	at org.apache.catalina.core.StandardContext.startInternal(StandardContext.java:5233) ~[tomcat-embed-core-8.5.23.jar:8.5.23]
	at org.apache.catalina.util.LifecycleBase.start(LifecycleBase.java:150) ~[tomcat-embed-core-8.5.23.jar:8.5.23]
	at org.apache.catalina.core.ContainerBase$StartChild.call(ContainerBase.java:1419) ~[tomcat-embed-core-8.5.23.jar:8.5.23]
	at org.apache.catalina.core.ContainerBase$StartChild.call(ContainerBase.java:1409) ~[tomcat-embed-core-8.5.23.jar:8.5.23]
	at java.base/java.util.concurrent.FutureTask.run(FutureTask.java:264) ~[na:na]
	at java.base/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1128) ~[na:na]
	at java.base/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:628) ~[na:na]
	at java.base/java.lang.Thread.run(Thread.java:834) ~[na:na]
Caused by: java.lang.ClassNotFoundException: javax.xml.bind.JAXBContext
	at java.base/jdk.internal.loader.BuiltinClassLoader.loadClass(BuiltinClassLoader.java:581) ~[na:na]
	at java.base/jdk.internal.loader.ClassLoaders$AppClassLoader.loadClass(ClassLoaders.java:178) ~[na:na]
	at java.base/java.lang.ClassLoader.loadClass(ClassLoader.java:521) ~[na:na]
	at java.base/java.lang.Class.forName0(Native Method) ~[na:na]
	at java.base/java.lang.Class.forName(Class.java:398) ~[na:na]
	at java.base/sun.reflect.generics.factory.CoreReflectionFactory.makeNamedType(CoreReflectionFactory.java:114) ~[na:na]
	... 36 common frames omitted

2020-04-29 09:01:06.437 ERROR 21052 --- [ost-startStop-1] o.apache.catalina.core.StandardContext   : One or more Filters failed to start. Full details will be found in the appropriate container log file
2020-04-29 09:01:06.437 ERROR 21052 --- [ost-startStop-1] o.apache.catalina.core.StandardContext   : Context [] startup failed due to previous errors
2020-04-29 09:01:06.444  WARN 21052 --- [           main] ationConfigEmbeddedWebApplicationContext : Exception encountered during context initialization - cancelling refresh attempt: org.springframework.context.ApplicationContextException: Unable to start embedded container; nested exception is org.springframework.boot.context.embedded.EmbeddedServletContainerException: Unable to start embedded Tomcat
2020-04-29 09:01:06.452  INFO 21052 --- [           main] utoConfigurationReportLoggingInitializer : 

Error starting ApplicationContext. To display the auto-configuration report re-run your application with 'debug' enabled.
2020-04-29 09:01:06.458 ERROR 21052 --- [           main] o.s.boot.SpringApplication               : Application startup failed

org.springframework.context.ApplicationContextException: Unable to start embedded container; nested exception is org.springframework.boot.context.embedded.EmbeddedServletContainerException: Unable to start embedded Tomcat
	at org.springframework.boot.context.embedded.EmbeddedWebApplicationContext.onRefresh(EmbeddedWebApplicationContext.java:137) ~[spring-boot-1.5.9.RELEASE.jar:1.5.9.RELEASE]
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:537) ~[spring-context-4.3.13.RELEASE.jar:4.3.13.RELEASE]
	at org.springframework.boot.context.embedded.EmbeddedWebApplicationContext.refresh(EmbeddedWebApplicationContext.java:122) ~[spring-boot-1.5.9.RELEASE.jar:1.5.9.RELEASE]
	at org.springframework.boot.SpringApplication.refresh(SpringApplication.java:693) ~[spring-boot-1.5.9.RELEASE.jar:1.5.9.RELEASE]
	at org.springframework.boot.SpringApplication.refreshContext(SpringApplication.java:360) ~[spring-boot-1.5.9.RELEASE.jar:1.5.9.RELEASE]
	at org.springframework.boot.SpringApplication.run(SpringApplication.java:303) ~[spring-boot-1.5.9.RELEASE.jar:1.5.9.RELEASE]
	at org.springframework.boot.SpringApplication.run(SpringApplication.java:1118) ~[spring-boot-1.5.9.RELEASE.jar:1.5.9.RELEASE]
	at org.springframework.boot.SpringApplication.run(SpringApplication.java:1107) ~[spring-boot-1.5.9.RELEASE.jar:1.5.9.RELEASE]
	at com.itmuch.cloud.study.EurekaApplication.main(EurekaApplication.java:15) ~[classes/:na]
Caused by: org.springframework.boot.context.embedded.EmbeddedServletContainerException: Unable to start embedded Tomcat
	at org.springframework.boot.context.embedded.tomcat.TomcatEmbeddedServletContainer.initialize(TomcatEmbeddedServletContainer.java:123) ~[spring-boot-1.5.9.RELEASE.jar:1.5.9.RELEASE]
	at org.springframework.boot.context.embedded.tomcat.TomcatEmbeddedServletContainer.<init>(TomcatEmbeddedServletContainer.java:84) ~[spring-boot-1.5.9.RELEASE.jar:1.5.9.RELEASE]
	at org.springframework.boot.context.embedded.tomcat.TomcatEmbeddedServletContainerFactory.getTomcatEmbeddedServletContainer(TomcatEmbeddedServletContainerFactory.java:554) ~[spring-boot-1.5.9.RELEASE.jar:1.5.9.RELEASE]
	at org.springframework.boot.context.embedded.tomcat.TomcatEmbeddedServletContainerFactory.getEmbeddedServletContainer(TomcatEmbeddedServletContainerFactory.java:179) ~[spring-boot-1.5.9.RELEASE.jar:1.5.9.RELEASE]
	at org.springframework.boot.context.embedded.EmbeddedWebApplicationContext.createEmbeddedServletContainer(EmbeddedWebApplicationContext.java:164) ~[spring-boot-1.5.9.RELEASE.jar:1.5.9.RELEASE]
	at org.springframework.boot.context.embedded.EmbeddedWebApplicationContext.onRefresh(EmbeddedWebApplicationContext.java:134) ~[spring-boot-1.5.9.RELEASE.jar:1.5.9.RELEASE]
	... 8 common frames omitted
Caused by: java.lang.IllegalStateException: StandardEngine[Tomcat].StandardHost[localhost].TomcatEmbeddedContext[] failed to start
	at org.springframework.boot.context.embedded.tomcat.TomcatEmbeddedServletContainer.rethrowDeferredStartupExceptions(TomcatEmbeddedServletContainer.java:167) ~[spring-boot-1.5.9.RELEASE.jar:1.5.9.RELEASE]
	at org.springframework.boot.context.embedded.tomcat.TomcatEmbeddedServletContainer.initialize(TomcatEmbeddedServletContainer.java:102) ~[spring-boot-1.5.9.RELEASE.jar:1.5.9.RELEASE]
	... 13 common frames omitted


Process finished with exit code 1

```







```
解决报错java.lang.TypeNotPresentException: Type javax.xml.bind.JAXBContext not present

白礼军 2019-09-04 22:02:27  2206  收藏 1
展开
今天在运行程序的时候，一直报“java.lang.TypeNotPresentException: Type javax.xml.bind.JAXBContext not present”的错误， 代码之前一直没有动过，唯一的改变的就是之前用的是jdk8，昨天卸载了jdk8，重装了jdk12。

百度原因，发现是因为用了jdk12的缘故。因为JAXB-API是java ee的一部分，在jdk12中没有在默认的类路径中。从jdk9开始java引入了模块的概念， 可以使用模块命令–add-modles java.xml.bind引入jaxb-api。也可以选择另一种解决方法，在maven里面加入下面依赖，可以解决这个问题：

 <dependency>
        <groupId>javax.xml.bind</groupId>
        <artifactId>jaxb-api</artifactId>
        <version>2.3.0</version>
    </dependency>
    <dependency>
        <groupId>com.sun.xml.bind</groupId>
        <artifactId>jaxb-impl</artifactId>
        <version>2.3.0</version>
    </dependency>
    <dependency>
        <groupId>org.glassfish.jaxb</groupId>
        <artifactId>jaxb-runtime</artifactId>
        <version>2.3.0</version>
    </dependency>
    <dependency>
        <groupId>javax.activation</groupId>
        <artifactId>activation</artifactId>
        <version>1.1.1</version>
    </dependency>

```

