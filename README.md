echo "# github-urmthj" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Direct-Dev-Ru/github-urmthj.git
git push -u origin main


…or push an existing repository from the command line
git remote add origin https://github.com/Direct-Dev-Ru/github-urmthj.git
git branch -M main
git push -u origin main


docker swarm init --advertise-addr 192.168.0.8
docker swarm join-token manager

docker stack deploy -c ./github-urmthj/stack.yml

docker node ls
docker stack ls
docker stack services ls
