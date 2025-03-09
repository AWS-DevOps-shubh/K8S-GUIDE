## Kind Installation 

### On Linux 

```bash
[ $(uname -m) = x86_64 ] && curl -Lo ./kind https://kind.sigs.k8s.io/dl/v0.27.0/kind-linux-amd64
```

### Change Permission
```bash
chmod +x kind
```

### Move kind to root folder to run like command

```bash
mv kind /usr/local/bin/kind
```

## kubectl Installation
```bash
curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"
```


### Change Permission
```bash
chmod +x kubectl
```

### Move kind to root folder to run like command

```bash
mv kubectl /usr/local/bin/kubectl
```