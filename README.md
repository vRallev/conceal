Deprecated
============

Luckily there is now the official artifact in maven central. Use this one and not mine anymore. You find more information about it here: https://github.com/facebook/conceal

~~facebook's Conceal~~
============

~~I created this project for an easier deployment of facebook's conceal.~~

~~All credit goes to: https://github.com/facebook/conceal~~

~~Last commit: 2014-02-05~~

~~Usage Maven Repo~~
----------------

~~I've uploaded the `.aar` in my maven repository. You only need to add following lines to your `build.gradle` to add the dependency:~~
```groovy
repositories {
    maven {
        url 'https://raw.github.com/vRallev/mvn-repo/master/'
    }
}

dependencies {
    compile 'com.facebook.crypto:conceal:1.0.0'
}
```
