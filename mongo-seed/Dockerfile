FROM mongo:4.2.7

COPY init.json /init.json
CMD mongoimport --host mongodb_win --port 27017 --username=root --password=secret --authenticationDatabase=myProject --db myProject --collection=Users --drop --file=/init.json --jsonArray
