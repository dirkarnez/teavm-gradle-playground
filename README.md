teavm-gradle-playground
=======================
- https://services.gradle.org/distributions/gradle-8.13-bin.zip
- https://github.com/adoptium/temurin11-binaries/releases/download/jdk-11.0.26%2B4/OpenJDK11U-jdk_x64_windows_hotspot_11.0.26_4.zip

### Gradle Documentation
- [Installing Gradle](https://docs.gradle.org/current/userguide/installation.html#ex-installing-manually)
- [Compatibility Matrix](https://docs.gradle.org/current/userguide/compatibility.html#compatibility)
- [Command-Line Interface Reference](https://docs.gradle.org/current/userguide/command_line_interface.html)

### TeaVM Documentation
- [TeaVM — Getting started](https://teavm.org/docs/intro/getting-started.html)

### Samples
- [teavm/samples at master · konsoletyper/teavm](https://github.com/konsoletyper/teavm/tree/master/samples)
- https://github.com/heruoji/Katana/
- https://github.com/konsoletyper/tnoodle-example


### Notes
- gradle's configuration cache should be disabled
  - [Configuration cache](https://docs.gradle.org/8.13/userguide/configuration_cache.html#config_cache:usage)
  - [`gradle.properties`](./gradle.properties)
- try `./gradlew :appRunWar`
