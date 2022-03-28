# SmartShopperAPI

### Author- Sheila Sharon Wambui Karani.




## Table of contents

* [Introduction](#Introduction)

* [Features](#Features)

* [Setup](#setup)

* [Technologies](#technologies)


* [Contact](#contact)

* [Licence](#Licence)

## Introduction

This is a shop/ supermarket self checkout app that is designed to make in store shopping easier. It allows one to scan products from their cart,and check them out without going through the hassle of queuing to be attended by a cashier.
## Features
1. Scanning items
1. Adding items to cart
1. Checkout

## Upcoming Features
1. Product image search
1. Finance analysis/shopping budgeting
1. Recommendations features(offers,products,shops)

## Setup
### Prerequisites
Android Studio
Jdk

## Technologies


### Testing
For testing i used the following libraries

```
androidTestImplementation 'androidx.test.ext:junit:1.1.1'
androidTestImplementation 'androidx.test:rules:1.2.0'
androidTestImplementation 'androidx.test 1.2.0'
androidTestImplementation 'androidx.test.espresso:espresso-core:3.2.0'
testImplementation 'org.robolectric:robolectric:4.3.1'
```
### Google vision
```
implementation 'com.google.android.gms:play-services-vision:20.0.0'
```

### Firebase
```
implementation 'com.google.firebase:firebase-analytics:17.4.2'
implementation 'com.firebaseui:firebase-ui-database:3.3.1'
implementation 'com.google.firebase:firebase-core:17.4.2'
implementation 'com.google.firebase:firebase-database:19.3.0'
implementation 'com.google.firebase:firebase-auth:19.3.1'
```
### Retrofit(Api)
```
implementation 'com.squareup.retrofit2:converter-gson:2.5.0'
implementation 'com.squareup.okhttp3:okhttp:3.12.0'
```
### Apis Used
```
Mobile vision api - for  scanning of barcodes.
SmartCheckotAPI -used to retrieve items using barcodes
```





## Contact
In case of any question or contributions, contact me at sheilasharon10@gmail.com


## Licence
MIT License

Copyright (c) 2022 Sheila Sharon

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







