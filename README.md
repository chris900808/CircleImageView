# CircleImageView
Demo picture

![](https://github.com/zhouyongxyz/CircleImageView/raw/master/circleimageview_demo.png)

CircleImageView
```xml
<com.example.jerry.libcircleimageview.CircleImageView
        android:id="@+id/image"
        android:layout_width="240dp"
        android:layout_height="240dp"
        android:layout_centerInParent="true"
        android:src="@drawable/album_jay"
        app:civ_border_width="2dp"
        app:civ_border_color="#ff000000"
        android:layout_gravity="center_horizontal" />
 ```       

build.gradle 
```xml
dependencies {
    compile 'com.github.zhouyongxyz:CircleImageView:1.0.1'
}
```
```xml
repositories {
    maven {
        url "https://jitpack.io"
    }
}
```
