# node-js-install-ubuntu-server

## installs fnm (Fast Node Manager)
```bash
curl -fsSL https://fnm.vercel.app/install | bash
```

## activate fnm
```bash
source ~/.bashrc
```

## download and install Node.js
```bash
fnm use --install-if-missing 22
```

## verifies the right Node.js version is in the environment
```bash
node -v # should print `v22.5.1`
```

## verifies the right npm version is in the environment
```bash
npm -v # should print `10.8.2`
```
