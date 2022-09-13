# How to run

## Option 1: With precompiled Windows executable

Go to the [latest release](https://github.com/SoulKa/ph2-model-inspector-server/releases/latest) from the [server repository](https://github.com/SoulKa/ph2-model-inspector-server) and download `PH2.Model.Inspector.exe`. This executable is built with [nexe](https://github.com/nexe/nexe) and includes all dependencies.

## Option 2: Run optimized source code directly

1. Go to the [latest release](https://github.com/SoulKa/ph2-model-inspector-server/releases/latest) from the [server repository](https://github.com/SoulKa/ph2-model-inspector-server) and download `build.zip`.
2. Extract the ZIP to a desired location
3. Open a [Node.js](https://nodejs.org/) terminal in the extracted directory and run `node .`

## Option 3: Run server source directly with prebuilt webUI

1. Clone the [server repository](https://github.com/SoulKa/ph2-model-inspector-server). Open a [Node.js](https://nodejs.org/) terminal inside the server directory, then execute `npm i` and `npm run dev`. The server API can be reached under `http://localhost:8080/api`
2. Download the `build.zip` from the [latest release](https://github.com/SoulKa/ph2-model-inspector-client/releases/latest) of the webUI
3. Extract the ZIP and place it under `/public` in the server directory. The webUI is now available under [http://localhost:8080](http://localhost:8080)

## Option 4: Run server and React webUI manually

1. Clone the [server repository](https://github.com/SoulKa/ph2-model-inspector-server). Open a [Node.js](https://nodejs.org/) terminal inside the server directory, then execute `npm i` and `npm run dev`. The server API can be reached under `http://localhost:8080/api`
2. Clone the [webUI repository](https://github.com/SoulKa/ph2-model-inspector-client). Then run `npm i` and `npm start` in it

## Prerequisits

### Option 1: With precompiled Windows executable
**None**. The executable includes a Node.js binary, as well as the server code and the compiled webUI. It does not need any installation, just run it

### Option 2-4: Running manually
You need to install [Node.js](https://nodejs.org/) with npm.