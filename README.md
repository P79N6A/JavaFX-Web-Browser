# JAVAFX-WEB-Browser 
You always dreamed how to make a WebBrowser in JavaFX? Well then you are in the right place . It took me 2 days to make it and it is here for you ready to test and improve it .

![browser](https://user-images.githubusercontent.com/20374208/49159861-1d466d00-f32e-11e8-8718-d6b2b3d41b42.jpg)



[![Latest Version](https://img.shields.io/github/release/goxr3plus/JavaFX-Web-Browser.svg?style=flat-square)](https://github.com/goxr3plus/JavaFX-Web-Browser/releases)
[![GitHub contributors][contributors-image]][contributors-url]
[![HitCount](http://hits.dwyl.io/goxr3plus/JavaFX-Web-Browser.svg)](http://hits.dwyl.io/goxr3plus/JavaFX-Web-Browser)
[![Total Downloads](https://img.shields.io/github/downloads/goxr3plus/JavaFX-Web-Browser/total.svg)](https://github.com/goxr3plus/JavaFX-Web-Browser/releases)

[contributors-url]: https://github.com/goxr3plus/JavaFX-Web-Browser/graphs/contributors
[contributors-image]: https://img.shields.io/github/contributors/goxr3plus/JavaFX-Web-Browser.svg
[browser-jitpack-url]: https://jitpack.io/#goxr3plus/JavaFX-Web-Browser

> Older Java 8 and 9 releases [here](https://github.com/goxr3plus/JavaFX-Web-Browser/wiki/Java-8-and-9-Releases)


### How to add this browser inside your application 


1.

You have to add it as a dependency , you can use [JitPack.io][browser-jitpack-url]

> Step 1. Add the JitPack repository to your build file

```XML
<repositories>
	<repository>
		  <id>jitpack.io</id>
		  <url>https://jitpack.io</url>
	</repository>
</repositories>

```

> Step 2. Add the dependency

```xml
 <dependency>
	   <groupId>com.github.goxr3plus</groupId>
	   <artifactId>JavaFX-Web-Browser</artifactId>
	   <version>Tag</version>
  </dependency>
```

2. 

Then from inside your code you can create an intance or multiple instances of Browser like this:

``` JAVA
public WebBrowserController webBrowser = new WebBrowserController();
```

and add it for example inside a BorderPane :

```JAVA
BorderPane borderPane = new BorderPane( webBrowser );
```

Happy :) ?  Cause i am ...

---


