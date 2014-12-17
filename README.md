docker-oracle-xe-11g
============================

Run with 22 1521 8080 ports opened:
```
docker run -d --restart=always -p 49160:22 -p 49161:1521 -p 49162:8080 prodasen/oracle:xe-11.2.0-1.0
```

Connect database with following setting:
```
hostname: localhost
port: 49161
sid: xe
username: system
password: oracle
```

Password for SYS
```
oracle
```

Login by SSH
```
ssh root@localhost -p 49160
password: prodasen
```
