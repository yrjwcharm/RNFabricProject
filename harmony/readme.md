#### 若运行oh-package.json5显示错误，是因为由于react_native_openharmony仓库太大，没有上传github

**如果想获取react_native_openharmony.har这个库，首先在RNFabricProject工程目录下执行npm install**
***在node_modules/@react-native-oh/react-native-harmony/下找到，然后复制一份到Harmony原生工程libs目录下就可以了***
**然后执行ohpm install即可**
