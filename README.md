# Tinted ProgressBar
[![](https://jitpack.io/v/jchernandez/TintedProgressBar.svg)](https://jitpack.io/#jchernandez/TintedProgressBar)

## What is a Tinted ProgressBar?

TintedProgressBar is a simple `ProgressBar` than can be tinted from the `xml`.

<div align="center">
  <img height="355" src="raw/screen.png"/>
</div>

## Usage
Simply add the View to your layout:
```xml
<com.rojoxpress.TintedProgressBar
        style="?android:attr/progressBarStyleLarge"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_centerVertical="true"
        app:tint_color="@color/colorAccent"
        android:layout_centerHorizontal="true"
        android:id="@+id/progressBar" />
```
# Gradle Dependency

### Repository
The Gradle dependency is available via [JitPack](https://jitpack.io/#jchernandez/SlideButton).

Add it in your root build.gradle at the end of repositories:
```gradle
allprojects {
	repositories {
		...
		maven { url "https://jitpack.io" }
	}
}
```

 Add the dependency:
```gradle
dependencies {
    compile 'com.github.jchernandez:TintedProgressBar:0.0.1'
}
```
