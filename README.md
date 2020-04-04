# Classpip Service
[![Classpip Badge](https://img.shields.io/badge/classpip-dashboard-brightgreen.svg)](https://github.com/rocmeseguer/classpip-dashboard)
[![Classpip Badge](https://img.shields.io/badge/classpip-mobile-brightgreen.svg)](https://github.com/rocmeseguer/classpip-mobile)
[![Classpip Badge](https://img.shields.io/badge/classpip-services-brightgreen.svg)](https://github.com/rocmeseguer/classpip-services)
[![license](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/classpip/classpip/blob/master/LICENSE)

## NodeJS

Make sure you have NodeJS installed. Download the installer or use your favorite package manager. It's best to get the 10x version of node. This offers the best in stability and speed for building.

You may also need development tools to build native addons.

```
node -v
> v10.13.0
```

### To build native addons on Linux (Ubuntu)

```
sudo apt-get install gcc g++ make
```

### To build native addons on Windows

```
npm install -g windows-build-tools
```

## Global dependencies

You have to install LoopBack tooling for managing the model:

```
npm install -g strongloop@6.0.3
```

## Local dependencies

All the project dependencies are manage through [npmjs](https://www.npmjs.com/). This command will also download the typings configured in the **typings.json** file. To install this dependencies you should run:

```
npm install
```

## Running
Start the server `(node .)` and open `localhost:3000` in your browser to view the app.


## License

Classpip is released under the [Apache2 License](https://github.com/classpip/classpip-mobile/blob/master/LICENSE).
