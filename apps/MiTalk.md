---
layout: app

permalink: /MiTalk/
description: mitalk desktop

icons:
  - MiTalk/icons/128x128/mitalk.png

screenshots:
  - MiTalk/screenshot.png

authors:

links:

desktop:
  Desktop Entry:
    Name: 米聊
    Comment: mitalk desktop
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: mitalk
    StartupWMClass: Mitalk Desktop
    X-AppImage-Version: 4.0.32
    MimeType: x-scheme-handler/miliao
    Categories: Network
    X-AppImage-BuildId: 1NlW5ikjiT0jahpljch8wwinQg2
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  description: mitalk desktop
  license: 'null'
  repository:
    type: git
    url: http://v9.git.n.xiaomi.com/MitalkClient/MiTalk_Desktop.git
  homepage: http://www.miliao.com
  main: "./dist/electron/main.js"
  dependencies:
    "@chenfengyuan/vue-qrcode": "^1.0.0"
    archiver: "^3.0.0"
    axios: "^0.18.0"
    crypto-js: "^3.1.9-1"
    electron-json-storage: "^4.1.6"
    electron-localstorage: "^1.0.5"
    electron-log: "^3.0.5"
    electron-updater: "^4.0.6"
    ffi: "^2.3.0"
    file-type: "^11.1.0"
    fluent-ffmpeg: "^2.1.2"
    google-protobuf: "^3.7.0"
    iview: "^3.1.0"
    jquery: "^3.4.1"
    jquery.caret: "^0.3.1"
    ks3: "^0.5.0"
    read-chunk: "^3.2.0"
    request: "^2.88.0"
    screenshot-desktop: "^1.8.0"
    sqlite3: "^4.0.8"
    typeorm: "^0.2.15"
    v-viewer: "^1.4.1"
    vue: "^2.6.10"
    vue-electron: "^1.0.6"
    vue-router: "^3.0.1"
    vue-scroll-loader: "^1.1.6"
    vue-uweb: "^0.2.1"
    vuex: "^3.1.0"
    vuex-electron: "^1.0.0"
---