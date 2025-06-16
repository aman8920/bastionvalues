# bastionvalues




# service-account.yaml
apiVersion: v1
kind: ServiceAccount
metadata:
  name: my-app-sa
  annotations:
    azure.workload.identity/client-id: 6baabffd-464f-41cf-a940-c11eca500b3b


