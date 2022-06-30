# CREATION STEPS

## ANDROID ENVIRONMENT

1. JAVA_HOME=C:\Program Files\Java\jdk-18.0.1.1
1. ANDROID_HOME=C:\Users\victor.reis\AppData\Local\Android\Sdk
1. ANDROID_SDK_ROOT=C:\Users\victor.reis\AppData\Local\Android\Sdk
1. ANDROID_AVD_HOME=C:\Users\victor.reis\.android\avd
1. Path
    * %ANDROID_HOME%\platform-tools
    * %ANDROID_HOME%\tools

## Initialization

1. Override the "ReactNativeUltimate" and the "react-native-ultimate" for your project's name `npx react-native init ReactNativeUltimate --template react-native-template-typescript --skip-install --title react-native-ultimate --directory react-native-ultimate`
1. Run `echo "# react-native-ultimate" >> README.md`
1. Run `git init`
1. Run `git add .`
1. Run `git commit -m "chore: initialization"`
1. Run `git branch -M main`
1. Run `git remote add origin https://github.com/victorreis/react-native-ultimate.git`
1. Run `git push -u origin main`
