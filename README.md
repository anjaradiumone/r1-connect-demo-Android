r1-connect-demo-Android
=======================

## R1 Connect Library for Android

### Overview


Downloading LibR1Connect.jar allows you to begin the integration process of adding R1 Connect services to your Android app. All mobile and tablet devices running Android 2.2. and above are supported.

This integration doc assumes you have already set up Google Play Services in your application project, which is needed to use Google Cloud Messaging (GCM), the notification gateway R1 Connect utilizes. Also you will need to have created the app you will be using in R1 Connect.

In order to use R1 Connect with your application you will need a project number (sender ID) and API key from Google. Please visit “GCM Getting Started” [here](http://developer.android.com/intl/ru/google/gcm/gs.html) and create a google project and an API key.

### Setup

The following steps will explain how to integrate with R1 Connect to enable both event tracking and push notifications. You have the option to use the R1 Connect Demo as a sample app project to begin with or you can use your own app project. 
t
Once you have downloaded the R1 Connect Library from this repo you can add it to your project in the libs directory. 

### Configuring your App

![Configure image](https://raw.github.com/radiumone/r1-connect-demo-Android/master/readme-images/image1.png)

Next, to configure how the library will be used in your project you will need to create a file called **r1connect.properties** in the folder called “assets”.

<img src="https://raw.github.com/radiumone/r1-connect-demo-Android/master/readme-images/image2.png" alt="Parameters image" style="width: 1100px; height: 688px;"/>
