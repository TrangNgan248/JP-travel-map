# JP-travel-map
Cách chạy dự án với Docker
cd travel-map
docker compose build
docker compose up -d

Cách migrate db:
Đảm bảo container db đang chạy
docker compose exec web sh
npx prisma migrate dev --name init

