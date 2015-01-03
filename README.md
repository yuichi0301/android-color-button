android-color-button
====================

Using Maven
-----

<p>ColorButton Library is pushed to <a href="http://search.maven.org/#search%7Cga%7C1%7Ccbutton">Maven Central</a>, so you just need to add the following dependency to your <code>build.gradle</code>.</p>

<pre><code>dependencies {
    compile 'me.yuichi0301:cbutton:1.0.6'
}
</code></pre>

<h3>

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