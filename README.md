# Android App regular (often used) dependencies
Use the below deps and copy and paste them into your project in the correct places.

With all of these dependencies there will most likely be version updates at the time that you are copying and pasting, so be aware.

# Retrofit

## Desc
These provide your app with the retrofit ability. Meaning that you can declare and call url endpoints from your application and with the second dep you can cast the response into JSON models that you specify.

## Deps
Copy these dependencies into the app/build.gradle file in the `dependencies` block

```
    implementation 'com.squareup.retrofit2:retrofit:2.9.0'
    implementation 'com.squareup.retrofit2:converter-gson:2.9.0'
```

# Hilt

## Desc
These provide your app with the retrofit ability. Meaning that you can declare and call url endpoints from your application and with the second dep you can cast the response into JSON models that you specify.

## Deps
Copy these dependencies into the app/build.gradle file in the `dependencies` block

```
    implementation "com.google.dagger:hilt-android:2.28.3-alpha"
    kapt "com.google.dagger:hilt-android-compiler:2.28.3-alpha"
    implementation 'androidx.hilt:hilt-lifecycle-viewmodel:1.0.0-alpha02'
    kapt 'androidx.hilt:hilt-compiler:1.0.0-alpha02'
```
NOTE: the numbers here are important otherwise you wont get ViewModelInject along side

Copy this line into the project level build.gradle file in the `dependencies` block

```
    classpath 'com.google.dagger:hilt-android-gradle-plugin:2.28-alpha'
```

Copy these lines in order to include hilt testing deps for instrumentation tests

```
    kaptAndroidTest "com.google.dagger:hilt-android-compiler:2.28.3-alpha"
    debugImplementation "androidx.fragment:fragment-testing:1.3.0-alpha08"
    androidTestImplementation "com.google.dagger:hilt-android-testing:2.28.3-alpha"
    androidTestImplementation "androidx.test:core-ktx:1.3.0"
```

# Mockito

## Desc

## Deps
Copy these dependencies into the app/build.gradle file in the `dependencies` block for both unit and instrumentation tests

```
    testImplementation "org.mockito:mockito-core:3.5.6"
    testImplementation "com.nhaarman.mockitokotlin2:mockito-kotlin:2.2.0"
    androidTestImplementation "org.mockito:mockito-android:3.0.0"
    androidTestImplementation "androidx.arch.core:core-testing:2.1.0"
    androidTestImplementation "com.nhaarman.mockitokotlin2:mockito-kotlin:2.2.0"
```

# Material

## Desc

## Deps

```
    implementation "com.google.android.material:material:1.1.0"
```

# Navigation Component

## Desc

## Deps
Copy these dependencies into the app/build.gradle file in the `dependencies` block

```
    implementation "androidx.navigation:navigation-fragment-ktx:2.3.0"
    implementation "androidx.navigation:navigation-ui-ktx:2.3.0"
```

# Useful KTX functions

## Desc

## Deps
Copy these dependencies into the app/build.gradle file in the `dependencies` block

```
    implementation "androidx.lifecycle:lifecycle-runtime-ktx:2.2.0"
    implementation "androidx.lifecycle:lifecycle-livedata-ktx:2.2.0"
    implementation "androidx.lifecycle:lifecycle-livedata-core-ktx:2.2.0"
```

# Useful Viewmodel delegate 'by viewmodels'

## Desc

## Deps
Copy these dependencies into the app/build.gradle file in the `dependencies` block

```
    implementation "androidx.fragment:fragment-ktx:1.2.5"
```

# Room

## Desc
Enables you to use the Room SQL Database functionality in your app

## Deps
Copy these dependencies into the app/build.gradle file in the `dependencies` block

```
    implementation 'androidx.room:room-runtime:2.2.3'
    implementation 'androidx.room:room-ktx:2.2.3'
    kapt "androidx.room:room-compiler:2.2.3"
```

# Robolectric

## Desc

## Deps

```
    testImplementation "androidx.test.ext:junit:1.1.1" 
    testImplementation "org.robolectric:robolectric:4.3.1"
```

# Lottie

## Desc

## Deps

```
    implementation "com.airbnb.android:lottie:3.4.2"
```

# Glide

## Desc

## Deps

```
    implementation 'com.github.bumptech.glide:glide:4.11.0'
```

# Useful others

```
    implementation 'androidx.browser:browser:1.2.0'
    implementation 'androidx.viewpager2:viewpager2:1.0.0'
    implementation 'androidx.core:core-ktx:1.3.1'
    implementation 'androidx.multidex:multidex:2.0.1'
    implementation 'androidx.appcompat:appcompat:1.2.0'
    implementation 'androidx.recyclerview:recyclerview:1.1.0'
    implementation 'androidx.cardview:cardview:1.0.0'
    implementation 'androidx.annotation:annotation:1.1.0'
    implementation 'androidx.legacy:legacy-support-v4:1.0.0'
    implementation 'androidx.vectordrawable:vectordrawable:1.1.0'
    implementation 'androidx.vectordrawable:vectordrawable-animated:1.1.0'
    implementation 'androidx.constraintlayout:constraintlayout:2.0.2'
    implementation 'androidx.lifecycle:lifecycle-extensions:2.2.0'
    implementation 'androidx.lifecycle:lifecycle-viewmodel-ktx:2.2.0'
    implementation 'androidx.lifecycle:lifecycle-livedata-ktx:2.2.0'
    implementation 'androidx.lifecycle:lifecycle-runtime-ktx:2.2.0'
    implementation 'androidx.activity:activity-ktx:1.2.0-beta01'
    implementation 'androidx.fragment:fragment-ktx:1.3.0-beta01'
    implementation "androidx.fragment:fragment-ktx:1.2.5"
    implementation 'androidx.preference:preference-ktx:1.1.1'
    implementation 'com.google.android.material:material:1.2.0'
    implementation 'com.google.android.gms:play-services-analytics:17.0.0'
    implementation 'androidx.dynamicanimation:dynamicanimation:1.0.0'
```
