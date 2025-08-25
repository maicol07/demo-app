# Compose Multiplatform Application

### Web Distribution
Build web distribution: `./gradlew :composeApp:composeCompatibilityBrowserDistribution`  
Deploy a dir `composeApp/build/dist/composeWebCompatibility/productionExecutable` to a web server  

### JS Browser
Run the browser application: `./gradlew :composeApp:jsBrowserDevelopmentRun --continue`  
Run browser UI tests: `./gradlew :composeApp:jsBrowserTest`  

### Wasm Browser
Run the browser application: `./gradlew :composeApp:wasmJsBrowserDevelopmentRun --continue`  
Run browser UI tests: `./gradlew :composeApp:wasmJsBrowserTest`  

