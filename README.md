First-Time Setup:
run this command once to initialize the database:
docker-compose exec fastapi alembic upgrade head


if you encounter a 500 error after build, ensure a fresh start using:
docker-compose down -v && docker-compose up --build
