# Android-RTSP-Video
Android Audio and Video Development


1、新建空工程

2、在app的build.gradle中添加依赖：

    android{
        ...
        minSdkVersion 改成 17
    }
    
    dependencies {
            ...
        implementation 'org.videolan.android:libvlc-all:3.1.12'
    }

3、将javaActivity.java和其xml拷贝到新工程相应位置，在AndroidManifest.xml中添加：

    <activity android:name=".JavaActivity"></activity>

4、运行即可。
