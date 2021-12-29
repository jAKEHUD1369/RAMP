# RAMP
allprojects {     repositories {         maven { url 'https://jitpack.io' }         maven { url 'https://button.passbase.com/__android' }     } }
allprojects {
    repositories {
        maven { url 'https://jitpack.io' }
        maven { url 'https://button.passbase.com/__android' }
    }
}dependencies {
    implementation 'com.github.RampNetwork:ramp-sdk-android:1.+'
}
