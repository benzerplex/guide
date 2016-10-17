# Upgrade angular-cli:
```
sudo chown -R $(whoami) /usr/local/bin/
sudo chown -R $(whoami) /usr/local/lib/node_modules/angular-cli/bin/
sudo chown -R $(whoami) /usr/local/bin/node
sudo chown -R $(whoami) /usr/local/bin/npm
sudo chown -R $(whoami) /usr/local/lib/node_modules/
sudo chown -R $(whoami) /usr/local/lib/node_modules/npm/
npm cache clean
npm uninstall -g angular-cli
npm install -g angular-cli
npm install -g -f angular-cli
npm install angular-cli
```
