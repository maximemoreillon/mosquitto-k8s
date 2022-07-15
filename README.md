# Mosquitto in Kubernetes

## Password generation

```
mosquitto_passwd -c ./mosquitto_passwd_output your_user 
```

Then copy the content of mosquitto_passwd_output in the corresponding configmap section of the K8s manifest.