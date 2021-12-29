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
class MainActivity : AppCompatActivity() {

    private lateinit var rampSdk: RampSDK

    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContentView(R.layout.activity_main)
        rampSdk = RampSDK()
        // ...
    }
    // ...
}
