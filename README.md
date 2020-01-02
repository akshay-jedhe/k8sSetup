Using Secret As type of Volume:
1.A secret volume is used to pass sensitive information, such as passwords, to Pods. You can store secrets in the Kubernetes API and mount them as files for use by Pods without coupling to Kubernetes directly. 
2.You must create a secret in the Kubernetes API before you can use it.
3.A Container using a Secret as a subPath volume mount will not receive Secret updates.
