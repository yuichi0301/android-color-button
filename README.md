android-color-button
====================

Usage
-----

### via xml (sample)

```xml
<me.yuichi0301.widget.ColorButton
    android:layout_marginTop="10dp"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:text="@string/hello_world"
    android:textColor="#fff"
    custom:backgroundColor="#f00" />
```

### via code (sample)

```java
ColorButton cbutton = new ColorButton(getApplicationContext());
cbutton.setStyle(7, Color.GREEN);
```