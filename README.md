# CrowdSourcing-vue-docker
Deployment project for the frontend of CrowdSourcing platform

# Usage
cd mart-vue

npm install

npm run build

cd ..

mv mart-vue/dist/ dist/

docker build -t txhsl/crowdsourcing-vue-docker . 

docker run -d -p 80:80 txhsl/crowdsourcing-vue-docker