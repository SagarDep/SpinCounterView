# SpinCounterView
[![Download](https://img.shields.io/badge/download-App-blue.svg)](https://raw.githubusercontent.com/jenly1314/SpinCounterView/master/app/app-release.apk)
[![](https://jitpack.io/v/jenly1314/SpinCounterView.svg)](https://jitpack.io/#jenly1314/SpinCounterView)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/mit-license.php)
[![Blog](https://img.shields.io/badge/blog-Jenly-9933CC.svg)](http://blog.csdn.net/jenly121)

SpinCounterView for Android 一个类似码表变化的旋转计数器动画控件。

## Gif 展示
![Image](GIF.gif)

## 引入

### Maven：
```maven
<dependency>
  <groupId>com.king.view</groupId>
  <artifactId>spincounterview</artifactId>
  <version>1.1.1</version>
  <type>pom</type>
</dependency>
```
### Gradle:
```gradle
compile 'com.king.view:spincounterview:1.1.1'
```
### Lvy:
```lvy
<dependency org='com.king.view' name='spincounterview' rev='1.1.1'>
  <artifact name='$AID' ext='pom'></artifact>
</dependency>
```
###### 如果Gradle出现compile失败的情况，可以在Project的build.gradle里面添加如下：（也可以使用上面的GitPack来complie）
```gradle
allprojects {
    repositories {
        //...
        maven { url 'https://dl.bintray.com/jenly/maven' }
    }
}
```

## 示例

布局
```Xml
    <com.king.view.spincounterview.SpinCounterView
        android:id="@+id/scv"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        app:max="100"
        app:maxValue="1000"/>
```

核心动画代码
```Java
spinCounterView.showAnimation(80);
```

## 关于我
   Name: Jenly

   Email: jenly1314@gmail.com / jenly1314@vip.qq.com

   CSDN: http://blog.csdn.net/jenly121

   Github: https://github.com/jenly1314

   微信公众号:

   ![公众号](http://olambmg9j.bkt.clouddn.com/jenly666.jpg)

   加入QQ群: [20867961](http://shang.qq.com/wpa/qunwpa?idkey=8fcc6a2f88552ea44b1411582c94fd124f7bb3ec227e2a400dbbfaad3dc2f5ad)


