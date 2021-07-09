# dhr-cropper

inspiration from

```
wget https://raw.githubusercontent.com/CESNET/DHuSTools/master/gist/download-and-crop.sh
```

# docker env variables

Mandatory COORDS fe. 49.72,13.45
Optional SCRATCH defaults /usr/share/nginx/html

# github repo auth

goto https://github.com/settings/tokens, create token with `read:packages` scope.

create docker login w/ github username, password is token

```
docker login docker.pkg.github.com
```

```
kubectl create secret docker-registry docker-pkg-github-com-login --docker-server=docker.pkg.github.com --docker-username=github-username --docker-password=token
```

