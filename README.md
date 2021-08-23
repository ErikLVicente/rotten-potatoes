# Rotten Potatoes - (Isolating Pods with Namespaces on Kubernetes)

1- To do git clone this repository
    $ git clone https://github.com/ErikLVicente/rotten-potatoes.git

2- Create 2 namespaces your environment - "web" and "db"
    $ kubectl create namespace web
    $ kubectl create namespace db

3- Apply demo app deployment  
    $ kubectl create -f ./k8s/mongodb -f ./k8s/web

4- Test App in your browse
    localhost:8080



