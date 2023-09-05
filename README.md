# darttmp

個人用のdart言語メモプログラム置き場

[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/devlights/darttmp)

```sh
$ task init
task: [clean] rm -rf app
task: [init] dart create app
Creating app using template console...

  .gitignore
  analysis_options.yaml
  CHANGELOG.md
  pubspec.yaml
  README.md
  bin/app.dart
  lib/app.dart
  test/app_test.dart

Running pub get...                     3.2s
  Resolving dependencies...
  Changed 46 dependencies!

Created project app in app! In order to get started, run the following commands:

  cd app
  dart run


$ task run
Building package executable... 
Built app:app.
Hello world: 42!


$ task clean
task: [clean] rm -rf app
```