# Create a pod with tolerations
```shell
kubectl run bee --image=nginx --overrides='{"spec":{"tolerations":[{"effect":"NoSchedule", "key":"spray", "operator":"Equal", "value":"mortein"}]}}'
```
