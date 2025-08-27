spring.application.name=codenova
#ë¨ìê° ì´, íì¬ì¤ì ì ê¸°ë³¸ê°
server.servlet.session.timeout=1800
#live reload
spring.devtools.livereload.enabled=true
# MySQLDB ì¤ì 
spring.datasource.url=jdbc:mysql://localhost:3306/codenova?useSSL=false&useUnicode=true&serverTimezone=Asia/Seoul&allowPublicKeyRetrieval=true
#spring.datasource.url=jdbc:mysql://192.168.0.31:3306/codenova?useSSL=false&useUnicode=true&serverTimezone=Asia/Seoul
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
# ë°ì´í°ë² ì´ì¤ ì¤ì 
#spring.datasource.username=codenova
#spring.datasource.password=codenova123
spring.datasource.username=root
spring.datasource.password=1234

#spring.security.user.name=admin
#spring.security.user.password=1234
# JPA
# 'update' --> ê°ë°ì ì¼ë°ì ì¼ë¡ ì¬ì©, íë¡ì í¸ ìë£ í ë³ê²½ --> vaildate ë³ê²½ ê°ë
spring.jpa.hibernate.ddl-auto=update
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQLDialect
# Thymeleaf ííë¦¿ ê²½ë¡ ë° íì¥ì ì¤ì 
spring.thymeleaf.cache=false
spring.thymeleaf.prefix=classpath:/templates/
spring.thymeleaf.suffix=.html

spring.jpa.properties.hibernate.SQL=debug

spring.jpa.properties.hibernate.show_sql=true
spring.jpa.properties.hibernate.format_sql=true
spring.jpa.properties.hibernate.highlight_sql=true

upload.path=src/main/uploads/
