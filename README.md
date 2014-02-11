facebook's Conceal
============

I created this project for an easier deployment of facebook's conceal.

All credit goes to: https://github.com/facebook/conceal 

Usage Maven Repo
----------------

I've uploaded the `.aar` in my maven repository. You only need to add following lines to your `build.gradle` to add the dependency:
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