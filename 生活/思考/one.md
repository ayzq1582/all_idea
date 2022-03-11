# 这肯定是最伟大的作品

----------

## 图片 ##
![](img/成功.jpg)

## 字体颜色
<font color="red" size="6px">
	asdqeasd
</font>

## 代码
```
@Configuration
public class CxfConfig {
    @Bean
    public ServletRegistrationBean disServlet() {
        ServletRegistrationBean servletRegistrationBean = new ServletRegistrationBean(new CXFServlet(), "/webService/*");
        return servletRegistrationBean;
    }
    @Bean(name = Bus.DEFAULT_BUS_ID)
    public SpringBus springBus() {
        return new SpringBus();
    }
    @Bean
    public Endpoint endpoint() {
        EndpointImpl endpoint = new EndpointImpl(springBus(), new TestServiceImp());
        endpoint.publish("/TestService");
        return endpoint;
    }
    @Bean
    public Endpoint endpoint2() {
        EndpointImpl endpoint = new EndpointImpl(springBus(), new CatServiceImp());
        endpoint.publish("/CatService");
        return endpoint;
    }

}
```