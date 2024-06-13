# k8s-configuration
To change password and user name: <br>
kubectl set env deployment/mongo-express ME_CONFIG_BASICAUTH_USERNAME=admin  <br>
kubectl set env deployment/mongo-express ME_CONFIG_BASICAUTH_PASSWORD=pass123 <br>
