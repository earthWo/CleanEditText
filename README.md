# CleanEditText

自带删除功能的EditText

### 效果图：

![](http://7xjrms.com1.z0.glb.clouddn.com/SM-G9500_20171011105519_1.gif)



### 接入方式：

Gradle:

```
compile 'whitelife.win.cleanedittextlibrary:cleanedittextlibrary:1.0'
```

maven:

```
<dependency>
  <groupId>whitelife.win.cleanedittextlibrary</groupId>
  <artifactId>cleanedittextlibrary</artifactId>
  <version>1.0</version>
  <type>pom</type>
</dependency>
```

### 使用方式：

```
 <whitelife.win.cleanedittextlibrary.CleanEditText
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:textColor="@color/colorPrimary"
        app:focusIcon="@drawable/user_focus"//左边icon有焦点时的图片
        app:cursor="@drawable/cursor" //光标图片
        app:icon="@drawable/user" //左边icon的图片
        android:gravity="center_vertical"
        app:deleteIcon="@drawable/delete"//右边删除icon的图片
        app:focusTextColor="#aa44cc"//有焦点时文字的颜色
        app:iconWidth="20dp"//左边icon尺寸
        app:iconHeight="20dp"
        app:dividerMarginLeft="10dp"//分割线的左右距
        app:dividerMarginRight="10dp"
        app:deleteIconWidth="20dp"//右边删除icon的尺寸
        app:deleteIconHeight="20dp"
        android:drawablePadding="10dp"
        app:dividerColor="@color/colorPrimaryDark"//分割线颜色
        app:focusDividerColor="#009988"//分割线有焦点时的颜色
        app:dividerBonds="3dp" />//分割线的厚度
```



