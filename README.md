# @shamilovtim/react-native-leveldb-async

`abstract-level` adapter for `react-native-leveldb`

Passes nearly all tests of `abstract-level` except for "async-iterator-test.js".

## Installation

```sh
yarn add @shamilovtim/react-native-leveldb-async
```

### Setup polyfills

You will need to polyfill TextEncoder, TextDecoder and Buffer. Take a look at the sourcecode and documentation of [web5-react-native-polyfills](https://github.com/TBD54566975/web5-react-native-polyfills) for an example of how to set these up.

## Credits

- [react-native-leveldb](https://github.com/greentriangle/react-native-leveldb)
- [react-native-leveldb-level-adapter](https://github.com/swittk/react-native-leveldb-level-adapter)
- [expo-level](https://www.npmjs.com/package/expo-level)

## License

MIT
