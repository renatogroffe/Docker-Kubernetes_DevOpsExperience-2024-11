Exibir clusters disponíveis com **kubectl**:

```bash
kubectl config get-contexts
```

Equivalente com **kubectx**:

```bash
kubectx
```

---

Selecionando um cluster com **kubectl**:

```bash
kubectl config use-context AKSCluster
```

Equivalente com **kubectx**:

```bash
kubectx AKSCluster
```

---

Exibir namespace existentes com **kubectl**:

```bash
kubectl get namespaces
```

Equivalente com **kubens**:

```bash
kubens
```

---

Selecionando um cluster com **kubectl**:

```bash
kubectl config set-context --current --namespace=keda
```

Equivalente com **kubens**:

```bash
kubens keda
```