# Change Repo of ubuntu server
use any CN instead of uae
```
sed -i 's/http:\/\/[a-z]*.archive.ubuntu.com/http:\/\/uae.archive.ubuntu.com/g' /etc/apt/sources.list
```

# Install Sanaie

```
bash <(curl -4 -Ls https://raw.githubusercontent.com/im-api/modified-scripts/main/install_sanaie.sh)
```
