# AR-shopping-app-flutter
졸프2

1. 한글화 - pass
  + flutter pub upgrade - pass ( flutter clean ) pass
  

2. 합치기 - **not yet**
라이브러리 최신화 후 합치기 - pass


ar proj -> 
1. 한글화 - **not yet**

2. 제품 등록 및 glb file 모음 - **fail** -> flutter upgrade -> flutter pub upgrade ->
     방법 -> 원본 프로젝트 가져오기 -> glb 파일 address 바꿔줘야 함

android -> delete -> flutter create .

0. version flutter_macos_arm64_3.22.2-stable
1. ./gradlew --stop (cd android)
3. rm -rf $HOME/.gradle/caches/

build gradle 
min 24
```
    defaultConfig {
        // TODO: Specify your own unique Application ID (https://developer.android.com/studio/build/application-id.html).
        applicationId = "com.example.ar_demo_ti"
        // You can update the following values to match your application needs.
        // For more information, see: https://docs.flutter.dev/deployment/android#reviewing-the-gradle-build-configuration.
        minSdk = 24

```

