Gebruik:

In development mode met hot reloading:

`docker run -it --rm -p 8080:8080 -v $PWD/src:/src -w /src node:8 bash -c "npm install gulp-cli -g && npm install --no-bin-links && npm install nodemon -g && npm run dev"`



Standaard poort 8080

localhost:8080/login.html