# Important andorid dependency

## Overview


A brief description of your project goes here.  Explain its purpose, features, and any relevant information.

## Important Android Dependencies

Below is a list of important dependencies for your Android project using Jetpack Compose and other libraries.

### Ksp
```
ksp = "2.0.20-1.0.24"
alias(libs.plugins.ksp)
ksp = { id = "com.google.devtools.ksp", version.ref = "ksp" }
```

### Retrofit
```
implementation ("com.squareup.retrofit2:retrofit:2.11.0")
implementation("com.squareup.retrofit2:converter-gson:2.11.0")
```


### Ktor
```
implementation ("io.ktor:ktor-client-core:2.3.2")
implementation ("io.ktor:ktor-client-android:2.3.2")
implementation ("io.ktor:ktor-client-gson:2.3.2")
implementation ("io.ktor:ktor-client-content-negotiation:2.3.2")
implementation("io.ktor:ktor-serialization-kotlinx-json:2.3.2")
```

### coil
```
implementation("io.coil-kt.coil3:coil-compose:3.0.0-rc01")
implementation("io.coil-kt.coil3:coil-network-okhttp:3.0.0-rc01")
```

### Koin
```
implementation("io.insert-koin:koin-android:4.0.0")
implementation("io.insert-koin:koin-androidx-compose:4.0.0")
```
### hilt
```
hiltAndroid = "2.51.1"
hilt-android = { module = "com.google.dagger:hilt-android", version.ref = "hiltAndroid" }
hilt-android-compiler = { module = "com.google.dagger:hilt-android-compiler", version.ref = "hiltAndroid" }
implementation (libs.hilt.android)
ksp (libs.hilt.android.compiler)
```

### Room
```
implementation (libs.androidx.room.runtime)
 annotationProcessor (libs.androidx.room.compiler)
ksp (libs.androidx.room.compiler)
roomCompiler = "2.6.1"
roomRuntime = "2.6.1"
androidx-room-compiler = { module = "androidx.room:room-compiler", version.ref = "roomCompiler" }
androidx-room-runtime = { module = "androidx.room:room-runtime", version.ref = "roomRuntime" }
```

### DataStore
```
datastorePreferences = "1.1.1"
androidx-datastore-preferences = { module = "androidx.datastore:datastore-preferences", version.ref = "datastorePreferences" }
implementation (libs.androidx.datastore.preferences)
```
