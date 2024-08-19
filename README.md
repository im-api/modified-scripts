# Other Scripts
- [6to4 tunnel](https://github.com/im-api/6to4)

# Change Repo of ubuntu server
use any CN instead of uae
```
sed -i 's/http:\/\/[a-z]*.archive.ubuntu.com/http:\/\/uae.archive.ubuntu.com/g' /etc/apt/sources.list
```

# Install Sanaie

```
bash <(curl -4 -Ls https://raw.githubusercontent.com/im-api/modified-scripts/main/install_sanaie.sh)
```

# Install FranzKafka
```
bash <(curl -4 -Ls https://raw.githubusercontent.com/im-api/modified-scripts/main/install_franzkafka.sh)
```
