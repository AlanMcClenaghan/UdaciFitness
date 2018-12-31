### UdaciFitness

Before you submit your application to either app store, you need to "package" it appropriately. The iOS App Store will ask you for a .ipa ("iOS App Store Package") file and the Android Google Play store will ask you for a .apk ("Android Application Package") file. When you create either an ipa or a apk file, you're essentially creating a bundle of all of the necessary information that either App store needs in order to process and run your application.

The easiest way to generate both the .apk and the .ipa files is to use Expo's exp CLI. First, run npm install -g exp. Once that's installed (and after you've configured your app.json file), you can run exp build:ios to build your .ipa file, and exp build:android to build your .apk file.

Note that these will take anywhere from 10-20 minutes to build, so you'll need to be patient. To check the status of the build you can run exp build:status. Eventually that command will give you a URL where you can go to download either your .ipa or .apk files.