# Mysql docker-compose
### Setup
```bash
docker-compose up -d
```
### Using mysql cli
```bash
docker exec -it mysql mysql -u root -p
```
### Export backup
```bash
docker exec -i mysql mysqldump -u root -p database > database.sql
```
### Import backup
```bash
docker exec -i mysql mysql -u root -p<password> database < database.sql
```
