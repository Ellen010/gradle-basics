# gradle-basics
Basic lines to insert your intro message
// build.gradle

plugins {
    id 'java'
}

repositories {
    jcenter()
}

dependencies {
    implementation 'com.google.guava:guava:30.1-jre'
    // Gradle will automatically download the specified version of the Guava library from the configured repositories
}

task hello {
    doLast {
        println 'Here is my introductory message!'
        //Type whatever you wanna say once the program executed
    }
}
