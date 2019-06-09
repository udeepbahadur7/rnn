Save your time configuring React Native Navigation(RNN)
Configuring React Native Navigation can be pain in ass sometimes. Configuring correct version of gradle, and other configuration can consume your precious hours. Just remove the android folder in your project and clone this project.Then run `npm  run android` to build your application after updating your package.json

"scripts": {
  ...
  "android": "cd ./android && ./gradlew app:assembleDebug && ./gradlew installDebug"
}


Dont forget to update your index.js as mentioned in docs

Currently, I've only configured RNN for android. As soon as, I get my hands on Mac, I'll update this repo.

Thanks
