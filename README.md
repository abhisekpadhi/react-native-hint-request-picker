# Fix
This fork fixes the following issue.
Errors in original:
```
e: /Users/abhisek/IdeaProjects/ReactNativeApp/node_modules/react-native-hint-request-picker/android/src/main/java/com/reactnativehintrequestpicker/HintRequestPickerModule.kt: (52, 43): Type inference failed. Expected type mismatch: inferred type is Credential? but Credential was expected
e: /Users/abhisek/IdeaProjects/ReactNativeApp/node_modules/react-native-hint-request-picker/android/src/main/java/com/reactnativehintrequestpicker/HintRequestPickerModule.kt: (63, 43): Type inference failed. Expected type mismatch: inferred type is Credential? but Credential was expected
```

# react-native-hint-request-picker

React native wrapper for HintRequest api on android

## Installation

### NPM
```sh
npm install react-native-hint-request-picker
```

### Yarn
```sh
yarn add react-native-hint-request-picker
```

## Usage

### Picker for Phone number
```js
import { getPhoneNumber } from "react-native-hint-request-picker";

// ...

const result = await getPhoneNumber();
```

### Picker for Google Accounts
```js
import  { getGoogleAccount } from "react-native-hint-request-picker";

// ...

const result = await getGoogleAccount();
```

## Contributing

See the [contributing guide](CONTRIBUTING.md) to learn how to contribute to the repository and the development workflow.

## License

MIT
