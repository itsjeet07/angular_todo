# Angular Todo app
_Simple todo application, that is easy to understand and extend_


## The application currently supports Angular 15.1.2 version

# Addtional specs

| Feature | Version |
| ------ | ------ |
| Typescript | [4.9.4](https://github.com/microsoft/TypeScript/releases/tag/v4.9.4) |
| Karma | [6.3.4](https://github.com/karma-runner/karma/releases/tag/v6.3.4) |
| Jasmin | [4.0.3](https://github.com/karma-runner/karma-jasmine/releases/tag/v4.0.1) |

> Note: project is configured to use [SASS](https://sass-lang.com/).
---

## Installation

Angular Todo requires [Node.js](https://nodejs.org/) latest to run )).

Install the dependencies and devDependencies and start the server.

```sh
npm i
```

## Development
### RUN
To run the application server:
```sh
npm run server
```
Then you can run the main application:
```sh
npm start
```
> Note: Application uses 4200 port as default. 
Want to change the port? 
Then go to `package.json` and change `ng serve --open` to `ng serve --port XXXX --open`

### BUILD
To build the application run:
```sh
ng build
```

### UNIT TESTS
To execute the unit tests run:
```sh
ng test
```

### END 2 END UNIT TESTS
To execute the end-to-end unit tests run:
```sh
ng e2e
```
---
