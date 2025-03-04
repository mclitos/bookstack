# bookstack
Bookstack - Gestión documental - Repositorio Guias

```
git clone https://github.com/mclitos/bookstack
```
```
cd bookstack
```
### Hay que generar una  APP_KEY= 
```
docker run -it --rm --entrypoint /bin/bash lscr.io/linuxserver/bookstack:latest appkey
```
copiar el resultado y editar el docker-compose.yaml en la opcion  **APP_KEY=**

```
docker compose up -d
```

Modifica si es necesario el docker-compose.yaml  **APP_URL=**  Ya Sea

**APP_URL=** http://localhost:8920  ó https://tudominio.com ó http://IP:8920

Ver en "localhost:8920" ó "IP:8920"

Usuario: admin@admin.com

Password: password
