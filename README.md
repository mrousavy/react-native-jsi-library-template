# react-native-jsi-library-template

A template for creating JSI libraries for React Native with my style and setup.

My libraries always have cool GitHub actions for linting and building, strong ESLint and TypeScript setup, an example app, up-to-date dependencies, and a lazy and stable install function to initialize the JSI Module.

The JSI Module can do anything with the `jsi::Runtime`, whether it's a single function (see react-native-mmkv) or an entire HostObject (see react-native-fast-crypto or my talk about HostObjects).

---

## Installation

### React Native

```sh
yarn add react-native-...
cd ios && pod install
```

### Expo

```sh
expo install react-native-...
expo prebuild
```

## Usage

TODO: Add usage example

## Sponsors

TODO: List sponsors here

## Limitations

As the library uses JSI for synchronous native methods access, remote debugging (e.g. with Chrome) is no longer possible. Instead, you should use [Flipper](https://fbflipper.com).

## Adopting at scale

react-native-jsi-library-template was built by me in my free time. For enterprise support or other business inquiries, contact us at <a href="mailto:hello@margelo.io?subject=Hello!">hello@margelo.io</a>!

## Contributing

See the [contributing guide](CONTRIBUTING.md) to learn how to contribute to the repository and the development workflow.

## License

MIT
