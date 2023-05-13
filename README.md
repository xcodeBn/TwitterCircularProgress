# Twitter Circular Progress JetPack Compose

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://github.com/xcodeBn/TwitterCircularProgress/blob/main/LICENSE)

A custom circular progress indicator for Jetpack Compose, inspired by the progress bar used on Twitter's website.

## Usage

You can add the library to your project by adding the following dependency to your app module's `build.gradle` file:

In your root build.gradle at the end of repositories add:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
	
Then add the dependency	

```groovy
dependencies {
    implementation 'com.github.xcodeBn:TwitterCircularProgress:5.0'
}
```




| Parameter   | Type     | Default         | Description                                     |
|-------------|----------|-----------------|-------------------------------------------------|
| arcColor    | Color    | TWITTER_BLUE    | Color of the circular progress arc              |
| modifier    | Modifier | Modifier        | Modifier for the composable                     |
| circleColor | Color    | Color.LightGray | Color of the background circle                  |
| strokeWidth | Dp       | 4.dp            | Width of the stroke for both the arc and circle |
| size        | Dp       | 32.dp           | Size of the composable                          |
