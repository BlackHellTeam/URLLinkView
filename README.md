LeoCardz Link Preview for Android
=================================

Developed by <a href='https://github.com/LeonardoCardoso' target='_blank'>@LeonardoCardoso</a>. 

[![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-Android--Link--Preview-green.svg?style=true)](https://android-arsenal.com/details/1/2755)

This a version for Android of my web [Facebook Link Preview](http://lab.leocardz.com/facebook-link-preview-php--jquery/ "Facebook Link Preview").

It makes a preview from an url, grabbing all informations. Such as title, relevant texts and images.

![Preview](http://i.imgur.com/VSejRyV.gif)

For more information about this, please access [Android Link Preview](http://android.leocardz.com/android-link-preview/ "Android Link Preview").

For a sample app, please install it from [Android Link Preview on Google Play](https://play.google.com/store/apps/details?id=com.leocardz.link.preview&feature=search_result "Android Link Preview on Google Play").

Note - Required Libs: [jsoup](http://jsoup.org/ "jsoup") is a smart lib to get the htlm code.


## How to use with Gradle

Simply add the repository to your build.gradle file:
```groovy
repositories {
	jcenter()
	maven { url 'https://github.com/leonardocardoso/mvn-repo/raw/master/maven-deploy' }
}
```

And you can use the artifacts like this:
```groovy
dependencies {
    compile 'org.jsoup:jsoup:1.8.3' // required
	compile 'com.leocardz:link-preview:1.2.1@aar'
	// ...
}
```

Apps using Android Link Preview
=================================
1. [Unshorten It](https://play.google.com/store/apps/details?id=com.leocardz.url.unshortener&feature=search_result "Unshorten It")

2. ...


Contact
=================================
If you are using this lib, let me know contacting me at android@leocardz.com then I add your app here in a list


License
=================================

    Copyright 2013 Leonardo Cardoso

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
