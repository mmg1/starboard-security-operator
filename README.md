# starboard-security-operator

![build](https://github.com/aquasecurity/starboard-security-operator/workflows/build/badge.svg)

## Getting Started

```
$ kubectl create secret generic starboard-security-operator \
  --namespace starboard \
  --from-literal OPERATOR_SCANNER_AQUA_CSP_USER=$AQUA_CONSOLE_USERNAME \
  --from-literal OPERATOR_SCANNER_AQUA_CSP_PASSWORD=$AQUA_CONSOLE_PASSWORD
```

```
$ kubectl apply -f kube/starboard-security-operator.yaml
```
