# Testes com kind

Site oficial: **https://kind.sigs.k8s.io/**

Para criar um cluster:

```bash
kind create cluster --name kind-01 --config=kind-cluster-config.yaml
```

Imagem para testes: **renatogroffe/workertests-dotnet8:2**

Para remover um cluster:

```bash
kind delete cluster --name kind-01
```