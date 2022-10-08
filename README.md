# metatech-university-task

### Setup database

1. docker compose up
2. docker cp ./db course_db:/var/lib/postgresql
3. docker exec -it course_db sh
4. cd var/lib/postgresql/db
5. setup.sh