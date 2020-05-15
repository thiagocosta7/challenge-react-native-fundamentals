### [Level 3] Challenge: React Native fundamentals (GoMarketplace) :rocket:
This application was developed using [React Native](https://reactnative.dev/), [TypeScript](https://www.typescriptlang.org/), [AsyncStorage](https://github.com/react-native-community/async-storage), [Context API](https://pt-br.reactjs.org/docs/context.html), and simulates a virtual store that allows you to increase and decrease a shopping cart, as well as check the sum of price and quantity of products added.

### Running Locally

```sh
# install packages
yarn

# if emulating on iOS, navigate into 'ios' folder and run
pod install

# run a fake API to fetch sample products
yarn json-server server.json -p 3333

# start emulator on iOs
react-native run-ios

# or Android
react-native run-android
```
