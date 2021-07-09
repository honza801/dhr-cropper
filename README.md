# dhr-cropper

inspiration from

```
wget https://raw.githubusercontent.com/CESNET/DHuSTools/master/gist/download-and-crop.sh
```

# github repo auth

goto https://github.com/settings/tokens, create token with `read:packages` scope.

create docker login w/ github username, password is token

```
docker login docker.pkg.github.com
```

```
kubectl create secret docker-registry docker-pkg-github-com-login --docker-server=docker.pkg.github.com --docker-username=github-username --docker-password=token
```

