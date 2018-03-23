SIKEN Bitcore Library
=======

A pure and powerful JavaScript SIKEN library.


## Get Started

```
npm install SIKEN-lib
```

```
bower install SIKEN-lib
```

## Security

We're using SIKEN-lib in production, but please use common sense when doing anything related to finances! We take no responsibility for your implementation decisions.



## Contributing

Please send pull requests for bug fixes, code optimization, and ideas for improvement. 

## Building the Browser Bundle

To build a SIKEN-lib full bundle for the browser:

```sh
gulp browser
```

This will generate files named `SIKEN-lib.js` and `SIKEN-lib.min.js`.

## Development & Tests

```sh
git clone https://github.com/SIKEN/SIKEN-lib
cd SIKEN-lib
npm install
```

Run all the tests:

```sh
gulp test
```

You can also run just the Node.js tests with `gulp test:node`, just the browser tests with `gulp test:browser`
or create a test coverage report (you can open `coverage/lcov-report/index.html` to visualize it) with `gulp coverage`.

## License

