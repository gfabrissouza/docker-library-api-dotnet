FROM mysql:8.3.0
EXPOSE 3308
COPY ./docker-library-api-dotnet/db/migrations/ /home/database/
COPY ./docker-library-api-dotnet/db/dataset/ /home/database/
COPY ./docker-library-api-dotnet/ci/init_database.sh /docker-entrypoint-initdb.d/init_database.sh