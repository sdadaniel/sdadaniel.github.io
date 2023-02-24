---
layout: post
title: "How to add Fonts"
categories: "react-native"
---

## Adding fonts the React Native

#### Get the fonts required for the app

- ex) ./assets/font

#### Add the configuration to the project

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

#### Link the assets to the project

react-native < 0.69

```
react-native link
```

react-native >= 0.69

```
react-native-asset
```
