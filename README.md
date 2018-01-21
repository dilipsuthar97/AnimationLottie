# AnimationLottie
This is my simple lottie Animation App

# How to use or Impement
This code consist a simple loading animation in the App
use loading.json file into the assets folder for do this

<com.airbnb.lottie.LottieAnimationView

android:id="@+id/animation_view"

android:layout_width="match_parent"
android:layout_height="match_parent"
android:layout_gravity="center"a
app:lottie_autoPlay="true"
app:lottie_colorFilter="@color/colorAccent"
app:lottie_fileName="loading.json"
app:lottie_loop="true"/>
        
# Use this library Lottie dependency to your build.gradle(Module:app) file

dependencies {
        compile 'com.airbnb.android:lottie:2.0.0'
    }
