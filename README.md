# basic-dockerfile
1. Clone the repo to your machine
```
git clone https://github.com/cilginc/basic-dockerfile.git
cd basic-dockerfile
```
2. Build docker image and run
```
docker build -t hey-docker:1.0
docker run hey-docker:1.0
```
# If you want html version
1. Clone the repo to your machine
```
git clone https://github.com/cilginc/basic-dockerfile.git
cd basic-dockerfile
cd html-one
```
2. Build the docker image
   ```
   docker build -t nginx-docker:1.0
   ```
3. Run the docker image
   ```
   docker run -d -p 5000:80 nginx-docker:1.0
   ```
4. Open the localhost to see the output
   [localhost:5000](http://localhost:5000/)


This project is part of [roadmap.sh](https://roadmap.sh/projects/basic-dockerfile) DevOps projects.
