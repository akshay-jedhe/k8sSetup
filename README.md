Using ConfigMap As type of Volume:
1.The configMap resource provides a way to inject configuration data into Pods. The data stored in a ConfigMap object can be referenced in a volume of type configMap and then consumed by containerized applications running in a Pod.
2.You must create a ConfigMap before you can use it.
3.A Container using a ConfigMap as a subPath volume mount will not receive ConfigMap updates.
4.for more please ref Docs.
