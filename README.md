first :-
docker run -d --name mongo -p 27017:27017 mongo:4.4


second :-
docker run -d --name app --link mongo:mongo -p 3000:3000 ankitrawat3987/node-mongo-db
