# Deleting a POD

```
$ kubectl create ns chaosengineering
```

deploy some example app with labels ```app: webapp``` in the ```chaosengineering``` namespace.

# Chaos start
```
$ chaos --verbose run terminate-pod.yaml
```