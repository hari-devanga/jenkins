# jenkins
lts:- long term supprt

first we need to install docker

then start the docker

and enable docker (it will enable our docker whenever we are reeboting our system)

and then we need to pull jenkins image

docker run -p 8080:8080 -p 50000:50000 jenkins/jenkins:lts

now it will run in port 8080 in browser

you will get a adminstration passwrd you need to use it to further installation

then go and install plugins tht are required,create user admin and jenkins will be ready

next step is to attach agents to jenkins server - to do this manage jenkins or nodes create node configuration

and generate a script there and run it on agent to make connection to nodes

give name ,give label it is used to tag multiple agents in one group....for example projecta - u can add two agents in under this .

and go to created node click on that and copy command and run it on the build agents and add "&"in command because it will text u to next line without shut down connection
