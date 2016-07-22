# How-to-Add-Google-Play-Services-to-Android-Studio-Project

In Eclipse, if we want to add Google Play Services to a project, we’ll simply import the play services project to workspace and add it as a library project. But in Android Studio, if you want to add play services, follow below steps.

Open your project’s build.gradle file and add below line under dependencies module. This will add all the Play Services APIs to your project.

dependencies {
    compile 'com.google.android.gms:play-services:7.0.0'
}


You can also selectively add the play services APIs which are necessary to your project.

The below will be add Google Analytics and Maps modules to your app.

dependencies {
    compile 'com.google.android.gms:play-services-base:7.0.0'
    compile 'com.google.android.gms:play-services-analytics:7.0.0'
    compile 'com.google.android.gms:play-services-maps:7.0.0'
}
