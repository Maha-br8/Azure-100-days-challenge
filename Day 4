# Day 08 - Nginx Reverse Proxy on Azure VMs

## 📌 Task

Set up a reverse proxy using Nginx on WebServerVM to forward requests to a Node.js app running on AppServerVM.

## ⚙️ Tools Used

- Azure CLI
- Ubuntu
- Node.js + Express
- Nginx
- SSH

## 🚀 Steps Performed

1. Created two VMs (AppServerVM & WebServerVM) using Azure CLI.
2. Installed Node.js and ran a simple app on AppServerVM.
3. Installed Nginx on WebServerVM and configured it as a reverse proxy.
4. Verified reverse proxy by accessing the WebServerVM IP via browser or `curl`.

## 💻 Node.js App Code

```js
const express = require('express');
const app = express();
app.get('/', (req, res) => res.send('Hello World from Node.js!'));
app.listen(3000, () => console.log('App running on port 3000'));
