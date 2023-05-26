![Moonojs logo](	https://www.moonojs.dev/assets/moonojs-brand.svg "Moonojs logo")

# MoonoJS CLI

![Moono CLI](https://img.shields.io/badge/%40moonojs%2Fcli-v1.1.1-%23573860.svg)
![Angular](https://img.shields.io/badge/Angular-Compatible-%23DD0031.svg)
[![Node.js Version](https://img.shields.io/badge/Node.js-%3E%3D%2018.10(suggest)-brightgreen.svg)](https://nodejs.org/)
[![License](https://img.shields.io/badge/License-NonCommercial-blue.svg)](https://choosealicense.com/licenses/non-commercial/)

MoonoJS/CLI is a command-line tool designed to accelerate development with Angular, Nest, and Ionic frameworks based on Node.js. It is the primary tool for working with the MoonoJS monorepo framework, which is specifically built to enhance scalability in this stack.

### Requirements

- Node.js >= 18.10

### Installation

To install MoonoJS/CLI globally, run the following command:

```bash
npm install -g @moonojs/cli
```

### Usage
Once installed, you can use MoonoJS/CLI by running the ```moono``` command in your terminal. For example:

```bash
moono generate provider UserSubscriptionProviderService ./src/app/providers
```

This will generate a provider named user--provider in 'src/app/providers/user-subscription'.

## About MoonoJS

Starting with version 2, which will be released at the end of August, Moono CLI will also allow you to create projects using the new MoonoJS monorepos framework. This framework has been developed to facilitate the scaling and management of projects in the mentioned stack.

### Features

- Create Angular providers quickly and efficiently, with an auto-generated CRUD.
- Easy setup and configuration for Angular, Nest, and Ionic projects.

### Release Roadmap

| Version   | Release Date     | Features                                                                  |
|:---------:|:---------------:|:------------------------------------------------------------------------:|
| 1.1.0     | End of May      | • HTTP Service generation<br>• Empty Models Generation                    |
| 1.2.0     | End of July     | • Multiple generation of Providers, Components, Services, and Modules for Angular       |
|           |                 | • Multiple generation of Resources and Modules Generation for Nest                    |
| 1.3.0     | End of August   | • Compose generation for monorepo with Docker                             |
|           |                 | • Support for multiple generation of Modules, Components, Providers, Services and Pages for Ionic |
| 2.0.0     | End of September | • Initial release of MoonoJS Core Framework                               |


<!--not-visible
### Principal Sponsors
|  |
|------|
| ![Logo](https://codefire.cl/assets/brand.svg) |
-->

### Stay in touch
For more information about MoonoJS, please visit the official website [Moonojs.com](https://moonojs.com).

<!--not-visible
Author - [@felipeinf](https://github.com/felipeinf)
-->

### License
MoonoJS CLI is licensed under the NonCommercial License. This license does not permit commercial use of the software.
