first :-
docker run -d --name mongo -p 27017:27017 mongo:4.4


second :-
docker run -d --name app --link mongo:mongo -p 3000:3000 ankitrawat3987/node-mongo-db

expose the port :- for cluster ip 
sudo -E kubectl port-forward service/nginx-service -n nginx 81:80 --address=0.0.0.0


