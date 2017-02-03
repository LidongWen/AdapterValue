# AdapterValue
一些 xml 适配值,这边适配一些本公司特制机型。 主要值：sp 、 dp ;


## 引用
```groovy
// 项目引用
dependencies {
    compile 'com.github.LidongWen:AdapterValue:1.0.0'
}

// 根目录下引用
buildscript {
    repositories {
        jcenter()
    }
    dependencies {
        classpath 'com.android.tools.build:gradle:2.1.0'
        classpath 'com.github.dcendents:android-maven-gradle-plugin:1.5'
    }
}

allprojects {
    repositories {
        jcenter()
        maven { url "https://www.jitpack.io" }
    }
}
```
## 用法示例
```groovy
 android:layout_height="@dimen/value_20"

android:textSize="@dimen/size_zt_4"
 ```
