# Nuxt 3 Minimal Starter

Look at the [Nuxt 3 documentation](https://nuxt.com/docs/getting-started/introduction) to learn more.

## Setup

Make sure to install the dependencies:

```bash
# npm
npm install

# pnpm
pnpm install

# yarn
yarn install
```

## Add Your Domain
add your local domain to /etc/hosts
or you can run this to auto add /etc/hosts **dont forget to change irsyaad.budi.dev in package.json**
```bash
yarn add:domain
```

Run this command only once

## Development Server
run docker-compose
```bash
yarn docker:ssl:up
```
make sure the **/certs** folder is created in **/config/https-local**

then open new terminal run your nuxt app with this command
```bash
yarn dev:ssl
```

so you can access your local domain with hot reload ✨
in my case is **https://irsyaad.budi.dev**

## IMPORTAN NOTES
Dont forget change all domain irsyaad.budi.dev with your own local domain