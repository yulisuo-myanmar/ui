# ui

## MMProgressBar

实现下面形式的进度条



## 引入依赖

project build.gradle

```
// Top-level build file where you can add configuration options common to all sub-projects/modules.
buildscript {
    repositories {
        google()
        jcenter()
        // 添加maven地址
        maven { url "https://github.com/yulisuo-myanmar/ui/raw/master" }
    }
    dependencies {
        classpath "com.android.tools.build:gradle:4.1.3"

        // NOTE: Do not place your application dependencies here; they belong
        // in the individual module build.gradle files
    }
}

allprojects {
    repositories {
        google()
        jcenter()
        // 添加maven地址
        maven { url "https://github.com/yulisuo-myanmar/ui/raw/master" }
    }
}


```

module build.gradle引入依赖

```
implementation 'com.myanmar.ui:ui:1.2'

```
