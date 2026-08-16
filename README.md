# LanDen Labs - all-stop
<br>18-Apr-2026
<br>API 36 AndroidX Java
<br>[Home website](https://landenlabs.com/android/index.html)

<img src="screenshots/landenlabs.webp" width="300" alt="Logo">

An Android utility application to manage and stop processes, view process details, and monitor system memory.

## Features

- **Process Management**: View a list of running processes and packages.
- **Stop Background Tasks**: Easily terminate background processes to free up memory.
- **Stop List**: Maintain a list of specific processes to be targeted.
- **Process Details**: View in-depth information about individual processes.
- **Memory Monitor**: Real-time display of available system memory.
- **Modern Android Stack**: Updated to use the latest Android tools and practices.

## Technical Specifications

- **Language**: Pure Java (Kotlin-free)
- **Minimum SDK**: 21 (Android 5.0)
- **Target/Compile SDK**: 36 (Android 16)
- **Java Version**: 17 (Toolchain)
- **Build System**: Gradle 9.4.1 with Version Catalog support
- **AGP**: 9.1.1

## Key Dependencies

- `androidx.appcompat`: For modern UI components.
- `com.jaredrummler:android-processes`: For advanced process management.

## Project Structure

- `app/`: Main application module.
- `gradle/libs.versions.toml`: Centralized dependency management.

## Development

The project has been modernized to use:
- **Gradle 9.x**: Utilizing the latest performance improvements and configuration cache.
- **New Variant API**: Uses `androidComponents` for APK renaming and resource value injection.
- **Java 17**: Leverages modern Java features and performance.

### License

```
Copyright 2026 Dennis Lang (LanDen Labs)

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

 http://www.apache.org/licenses/LICENSE-2.0
Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
See [LICENSE](LICENSE) for the full license text.

---
Author: Dennis Lang  
Website: [landenLabs.com](https://landenLabs.com/)
