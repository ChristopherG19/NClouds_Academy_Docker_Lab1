# NClouds_Academy_Docker_Lab1

## Apps for this lab:
- [Go App](https://github.com/ybkuroki/go-webapp-sample)
- [Node App](https://github.com/plesk/node-express)

## Commands
After clone this repository use the following commands:
#### Go App
```
cd .\go-webapp-sample\

docker build -t my-go-app .

docker run -p 8080:8080 my-go-app
```

#### Node App
```
cd .\node-express\

docker build -t my-node-app .

docker run -p 3000:3000 my-node-app
```

## Preview
#### Go App
![image](https://github.com/ChristopherG19/NClouds_Academy_Docker_Lab1/assets/60325784/a0deb0d0-981f-4f17-b4d9-4a6ad23cb346)
![image](https://github.com/ChristopherG19/NClouds_Academy_Docker_Lab1/assets/60325784/e8ed4412-c8ab-4ee3-91ee-699720d498c5)
![image](https://github.com/ChristopherG19/NClouds_Academy_Docker_Lab1/assets/60325784/40b254b6-bfdd-49e0-8572-01bda246f459)
![image](https://github.com/ChristopherG19/NClouds_Academy_Docker_Lab1/assets/60325784/511b67df-ff22-4715-a2b3-7782268c794b)

#### Node App
![image](https://github.com/ChristopherG19/NClouds_Academy_Docker_Lab1/assets/60325784/92e92f36-a2c6-42fa-8d7c-4a0207813016)

### DockerHub
Also you can download and run the images with the following commands:
#### Go App
```
docker pull chrisg19/go-app
docker run -p 8080:8080 chrisg19/go-app  
```
#### Node App
```
docker pull chrisg19/node-app
docker run -p 3000:3000 my-node-app
```
And you gonna get the same result. Thank you, happy coding!
