FROM isuper/java-oracle


COPY target /usr/src/myapp
WORKDIR /usr/src/myapp

EXPOSE 8080

CMD ["java", "-server", "-cp", "classes:dependency/*", "com.kumuluz.ee.EeApplication"]