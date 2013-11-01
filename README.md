AndroidBButton
==============

Bootstrap 3.0 style buttons and Font Awesome icons

#Current Capabilities
* BButton
 ..* Basic button using the bootstrap 3.0 style e.g. warning, default, or info.
 ..* Rounded or square buttons.
 ..* Buttons can be disabled.
 ..* Add a font awesome icon either to the right, left, or icon only using the font awesome 4.0 cheat sheet e.g. fa-heart.


#Future Updates




#BButton

 ```xml
 xmlns:bbutton="http://schemas.android.com/apk/res-auto"
  ```

 ```xml
<com.beardedhen.bbutton.BButton
  android:layout_width="wrap_content"
  android:layout_height="wrap_content"
  android:text="Default"
/>
 ```

 ```xml
bbutton:type="default"
  ```
  
  ```xml
bbutton:icon_left="fa-heart"
  ```
  
  ```xml
bbutton:icon_right="fa-android"
  ```
  
  ```xml
bbutton:roundedCorners="true"
  ```
  
  ```xml
android:enabled="false"
  ```
  
