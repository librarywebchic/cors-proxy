# CORS proxy via Node.js

A simple proxy server to add CORS to resources. Used by sample Angular Linked Data app

## Installation

### Step 1: Install from GitHub

In a Terminal Window

```bash
$ cd {YOUR-APACHE-DOCUMENT-ROOT}
$ git clone https://github.com/librarywebchic/cors-proxy.git
$ cd cors-proxy 
```

### Step 2: Install NPM
Go to http://nodejs.org/ download and install Node.js

### Step 3: Use NPM, Bower, and Grunt to install the dependencies


```bash
$ npm install

```

[NPM](https://www.npmjs.com/) is a dependency management library for Javascript. It is used to install the required libraries for testing and parsing RDF data. The server-side dependencies are configured in the file `package.json`.

### Step 4: Start the server

```bash
$ node index.js

```

## Usage

Proxy lives at [http://localhost:3000](http://localhost:3000)