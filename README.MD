## SPRING流程

1.org.springframework.web.context.ContextLoaderListener
2.org.springframework.web.servlet.DispatcherServlet

---
### 容器初始化spring过程
1.tomcat->web.xml->ContextLoaderListener->contextInitialized()   
2.initWebApplicationContext()  
--- createWebApplicationContext()  
--- configureAndRefreshWebApplicationContext()->wac.refresh()->AbstractApplicationContext.refresh()  
--- servletContext.setAttribute()   

----