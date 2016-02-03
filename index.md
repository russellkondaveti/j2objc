---
layout: default
root_nav: devsite-doc-set-nav-active
page_type: landing-page
---

## What J2ObjC Is ##
J2ObjC is an open-source command-line tool from Google that translates
Java source code to Objective-C for the iOS (iPhone/iPad) platform. This tool
enables Java source to be part of an iOS application's build, as no editing
of the generated files is necessary. The goal is to write an app's non-UI
code (such as application logic and data models) in Java, which is then
shared by web apps (using [GWT](http://www.gwtproject.org/)), Android apps,
and iOS apps.

<div class="devsite-product-button-row"><a href="{{site.github.url}}docs/Getting-Started.html" 
  class="button button-raised button-text-black">Get Started</a></div>

J2ObjC supports most Java language and runtime features required by
client-side application developers, including exceptions, inner and
anonymous classes, generic types, threads and reflection. JUnit test
translation and execution is also supported.

## What J2ObjC isn't ##
J2ObjC does not provide any sort of platform-independent UI toolkit, nor are
there any plans to do so in the future. We believe that iOS UI code needs to
be written in Objective-C, Objective-C++ or Swift using Apple's iOS SDK (Android
UIs using Android's API, web app UIs using GWT, etc.).

J2ObjC cannot convert Android binary applications. Developers must have source
code for their Android app, which they either own or are licensed to use.

## Requirements ##

* JDK 1.7 or higher
* Mac workstation or laptop
* Mac OS X 10.9 or higher
* Xcode 6 or higher