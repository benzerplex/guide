# Upgrade angular-cli:
```
sudo chown -R $(whoami) /usr/local/bin/npm
sudo chown -R $(whoami) /usr/local/lib/node_modules/
sudo chown -R $(whoami) /usr/local/lib/node_modules/npm/
npm cache clean
npm uninstall -g angular-cli
```
