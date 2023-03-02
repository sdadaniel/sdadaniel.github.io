---
title: "How to add Fonts"
categories: "react-native"
---

#### 1. Get the fonts required for the app

- ex) ./assets/font

#### 2. Add the configuration to the project

- fileName: ${root}/react-native.config.js

```
module.exports = {
    project: {
        ios:{},
        android:{}
    },
    assets:['./assets/fonts/'],
}
```

#### 3. Link the assets to the project

react-native < 0.69

```
react-native link
```

react-native >= 0.69

```
react-native-asset
```
