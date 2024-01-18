docker build -t myappexec .
docker run -d --name myapp5 -p 5432:5432 myappexec
docker exec -it myappexec psql -U localhost

SELECT nom FROM personnes WHERE age>30;