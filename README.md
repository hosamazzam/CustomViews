# CustomViews
[![](https://jitpack.io/v/hosamazzam/CustomViews.svg)](https://jitpack.io/#hosamazzam/CustomViews)
[![HitCount](https://hitt.herokuapp.com/hosamazzam/CustomViews.svg)](https://github.com/hosamazzam/CustomViews)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/hosamazzam/CustomViews/issues)
## Synopsis

CustomViews is library that support customize view like listview, gridview and textview

## Motivation

sometime you want to insert gridview or list view in scrollview but you can't do that is they not expanded as it has built in scrollview so i made this views tocatre non scroll view for this two views
For textview you can't add fontface for text in xml but in runtime but with this customfonttextview you can do that, Sound awesome right!

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
	        compile 'com.github.hosamazzam:CustomViews:v1.0.2'
	}

## Built With

* [Gradle](https://gradle.org/) - Build Tool
* [JitPack](https://jitpack.io/) - Publish your JVM and Android libraries

## Code Examples

<NonScrollGridView> tag in xml file

```
<com.hosamazzam.customviews.NonScrollGridView
                android:id="@+id/grid_listview"
                android:layout_width="match_parent"
                android:layout_height="match_parent"
               />
```

<NonScrollListView> tag in xml file

```
 <com.hosamazzam.customviews.NonScrollListView
  	android:id="@+id/custom_listview"
        android:layout_width="match_parent"
        android:layout_height="match_parent"/>

```


## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

