# PH2 Model Inspector

The source code in this repository is a local NodeJS server instance to copy and inspect custom 3D objects for the Perfect Heist 2 level editor.

## How to run

### Option 1: With precompiled Windows executable
Go to the [latest release](https://github.com/SoulKa/ph2-model-inspector-server/releases/latest) from this repository and download `PH2.Model.Inspector.exe`. This executable is built with [nexe](https://github.com/nexe/nexe) and includes all dependencies.

### Option 2: Run server source directly with prebuilt webUI

1. Clone this repository. Open a terminal inside the root directory, then execute `npm i` and `npm start`. The server API can be reached under http://localhost:8080/api
2. Download the `build.zip` from the [latest release](https://github.com/SoulKa/ph2-model-inspector-client/releases/latest) of the webUI
3. Extract the ZIP and place it under `/public` in the server directory

### Option 3: Run server and React webUI manually

1. Clone this repository. Open a terminal inside the root directory, then execute `npm i` and `npm start`. The server API can be reached under http://localhost:8080/api
2. Clone the [webUI repository](https://github.com/SoulKa/ph2-model-inspector-client). Then run `npm i` and `npm start` in it

## Prerequisits