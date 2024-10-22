# react native 0.70.6

## node version

v18.20.4

## xcode version

16.0


## init by

https://reactnative.dev/docs/getting-started-without-a-framework

npx @react-native-community/cli@latest init AwesomeProject --version 0.70.6

## error and fix

error: react native No template named 'unary_function' in namespace 'std'; did you mean '__unary_function'?
fix: https://github.com/facebook/react-native/issues/37748#issuecomment-1580334650

error: react native FlipperKit/FlipperPlatformWebSocket.mm:57:46 Called object type 'facebook::flipper::SocketCertificateProvider' (aka 'int') is not a function or function pointer

fix: https://github.com/facebook/react-native/issues/43335#issuecomment-1980246463