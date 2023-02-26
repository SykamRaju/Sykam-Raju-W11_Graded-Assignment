# Sykam-Raju-W11_Graded-Assignment
Graded Assignment on Implementing Micro Services

To run the micro service on Ubuntu:

Step 1:

Install  Docker using the following command

```bash
sudo apt-get install docker.io
```

Step 2:

Run the container


```bash
sudo docker run -p 5000:5000 microservice-breast-cancer-prediction
```

To Create a Docker image container containing everything needed to run the application 

```bash
sudo docker build -t microservice-breast-cancer-prediction .
```

