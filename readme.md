# Krateo FinOps CrateDB Custom Resource

This is a [Helm Chart](https://helm.sh/docs/topics/charts/) that installs a custom resource for the [crate-operator](https://github.com/crate/crate-operator), which initializes a CrateDB instance.

## How to install

```sh
$ helm repo add krateo https://charts.krateo.io
$ helm repo update krateo
$ helm install finops-cratedb-custom-resource krateo/finops-cratedb-custom-resource
```
