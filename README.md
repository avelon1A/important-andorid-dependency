# important-andorid-dependency
dependencies {
    // Jetpack Compose UI
    implementation("androidx.compose.ui:ui:<version>")
    implementation("androidx.compose.material:material:<version>")
    implementation("androidx.compose.ui:ui-tooling:<version>")
    implementation("androidx.activity:activity-compose:<version>")

    // Dependency Injection
    // Hilt
    implementation("com.google.dagger:hilt-android:<version>")
    kapt("com.google.dagger:hilt-compiler:<version>")
    // Koin
    implementation("io.insert-koin:koin-android:<version>")
    implementation("io.insert-koin:koin-androidx-compose:<version>")

    // Networking
    // Retrofit
    implementation("com.squareup.retrofit2:retrofit:<version>")
    implementation("com.squareup.retrofit2:converter-gson:<version>")
    // OkHttp
    implementation("com.squareup.okhttp3:okhttp:<version>")
    implementation("com.squareup.okhttp3:logging-interceptor:<version>")

    // Image Loading
    implementation("io.coil-kt:coil-compose:<version>")

    // Coroutines
    implementation("org.jetbrains.kotlinx:kotlinx-coroutines-core:<version>")
    implementation("org.jetbrains.kotlinx:kotlinx-coroutines-android:<version>")

    // ViewModel
    implementation("androidx.lifecycle:lifecycle-viewmodel-compose:<version>")

    // Navigation
    implementation("androidx.navigation:navigation-compose:<version>")

    // Testing
    // Compose Testing
    androidTestImplementation("androidx.compose.ui:ui-test-junit4:<version>")
    debugImplementation("androidx.compose.ui:ui-test-manifest:<version>")

    // Accompanist (for additional features)
    implementation("com.google.accompanist:accompanist-coil:<version>")
    implementation("com.google.accompanist:accompanist-navigation-animation:<version>")
}
