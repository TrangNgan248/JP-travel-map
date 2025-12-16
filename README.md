# JP-travel-map
## 🚀 Run project with Docker
- Install docker
- Clone dự án về máy:
```bash
git clone xxx
cd travel-map
```
Build Docker images:
```bash
cd travel-map
docker compose build
docker compose up -d
```
Start contrainer:
```bash
docker compose up -d
```

Database Migration (Prisma):
- Make sure the `db` container is running, then execute:
```bash
docker compose exec web sh
npx prisma migrate dev --name init
```

