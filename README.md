# Kubernetes Demo

Configuring and maintaining Kubernetes in MINIKUBE. 

## Installation

Install Docker.\
Go to the docker setting and enable Kubernetes.\
Install Minikub



```bash
docker context use default
```
```bash
minikube start --driver docker
```
then run this command
```bash
minikube status
```
```bash
kubectl get node
```
```bash
kubectl service webapp-service
```

## Contributing

[Kubernetes Crash Course for Absolute Beginners](https://www.youtube.com/watch?v=s_o8dwzRlu4&ab_channel=TechWorldwithNana)  
Link for the complete video, please watch the video if you get into any problem. :)

Pull requests are welcome. For significant changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.
