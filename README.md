# K8s-basic-monolic
## Docker commands 

```docker built -t news . ```

``` docker run news ```

## K8s commands 

``` kind create cluster --name news-k8s```

 ``` docker build -t news . ```

 ``` kind load docker-image news --name news-k8s ```

 ``` kubectl apply -f k8s  ```

 ``` kubectl port-forward svc/news-ap 9090:80 ```



## changes in the code 
``` docker built -t news . ```

 ``` kind load docker-image news --name news  ```

 ``` kubectl rollout restart news  ```

 ``` kubectl port-forward svc/news-ap 9090:80```
