# Subversion_server_on_Docker
Subversionサーバを構築する。

## 起動

``` bash
docker-compose up -d
```

## リポジトリURL

[http://\$\{サーバIP\}:10080/svn_repo](http://${サーバIP}:10080/svn_repo)

## アカウント

- ID : username
- Pass : secret

## 参考

- [kuchida1981/subversion-httpd:Dockerhub](https://hub.docker.com/r/kuchida1981/subversion-httpd/)