projectName: Durak
scm:
  type: git
  url: https://github.com/jabool1/Durakaz.git
  branch: main
targets:
  android:
    name: Android Build
    platform: android
    unityVersion: 2021.3.0f1
    enabled: true
    autoBuild: true
    cleanBuild: true
    scenes:
      - Assets/Scenes/MainMenu.unity
      - Assets/Scenes/Game.unity
