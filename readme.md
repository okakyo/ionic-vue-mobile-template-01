## Ionic Vue Mobile Template 01 
![Netlify Status](https://api.netlify.com/api/v1/badges/42a821d3-045b-458c-b950-b9b392048c4e/deploy-status)


Hybrid mobile template built with ([latest](https://ionicframework.com/blog/announcing-the-new-ionic-vue-beta/)) vue-ionic and using capacitor for native builds - These templates are from app design inspiration pages on Instagram or Dribble.


[Demo](https://ionic-vue-mobile-template-01.netlify.app)

<a href="https://www.buymeacoffee.com/simomafuxwana" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" width="120px" height="30px" style="height: 30px !important;width: 120px !important;" ></a>

## Project setup
```
npm install
```

### Run on the browser - development
```
npm run serve
```

## Design
![alt text](/design.png "Logo Title Text 1")

## Native

Using [Capacitor](https://capacitorjs.com/docs/getting-started) for native builds

### Prepare native builds

## iOS testing and distribution
1. Download latest Xcode
2. `npm run build`
3. `npx cap add ios`
3. `npx cap copy`
4. `npx cap open ios` Xcode takes a few minutes to index the files; keep an eye at the top of Xcode's window for progress.

[Not compulsory] For sanity check click on the play button in top left. This will prepare and run the app in a simulator, if all goes well you should be able to login and click around. If not, create an issue 🤷 and I will have a look.

*Icons and launch images* - Xcode (v11.5) cannot map icons listed in config.xml so this has to be done manually 😞. In the root folder look for Resources and select Images.xcassets. A panel will show up where you can select AppIcon to add app icons or LaunchImage to add launch images.

## Android testing and distribution
1. Download latest Android Studio
2. `npm run build`
3. `npx cap add android`
3. `npx cap copy`
4. `npx cap open android` Android Studio takes a few minutes to index the files, keep an eye at the bottom of Android Studio for progress.
5. Testing - When indexing is complete, look for a green play button. Click the play button and it will launch the app in an emulator ([See here to setup Emulator](https://developer.android.com/studio/run/managing-avds)) or on the phone if a phone is connected via USB.

## Official docs
- [Blog](https://ionicframework.com/blog/announcing-ionic-vue/)
- [Getting started](https://ionicframework.com/docs/vue/quickstart)
- [Changelog](https://github.com/ionic-team/ionic-framework/blob/master/CHANGELOG.md)


## Credits
-  [manuelroviradesign](https://www.instagram.com/manuelroviradesign/) via [We Love Web Design](https://www.instagram.com/p/CC1GFMrBB6T/) - App design inspiration
- [Tami Maiwashe](https://www.linkedin.com/in/tami-maiwashe-32824a19a/) - Documentation

## Contact
- [@dlodeprojuicer](https://twitter.com/dlodeprojuicer) on Twitter
