# CustomViews
[![](https://jitpack.io/v/hosamazzam/CustomViews.svg)](https://jitpack.io/#hosamazzam/CustomViews)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/hosamazzam/CustomViews/issues)
## Synopsis

CustomViews is library that support customize view like listView, gridView, imageView and textView

## Motivation

sometime you want to insert gridview or list view in scrollview but you can't do that is they not expanded as it has built in scrollview so i made this views tocatre non scroll view for this two views
For textview you can't add fontface for text in xml but in runtime but with this customfonttextview you can do that also if want to make your imageView rounded from corners, Sound awesome right!

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Installing

To get a Git project into your build:

Step 1. Add the JitPack repository to your build file (Gradle)

Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url "https://jitpack.io" }
		}
	}
  
Step 2. Add the dependency in app/build.gradle

	dependencies {
	        implementation 'com.github.hosamazzam:CustomViews:v1.0.5'
	}

## Built With

* [Gradle](https://gradle.org/) - Build Tool
* [JitPack](https://jitpack.io/) - Publish your JVM and Android libraries

## Code Examples

[NonScrollGridView] tag in xml file

```
<com.hosamazzam.customviews.NonScrollGridView
        android:id="@+id/grid_listview"
        android:layout_width="match_parent"
        android:layout_height="match_parent"/>
```

[NonScrollListView] tag in xml file

```
 <com.hosamazzam.customviews.NonScrollListView
    	android:id="@+id/custom_listview"
        android:layout_width="match_parent"
        android:layout_height="match_parent"/>
```

[RoundCornerImageView] tag in xml file

```
 <com.hosamazzam.customviews.RoundCornerImageView
  	    android:id="@+id/custom_imageview"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        app:cornerRadius="20.0"/>
```

[CustomFontTextView] tag in xml file

Notes : font file should put in src\main\assets/fonts/MyFont.ttf

```
 <com.hosamazzam.customviews.CustomFontTextView
  	    android:id="@+id/custom_textview"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        app:fontName="MyFont.ttf"/>
```


## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

