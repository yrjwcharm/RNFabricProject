**_本项目仓库孵化来源_**： **https://gitcode.com/openharmony-sig/ohos_react_native**

#### harmony 自定义 Fabric 组件 RN 端调用

#### react-native 适配 HarmonyFabric 自定义组件官方示例 DEMO 地址

***https://gitcode.com/openharmony-sig/ohos_react_native/tree/master/docs/Samples/FabricComponentSample/***

**_本项目已经把 ReactProject 与 NativeProject 统一结合到一个完整的 ReactNative 项目里面，方便开发者开发学习_**

```json5
  "scripts": {
    "harmony": "hdc rport tcp:8081 tcp:8081 && npm run start",
    "start": "react-native start",
    "bundle-harmony": "react-native bundle-harmony --dev false --bundle-output ./harmony/entry/src/main/resources/rawfile/bundle.harmony.js",
    "codegen": "react-native codegen-harmony --cpp-output-path ./harmony/entry/src/main/cpp/generated --rnoh-module-path ./harmony/entry/oh_modules/@rnoh/react-native-openharmony --no-safety-check"
  },
```

- **yarn harmony 运行项目**
- **yarn bundle-harmony 打包 rn jsbundle 到原生 harmony 工程指定位置**
- **yarn codegen 用来生成自定义组件/自定义 TurboModules 等**
