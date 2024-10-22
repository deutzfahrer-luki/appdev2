# Appdev

## Developer Setup

### Eigener Laptop

1.  Download: https://nodejs.org/en/download/prebuilt-installer
1. `npm i -g @ionic/cli@latest`
1. `ionic start helloworld blank --type vue`
1. `cd helloworld`
1. `ionic serve`

### Schul-PC (nicht vorinstalliert, keine Berechtigungen)

1. Download: https://nodejs.org/en/download/prebuilt-binaries
1. `cd ~/Downloads`
1. `tar -xvf node...tar.gz`
1. `cd ~`
1. `mkdir appdev`
1. `cd appdev`
1. `PATH=$PATH:~/Downloads/node.../bin/`
1. `npm i @ionic/cli@latest`
1. `PATH=$PATH:~/appdev/node_modules/@ionic/cli/bin`
1. `cd ~`
1. `ionic start helloworld blank --type vue`
1. `cd helloworld`
1. `ionic serve`

### Schul-PC (vorinstalliert)

1. `ionic start helloworld blank --type vue`
1. `cd helloworld`
1. `ionic serve`

### In jedem Fall weiter mit ...

... https://ionicframework.com/docs/vue/quickstart#build-your-way-with-typescript-or-javascript