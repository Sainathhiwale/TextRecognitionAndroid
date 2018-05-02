# Text Recognition for Android using Google Mobile Vision.

# we will create a simple Android app that uses Google Mobile Vision API’s for Optical character recognition(OCR).
The Mobile Vision Text API gives Android developers a powerful and reliable OCR capability that works with most
Android devices.

# This is a very powerful API that can also be used for live face detection and face tracking along with bar code 
   scanning capabilities.
   
   How to use Google Mobile Vision API in Android Studio. I have given some Idea.
   
   
 1.  Go to File -> New Project. When it prompts you to select the default activity, select Empty Activity and proceed.
 
 2.  Open build.gradle in (Module:app) and add Mobile Vision dependencies like this.
 
       dependencies {
    ...
    compile 'com.google.android.gms:play-services-vision:11.0.4'
    ...
       }
 
 3. To use this library, you may need to update your installed version of Google Repository in SDK tools .Do make 
    sure your version of Google Repository is up to date. It should be at least version 26.

 4. Don’t forget to add permissions for accessing CAMERA and also meta-data for using OCR in AndroidManifest.xml 
     file like this
     
     <uses-permission android:name="android.permission.INTERNET"></uses-permission>
     <application>
      <meta-data android:name="com.google.android.gms.vision.DEPENDENCIES" android:value="ocr"/>
      </application>
      
      
      ## Screen Shot
      
      ![screenshot_androidtext](https://user-images.githubusercontent.com/24228143/39515820-d5d601a2-4e18-11e8-9113-8fcf178c88d9.jpeg)
![screenshot_intel](https://user-images.githubusercontent.com/24228143/39515823-d62acfe8-4e18-11e8-8c23-3f8495806a5d.jpeg)

   
   
