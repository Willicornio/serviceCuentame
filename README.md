# Classpip Service

[![Classpip Badge](https://img.shields.io/badge/classpip-dashboard-brightgreen.svg)](https://github.com/rocmeseguer/classpip-dashboard)
[![Classpip Badge](https://img.shields.io/badge/classpip-mobile--profe-brightgreen)](https://github.com/rocmeseguer/classpip-mobile-profe)
[![Classpip Badge](https://img.shields.io/badge/classpip-mobile--student-brightgreen)](https://github.com/rocmeseguer/classpip-mobile-student)
[![Classpip Badge](https://img.shields.io/badge/classpip-services-brightgreen.svg)](https://github.com/rocmeseguer/classpip-services)
[![license](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/classpip/classpip/blob/master/LICENSE)

Classpip is a software architecture for teachers and students to perform school gamification activities inside the school environment through different platforms such as mobiles, tablets and computers.

The software architecture is composed by two mobile applications for performing “quick” class activities oriented to teachers and students. For “long” operations such as deep into reports and setup the platform there is an administration dashboard accessible from every computer. These three pieces share the information through a service-oriented architecture that exposes the main methods for data manipulation.

## Classpip-services
This repository contains the service-oriented application that exposes the main methods for data manipulation.

## Current models
Consult here the [current data models](https://github.com/rocmeseguer/classpip-services/blob/master/ModelosClasspip.pdf) for Classpip.

## Git and GitHub

You need to install Git and have an account in GitHub:
 
https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
 
https://github.com/
 
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
npm install -g windows-build-tools@5.1.0
```

## Global dependencies

You have to install LoopBack tooling for managing the model:

```
npm install -g strongloop@6.0.3
npm install -g loopback-cli@5.0.0
```

## Local dependencies

After cloning this repository you must install the local dependencies:

```
npm install
```

## Running
Start the server: 
```
npm run start
```
open `localhost:3000` in your browser to view the services.

## License

Classpip is released under the [Apache2 License](https://github.com/classpip/classpip-mobile/blob/master/LICENSE).
