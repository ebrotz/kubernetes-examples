# nginx-service-lb

In this example, nginx is deployed with a load balacer servce in front. When
this is applied to the cluster, http://localhost:80 should access the nginx
web server splash screen

## Deployment

    kubectl apply -f nginx.yml
