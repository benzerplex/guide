# WINDOWS OS

# MAC OS
## Upgrade angular-cli:

Sometime you might get annoying problems with updating angular-cli as following [updating-angular-cli] (https://github.com/angular/angular-cli/#updating-angular-cli)

To update `angular-cli` to new version:

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

To upgrade current local project to new version:

```

rm -rf node_modules dist tmp
npm install --save-dev angular-cli@latest
ng init

```
