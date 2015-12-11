# android-toolbar-example

* * *

### Set style no action bar


```xml
<style name="AppTheme" parent="Theme.AppCompat.Light.NoActionBar">
    <item name="colorPrimary">@color/colorPrimary</item>
    <item name="colorPrimaryDark">@color/colorPrimaryDark</item>
    <item name="colorAccent">@color/colorAccent</item>
</style>
```

### Add toolbar.xml to layouts

```xml
<android.support.v7.widget.Toolbar
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:background="#3d3dff"
    android:orientation="vertical">
</android.support.v7.widget.Toolbar>
```

### Include toolbar.xml to activity_main.xml

```xml
<include
    android:id="@+id/toolbar"
    layout="@layout/toolbar"/>
```

