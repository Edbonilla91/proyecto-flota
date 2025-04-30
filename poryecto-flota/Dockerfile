FROM tomcat:9.0-jdk17-temurin

# Elimina las aplicaciones de ejemplo predeterminadas de Tomcat
RUN rm -rf /usr/local/tomcat/webapps/*

# Copia el archivo WAR y lo renombra como ROOT.war para servirlo en la raíz
COPY app.war /usr/local/tomcat/webapps/ROOT.war

# Expone el puerto por defecto de Tomcat
EXPOSE 8080