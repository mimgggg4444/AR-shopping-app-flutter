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


xxx
``` 
==============================================================================
Running Gradle task 'assembleDebug'...                               

Running Gradle task 'assembleDebug'...                               
* Get more help at https://help.gradle.org
Running Gradle task 'assembleDebug'...                               

Running Gradle task 'assembleDebug'...                               
BUILD FAILED in 3s
Running Gradle task 'assembleDebug'...                                   3.7s
Error: Gradle task assembleDebug failed with exit code 1
```
xxx


flutter upgrade 하면서 생긴 오류
```
FAILURE: Build failed with an exception.

* What went wrong:
A problem occurred configuring project ':ar_flutter_plugin'.
> Could not create an instance of type com.android.build.api.variant.impl.LibraryVariantBuilderImpl.
   > Namespace not specified. Specify a namespace in the module's build file. See https://d.android.com/r/tools/upgrade-assistant/set-namespace for information about setting the namespace.

     If you've specified the package attribute in the source AndroidManifest.xml, you can use the AGP Upgrade Assistant to migrate to the namespace value in the build file. Refer to https://d.android.com/r/tools/upgrade-assistant/agp-upgrade-assistant for general information about using the AGP Upgrade Assistant.

* Try:
> Run with --stacktrace option to get the stack trace.
> Run with --info or --debug option to get more log output.
> Run with --scan to get full insights.
> Get more help at https://help.gradle.org.

BUILD FAILED in 881ms
Running Gradle task 'assembleDebug'...                           1,616ms
Error: Gradle task assembleDebug failed with exit code 1
```
gradle error 예상 -> android delete 후 flutter create . 소용 없었음.
  해결방안 예상
    flutter downgrade?

4. 
