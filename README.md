# Cyber Security
## Information

- Phuwadate Pingmuang (Phu)
- 6602041620131
- s6602041620131@email.kmutnb.ac.th


## Environment
```sh
cp env.simple .env
```

## Running a services
### Database
```sh
docker compose -f db.yaml up #monitoring
docker compose -f db.yaml up -d #background
```
### Admin
```sh
docker compose -f admin.yaml up #monitoring
docker compose -f admin.yaml up -d #background
```
### App
```sh
docker compose -f app.yaml up #monitoring
docker compose -f app.yaml up -d #background
```
