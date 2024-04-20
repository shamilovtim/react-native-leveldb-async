# @shamilovtim/react-native-leveldb-async

`abstract-level` adapter for `react-native-leveldb`

## Installation

```sh
npm install @shamilovtim/react-native-leveldb-async
```

### Setup polyfills

You will need to polyfill TextEncoder, TextDecoder and Buffer. Take a look at the sourcecode and documentation of [web5-react-native-polyfills](https://github.com/TBD54566975/web5-react-native-polyfills) for an example of how to set these up.

## Usage

## Issues

Passes nearly all tests of `abstract-level` except for "async-iterator-test.js".

This issue may be due to the metro bundler, see

- https://github.com/facebook/metro/commit/bf73ed3aa7fec15f1394fd492450163b62b6267a

To run tests, start up the testapp app and click "Start Test".

## Contributing

See the [contributing guide](CONTRIBUTING.md) to learn how to contribute to the repository and the development workflow.

## Thanks To

- [react-native-leveldb](https://github.com/greentriangle/react-native-leveldb)
- [react-native-leveldb-level-adapter](https://github.com/swittk/react-native-leveldb-level-adapter)

## License

MIT
