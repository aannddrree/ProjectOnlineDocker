# Para execução destas aplicações utilizando Docker

* APP JAVA SPRINGBOOT:

Acessar o diretório "projTest" via terminar e executar:

```
docker build -t aplicacao_spring .
```

```
docker run --name java-container-test -d -p 8081:8080 aplicacao_spring 
```

* PAGINA HTML (SERVER NGINX):

```
docker build -t nginx .
```

```
docker run --name app-web -d -p 8080:80 nginx 
```

* APOS EXECUTAR:

```
docker image list
```

![image](https://github.com/aannddrree/ProjectOnlineDocker/assets/8753843/23ee726e-e975-455a-a6d3-04f35eedd3ca)

```
docker ps
```

![image](https://github.com/aannddrree/ProjectOnlineDocker/assets/8753843/d8f13b95-c961-41fc-a458-51325b9a94bd)


