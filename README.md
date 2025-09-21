# Falcord Desktop App

Falcord is a custom server for Discord back in 2015-2018, and this is the desktop app for it! (maybe, idk)
<!-- hide for now as we do not have any previews
![](preview/preview1.png)
![](preview/preview2.png)
-->

## Downloads

Get the latest prebuilt binaries here: https://falcord.ixchats.com/download

## Building from Source

You need to have the following dependencies installed:
- [Git](https://git-scm.com/downloads)
- [Node.js](https://nodejs.org/en/download)
- pnpm: `npm install --global pnpm`

Packaging will create builds in the dist/ folder

```sh
git clone https://github.com/falcordapp/desktop-app
cd desktop-app

# Install dependencies
pnpm i

# Run the app without packaging
pnpm start

# Package the app for your OS
pnpm package

# Build only the Linux Pacman package
pnpm package --linux pacman

# Package to a specific directory
pnpm package:dir
```
