# CirclesLoadingView

Android Google Style Loading Animation Library

[![](https://jitpack.io/v/ibrahimsn98/CirclesLoadingView.svg)](https://jitpack.io/#ibrahimsn98/CirclesLoadingView)
[![API](https://img.shields.io/badge/API-16%2B-brightgreen.svg?style=flat)](https://android-arsenal.com/api?level=16)

##  GIF

<img src="https://raw.githubusercontent.com/ibrahimsn98/CirclesLoadingView/master/art/gif.gif?raw=true"/>

## Usage

-   Add view into your layout file
```xml
<me.ibrahimsn.lib.CirclesLoadingView
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    app:circleRadius="8dp"
    app:circleMargin="8dp"
    app:animDistance="10dp"
    app:animDuration="500"
    app:animDelay="150"
    app:animInterpolator="accelerateDecelerate"
    app:layout_constraintTop_toTopOf="parent"
    app:layout_constraintBottom_toBottomOf="parent" />
```

## Setup

```gradle
allprojects {
	repositories {
		...
		maven { url 'https://jitpack.io' }
	}
}

dependencies {
    implementation 'com.github.ibrahimsn98:CirclesLoadingView:1.0'
}
```

## License

```
MIT License

Copyright (c) 2019 İbrahim Süren

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```


> Follow me on Twitter [@ibrahimsn98](https://twitter.com/ibrahimsn98)
