FROM openjdk:17-alpine
ENV APP_FILE admin-service-1.2.jar
ENV APP_HOME /usr/apps
WORKDIR $APP_HOME
COPY target/$APP_FILE $APP_HOME/
EXPOSE 9090
ENTRYPOINT ["java", "-jar", "$APP_FILE"]