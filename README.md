# Welcome to ShapeView [![Maven Central](https://img.shields.io/jitpack/v/github/AndreyTurcevich/ShapeView.svg)](https://img.shields.io/jitpack/v/github/AndreyTurcevich/ShapeView.svg)

## What's ShapeView

ShapeView is an Android library that provides ability to setup views with shape that you needed by providing for it svg path.

![ShapeView](https://github.com/AndreyTurcevich/ShapeView/blob/master/social_media_preview.png)

## Getting Started

1. Add it in your root build.gradle at the end of repositories:
```
allprojects {
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```
2. Add the dependency
```
dependencies {
    implementation 'com.github.AndreyTurcevich:ShapeView:x.y.z'
}
```
(Please replace `x`, `y` and `z` with the latest version numbers: [![Maven Central](https://img.shields.io/jitpack/v/github/AndreyTurcevich/ShapeView.svg)](https://img.shields.io/jitpack/v/github/AndreyTurcevich/ShapeView.svg)

## Usage

```xml
<com.appogon.lib.ShapeImageView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:src="@drawable/image"
        app:shapePath="M150 0 L75 200 L225 200 Z" />
```

## Result

![ShapeViewExample](https://github.com/AndreyTurcevich/ShapeView/blob/master/triangle_shape_result.jpg)

## License

ShapeView is released under the [Apache License 2.0](https://opensource.org/licenses/Apache-2.0).

```
   Copyright [2019] [Andrew Turtsevich]

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
