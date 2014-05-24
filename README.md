# Yearofmoo AngularJS Seed Repo

A starter AngularJS repository for getting started with AngularJS. Includes helpful unit testing tools, Protractor integration and coverage testing.

## Installation

1. `sudo npm install -g grunt-cli`
2. `sudo npm install -g selenium`
3. `npm install`
4. `grunt install`

## Development

1. `grunt dev`
2. Go to: `http://localhost:8888`

## Testing

### Run all tests with
`grunt test` 

### Unit Testing

#### Single run tests
`grunt test:unit` 

#### Auto watching tests
`grunt autotest:unit`

### End to End Testing (Protractor)

#### Single run tests
`grunt test:e2e` 

#### Auto watching tests
`grunt autotest:e2e`

### Coverage Testing

`grunt coverage`

The browser will open to localhost:5555 you need to copy and paste the coverage report folder after it
e.g. http://localhost:5555/Chrome 35.0.1916 (Mac OS X 10.9.3)