# PostgreSQLfFrontend

<div id="built-with"></div>

### Built With

* [Angular](https://angular.io/) 13.0.1
* [Electron](https://www.electronjs.org/) 16.0.7


<div id="getting-started"></div>

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these steps.

<div id="prerequisites"></div>

### Prerequisites

npm is needed to install the dependecies.
* npm
  ```sh
  npm install npm@latest -g

  ```

<div id="installation"></div>

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/parrol/PostgreSQLf-frontend.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```

## Development server
<hr>

To open both web an local (platform specific executable) apps run:
   ```sh
   npm start
   ```
### Angular
To open web app run:
   ```sh
   npm run ng:serve
   ```
### Electron
To open local app run:
   ```sh
   npm run electron:serve
   ```

## Build
<hr>

### Angular
To build web app run:
   ```sh
   npm run build:prod
   ```
   or

   ```sh
   npm run build:dev
   ```
The build artifacts will be stored in the `dist/` directory.

### Electron
To build a local app executable run:
   ```sh
   npm run electron:build
   ```
The build artifacts and executables will be stored in the `release/` directory.


