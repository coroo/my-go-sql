#My Go SQL

Go x DB simple project

## Docker build
```
docker build . -t my-go-sql
```

## Docker images
Check the build result, you should have my-go-sql in the list
```
docker images 
```

#Test run
```
docker run -it -e dbuser=root -e dbpassword=P@ssw0rd -e dbhost=host.docker.internal -e dbport=3306 -e dbschema=enigma -e dbengine=mysql --name mygosql --rm my-go-sql
```
You should get the result on console