# FlatButton

Reason
===================

最近专注于Material Design，觉得默认的按钮色彩不够鲜明，在寻找一些替代的方案，Flat Ui 就是选择之一。

https://github.com/hoang8f/android-flat-button
这个库在 android 5.0 下的表现并不好。

https://github.com/eluleci/FlatUI
这个库对我来说又太大，我只关注 button。

好吧，还有些其他问题。

1. 在 disabled 状态下，按钮还是可点击的，我修正了这个问题。

2. 使用自定义主题需要配置4种颜色，这很麻烦。

3. 因为需要配置4种颜色，无法随着 material 主题的改变而自动改变颜色。

所有源码来自：https://github.com/eluleci/FlatUI

Example
-----------
![github](https://github.com/Ivolian/FlatButton/blob/master/simple.gif "github")

## Usage

```xml

    <com.ivo.flatbutton.FlatButton
        android:text="确认"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:enabled="false"
        flatui:fl_textAppearance="fl_none"
        flatui:fl_blockButtonEffectHeight="3dp"
        flatui:fl_touchEffect="fl_ease"
        flatui:fl_mainColor="@android:color/holo_blue_light"
        android:layout_marginTop="5dp" />

```
