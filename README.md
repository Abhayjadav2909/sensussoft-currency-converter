# sensussoft-currency-converter

## Description
This package provides a simple way to convert currencies. It supports conversion between various currencies such as INR, USD, CAD, etc. Users can easily integrate this package into their Node.js applications to handle currency conversion tasks.
exmaple : INR to USD , CAD to INR

# Installation
This is a Node.js module available through the npm registry.
Before installing, download and install Node.js. Node.js 0.10 or higher is required.
If this is a brand new project, make sure to create a package.json first with the npm init command.
Installation is done using the npm install command:
npm i sensussoft-currency-converter

## Usage

```javascript
import { convertCurrency } from "sensussoft-currency-converter";

// example 

convertCurrency("CAD","USD",1).then((data)=>{
    console.log(data);
})