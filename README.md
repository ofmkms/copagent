# copagent ![release](https://img.shields.io/badge/version-1.3-orange.svg)

**A java memory web shell extracting tool**



- Download:

  https://github.com/LandGrey/copagent/raw/release/cop.jar

- Build
  ```
  mvn compile package site
  ```

- Usage:

  ```
  zhangsy@zsy ~/Workspaces/copagent/cop/target (master*) $ java -jar cop.jar
  [INFO] Version    : 1.3
  [INFO] Build Time : 2020-12-06 08:53:43
  [INFO] Found existing java process, please choose one and hit RETURN.
  * [1]: 28449
    [2]: 23032 org.apache.catalina.startup.Bootstrap
    [3]: 25055 org.jetbrains.jps.cmdline.Launcher
    [4]: 21999 org.jetbrains.idea.maven.server.RemoteMavenServer
  2
  [INFO] Try to attach process 23032, please wait a moment ...
  [WARN] Current VM java version: 1.8 do not match target VM java version: 1.7, attach may fail.
  [WARN] Target VM JAVA_HOME is /Library/Java/JavaVirtualMachines/jdk1.7.0_80.jdk/Contents/Home/jre, copagent JAVA_HOME is /Library/Java/JavaVirtualMachines/jdk1.8.0_181.jdk/Contents/Home/jre, try to set the same JAVA_HOME.
  [INFO] Attach process 23032 finished .
  [INFO] Result store in : /Users/zhangsy/Workspaces/copagent/cop/target/.copagent/result.txt
  ```
  ```
  
  All Suspicious Class    : 27
  
  ============================================================
  high risk level Class   : 
  ============================================================
  normal risk level Class : 
  order       : 1
  name        : org.apache.struts.action.ActionServlet
  risk level  : normal
  location    : /Users/zhangsy/Workspaces/copagent/cop/target/.copagent/java/org.apache.catalina.loader.WebappClassLoader-44b1d2a0/org/apache/struts/action/ActionServlet.java
  hashcode    : 3ac9905e
  classloader : org.apache.catalina.loader.WebappClassLoader
  extends     : WebappClassLoader
    context: /struts2-showcase
    delegate: false
    repositories:
      /WEB-INF/classes/
  ----------> Parent Classloader:
  org.apache.catalina.loader.StandardClassLoader@163778cf
  
  
  order       : 2
  name        : org.apache.catalina.servlets.DefaultServlet
  risk level  : normal
  location    : /Users/zhangsy/Workspaces/copagent/cop/target/.copagent/java/org.apache.catalina.loader.StandardClassLoader-163778cf/org/apache/catalina/servlets/DefaultServlet.java
  hashcode    : 1bf5d5bc
  classloader : org.apache.catalina.loader.StandardClassLoader
  extends     : org.apache.catalina.loader.StandardClassLoader@163778cf
  
  order       : 3
  name        : org.apache.struts2.dispatcher.ng.filter.StrutsPrepareAndExecuteFilter
  risk level  : normal
  location    : /Users/zhangsy/Workspaces/copagent/cop/target/.copagent/java/org.apache.catalina.loader.WebappClassLoader-53028e9e/org/apache/struts2/dispatcher/ng/filter/StrutsPrepareAndExecuteFilter.java
  hashcode    : b96a575
  classloader : org.apache.catalina.loader.WebappClassLoader
  extends     : WebappClassLoader
    context: /struts2-blank
    delegate: false
    repositories:
      /WEB-INF/classes/
  ----------> Parent Classloader:
  org.apache.catalina.loader.StandardClassLoader@163778cf
  
  
  order       : 4
  name        : javax.faces.webapp.FacesServlet
  risk level  : normal
  location    : /Users/zhangsy/Workspaces/copagent/cop/target/.copagent/java/org.apache.catalina.loader.WebappClassLoader-44b1d2a0/javax/faces/webapp/FacesServlet.java
  hashcode    : 194206c9
  classloader : org.apache.catalina.loader.WebappClassLoader
  extends     : WebappClassLoader
    context: /struts2-showcase
    delegate: false
    repositories:
      /WEB-INF/classes/
  ----------> Parent Classloader:
  org.apache.catalina.loader.StandardClassLoader@163778cf
  
  
  order       : 5
  name        : org.apache.catalina.filters.CsrfPreventionFilter
  risk level  : normal
  location    : /Users/zhangsy/Workspaces/copagent/cop/target/.copagent/java/org.apache.catalina.loader.StandardClassLoader-163778cf/org/apache/catalina/filters/CsrfPreventionFilter.java
  hashcode    : 578e5065
  classloader : org.apache.catalina.loader.StandardClassLoader
  extends     : org.apache.catalina.loader.StandardClassLoader@163778cf
  
  order       : 6
  name        : org.apache.struts2.sitemesh.FreemarkerPageFilter
  risk level  : normal
  location    : /Users/zhangsy/Workspaces/copagent/cop/target/.copagent/java/org.apache.catalina.loader.WebappClassLoader-44b1d2a0/org/apache/struts2/sitemesh/FreemarkerPageFilter.java
  hashcode    : 60dac573
  classloader : org.apache.catalina.loader.WebappClassLoader
  extends     : WebappClassLoader
    context: /struts2-showcase
    delegate: false
    repositories:
      /WEB-INF/classes/
  ----------> Parent Classloader:
  org.apache.catalina.loader.StandardClassLoader@163778cf
  
  
  order       : 7
  name        : org.apache.velocity.tools.view.servlet.VelocityViewServlet
  risk level  : normal
  location    : /Users/zhangsy/Workspaces/copagent/cop/target/.copagent/java/org.apache.catalina.loader.WebappClassLoader-44b1d2a0/org/apache/velocity/tools/view/servlet/VelocityViewServlet.java
  hashcode    : 3e51ab7c
  classloader : org.apache.catalina.loader.WebappClassLoader
  extends     : WebappClassLoader
    context: /struts2-showcase
    delegate: false
    repositories:
      /WEB-INF/classes/
  ----------> Parent Classloader:
  org.apache.catalina.loader.StandardClassLoader@163778cf
  
  
  order       : 8
  name        : javax.servlet.http.HttpServlet
  risk level  : normal
  location    : /Users/zhangsy/Workspaces/copagent/cop/target/.copagent/java/org.apache.catalina.loader.StandardClassLoader-163778cf/javax/servlet/http/HttpServlet.java
  hashcode    : 3d80fbe2
  classloader : org.apache.catalina.loader.StandardClassLoader
  extends     : org.apache.catalina.loader.StandardClassLoader@163778cf
  
  order       : 9
  name        : org.apache.struts2.sitemesh.VelocityPageFilter
  risk level  : normal
  location    : /Users/zhangsy/Workspaces/copagent/cop/target/.copagent/java/org.apache.catalina.loader.WebappClassLoader-44b1d2a0/org/apache/struts2/sitemesh/VelocityPageFilter.java
  hashcode    : 40f53ad6
  classloader : org.apache.catalina.loader.WebappClassLoader
  extends     : WebappClassLoader
    context: /struts2-showcase
    delegate: false
    repositories:
      /WEB-INF/classes/
  ----------> Parent Classloader:
  org.apache.catalina.loader.StandardClassLoader@163778cf
  
  
  order       : 10
  name        : org.apache.struts2.views.JspSupportServlet
  risk level  : normal
  location    : /Users/zhangsy/Workspaces/copagent/cop/target/.copagent/java/org.apache.catalina.loader.WebappClassLoader-44b1d2a0/org/apache/struts2/views/JspSupportServlet.java
  hashcode    : 40f1e1bc
  classloader : org.apache.catalina.loader.WebappClassLoader
  extends     : WebappClassLoader
    context: /struts2-showcase
    delegate: false
    repositories:
      /WEB-INF/classes/
  ----------> Parent Classloader:
  org.apache.catalina.loader.StandardClassLoader@163778cf
  
  
  order       : 11
  name        : uk.ltd.getahead.dwr.DWRServlet
  risk level  : normal
  location    : /Users/zhangsy/Workspaces/copagent/cop/target/.copagent/java/org.apache.catalina.loader.WebappClassLoader-44b1d2a0/uk/ltd/getahead/dwr/DWRServlet.java
  hashcode    : 6925e60f
  classloader : org.apache.catalina.loader.WebappClassLoader
  extends     : WebappClassLoader
    context: /struts2-showcase
    delegate: false
    repositories:
      /WEB-INF/classes/
  ----------> Parent Classloader:
  org.apache.catalina.loader.StandardClassLoader@163778cf
  
  
  order       : 12
  name        : org.apache.struts2.s1.ActionFormValidationInterceptor$1
  risk level  : normal
  location    : /Users/zhangsy/Workspaces/copagent/cop/target/.copagent/java/org.apache.catalina.loader.WebappClassLoader-44b1d2a0/org/apache/struts2/s1/ActionFormValidationInterceptor$1.java
  hashcode    : 560027a4
  classloader : org.apache.catalina.loader.WebappClassLoader
  extends     : WebappClassLoader
    context: /struts2-showcase
    delegate: false
    repositories:
      /WEB-INF/classes/
  ----------> Parent Classloader:
  org.apache.catalina.loader.StandardClassLoader@163778cf
  
  
  order       : 13
  name        : org.apache.struts2.sitemesh.FreemarkerDecoratorServlet
  risk level  : normal
  location    : /Users/zhangsy/Workspaces/copagent/cop/target/.copagent/java/org.apache.catalina.loader.WebappClassLoader-44b1d2a0/org/apache/struts2/sitemesh/FreemarkerDecoratorServlet.java
  hashcode    : 3dcb8313
  classloader : org.apache.catalina.loader.WebappClassLoader
  extends     : WebappClassLoader
    context: /struts2-showcase
    delegate: false
    repositories:
      /WEB-INF/classes/
  ----------> Parent Classloader:
  org.apache.catalina.loader.StandardClassLoader@163778cf
  
  
  order       : 14
  name        : org.apache.struts2.dispatcher.ng.filter.StrutsPrepareFilter
  risk level  : normal
  location    : /Users/zhangsy/Workspaces/copagent/cop/target/.copagent/java/org.apache.catalina.loader.WebappClassLoader-44b1d2a0/org/apache/struts2/dispatcher/ng/filter/StrutsPrepareFilter.java
  hashcode    : 64bec5f3
  classloader : org.apache.catalina.loader.WebappClassLoader
  extends     : WebappClassLoader
    context: /struts2-showcase
    delegate: false
    repositories:
      /WEB-INF/classes/
  ----------> Parent Classloader:
  org.apache.catalina.loader.StandardClassLoader@163778cf
  
  
  order       : 15
  name        : uk.ltd.getahead.dwr.AbstractDWRServlet
  risk level  : normal
  location    : /Users/zhangsy/Workspaces/copagent/cop/target/.copagent/java/org.apache.catalina.loader.WebappClassLoader-44b1d2a0/uk/ltd/getahead/dwr/AbstractDWRServlet.java
  hashcode    : 6972062c
  classloader : org.apache.catalina.loader.WebappClassLoader
  extends     : WebappClassLoader
    context: /struts2-showcase
    delegate: false
    repositories:
      /WEB-INF/classes/
  ----------> Parent Classloader:
  org.apache.catalina.loader.StandardClassLoader@163778cf
  
  
  order       : 16
  name        : org.apache.struts2.dispatcher.ng.filter.StrutsExecuteFilter
  risk level  : normal
  location    : /Users/zhangsy/Workspaces/copagent/cop/target/.copagent/java/org.apache.catalina.loader.WebappClassLoader-44b1d2a0/org/apache/struts2/dispatcher/ng/filter/StrutsExecuteFilter.java
  hashcode    : 4de2dfad
  classloader : org.apache.catalina.loader.WebappClassLoader
  extends     : WebappClassLoader
    context: /struts2-showcase
    delegate: false
    repositories:
      /WEB-INF/classes/
  ----------> Parent Classloader:
  org.apache.catalina.loader.StandardClassLoader@163778cf
  
  
  order       : 17
  name        : javax.servlet.GenericServlet
  risk level  : normal
  location    : /Users/zhangsy/Workspaces/copagent/cop/target/.copagent/java/org.apache.catalina.loader.StandardClassLoader-163778cf/javax/servlet/GenericServlet.java
  hashcode    : 5f18d1f9
  classloader : org.apache.catalina.loader.StandardClassLoader
  extends     : org.apache.catalina.loader.StandardClassLoader@163778cf
  
  order       : 18
  name        : com.opensymphony.sitemesh.webapp.SiteMeshFilter
  risk level  : normal
  location    : /Users/zhangsy/Workspaces/copagent/cop/target/.copagent/java/org.apache.catalina.loader.WebappClassLoader-44b1d2a0/com/opensymphony/sitemesh/webapp/SiteMeshFilter.java
  hashcode    : 4d3de8ab
  classloader : org.apache.catalina.loader.WebappClassLoader
  extends     : WebappClassLoader
    context: /struts2-showcase
    delegate: false
    repositories:
      /WEB-INF/classes/
  ----------> Parent Classloader:
  org.apache.catalina.loader.StandardClassLoader@163778cf
  
  
  order       : 19
  name        : org.apache.jasper.servlet.JspServlet
  risk level  : normal
  location    : /Users/zhangsy/Workspaces/copagent/cop/target/.copagent/java/org.apache.catalina.loader.StandardClassLoader-163778cf/org/apache/jasper/servlet/JspServlet.java
  hashcode    : 2d33ee43
  classloader : org.apache.catalina.loader.StandardClassLoader
  extends     : org.apache.catalina.loader.StandardClassLoader@163778cf
  
  order       : 20
  name        : freemarker.ext.servlet.FreemarkerServlet
  risk level  : normal
  location    : /Users/zhangsy/Workspaces/copagent/cop/target/.copagent/java/org.apache.catalina.loader.WebappClassLoader-44b1d2a0/freemarker/ext/servlet/FreemarkerServlet.java
  hashcode    : 7c0a7416
  classloader : org.apache.catalina.loader.WebappClassLoader
  extends     : WebappClassLoader
    context: /struts2-showcase
    delegate: false
    repositories:
      /WEB-INF/classes/
  ----------> Parent Classloader:
  org.apache.catalina.loader.StandardClassLoader@163778cf
  
  
  order       : 21
  name        : org.apache.catalina.filters.RequestDumperFilter
  risk level  : normal
  location    : /Users/zhangsy/Workspaces/copagent/cop/target/.copagent/java/org.apache.catalina.loader.StandardClassLoader-163778cf/org/apache/catalina/filters/RequestDumperFilter.java
  hashcode    : 676ffc31
  classloader : org.apache.catalina.loader.StandardClassLoader
  extends     : org.apache.catalina.loader.StandardClassLoader@163778cf
  
  order       : 22
  name        : org.apache.catalina.filters.SetCharacterEncodingFilter
  risk level  : normal
  location    : /Users/zhangsy/Workspaces/copagent/cop/target/.copagent/java/org.apache.catalina.loader.StandardClassLoader-163778cf/org/apache/catalina/filters/SetCharacterEncodingFilter.java
  hashcode    : 157eba20
  classloader : org.apache.catalina.loader.StandardClassLoader
  extends     : org.apache.catalina.loader.StandardClassLoader@163778cf
  
  order       : 23
  name        : org.apache.struts2.sitemesh.VelocityDecoratorServlet
  risk level  : normal
  location    : /Users/zhangsy/Workspaces/copagent/cop/target/.copagent/java/org.apache.catalina.loader.WebappClassLoader-44b1d2a0/org/apache/struts2/sitemesh/VelocityDecoratorServlet.java
  hashcode    : 47bedb42
  classloader : org.apache.catalina.loader.WebappClassLoader
  extends     : WebappClassLoader
    context: /struts2-showcase
    delegate: false
    repositories:
      /WEB-INF/classes/
  ----------> Parent Classloader:
  org.apache.catalina.loader.StandardClassLoader@163778cf
  
  
  order       : 24
  name        : compressionFilters.CompressionFilter
  risk level  : normal
  location    : /Users/zhangsy/Workspaces/copagent/cop/target/.copagent/java/org.apache.catalina.loader.WebappClassLoader-2cfb1075/compressionFilters/CompressionFilter.java
  hashcode    : 742f2a56
  classloader : org.apache.catalina.loader.WebappClassLoader
  extends     : WebappClassLoader
    context: /examples
    delegate: false
    repositories:
      /WEB-INF/classes/
  ----------> Parent Classloader:
  org.apache.catalina.loader.StandardClassLoader@163778cf
  
  
  order       : 25
  name        : filters.ExampleFilter
  risk level  : normal
  location    : /Users/zhangsy/Workspaces/copagent/cop/target/.copagent/java/org.apache.catalina.loader.WebappClassLoader-2cfb1075/filters/ExampleFilter.java
  hashcode    : 1b16b24f
  classloader : org.apache.catalina.loader.WebappClassLoader
  extends     : WebappClassLoader
    context: /examples
    delegate: false
    repositories:
      /WEB-INF/classes/
  ----------> Parent Classloader:
  org.apache.catalina.loader.StandardClassLoader@163778cf
  
  
  order       : 26
  name        : org.apache.struts2.views.JspSupportServlet
  risk level  : normal
  location    : /Users/zhangsy/Workspaces/copagent/cop/target/.copagent/java/org.apache.catalina.loader.WebappClassLoader-53028e9e/org/apache/struts2/views/JspSupportServlet.java
  hashcode    : 6f146e6d
  classloader : org.apache.catalina.loader.WebappClassLoader
  extends     : WebappClassLoader
    context: /struts2-blank
    delegate: false
    repositories:
      /WEB-INF/classes/
  ----------> Parent Classloader:
  org.apache.catalina.loader.StandardClassLoader@163778cf
  
  
  order       : 27
  name        : org.apache.catalina.filters.FilterBase
  risk level  : normal
  location    : /Users/zhangsy/Workspaces/copagent/cop/target/.copagent/java/org.apache.catalina.loader.StandardClassLoader-163778cf/org/apache/catalina/filters/FilterBase.java
  hashcode    : 404043cb
  classloader : org.apache.catalina.loader.StandardClassLoader
  extends     : org.apache.catalina.loader.StandardClassLoader@163778cf
  
 
```
  

- Reference:

  [arthas](https://github.com/alibaba/arthas)

