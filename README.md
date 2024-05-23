# H5_Builder 将H5网页一键编译成 Android APK 。
### 使用方法
1.Fork本仓库，修改project-to-build中的地址为你仓库中本项目的地址。

2.将 `app/java/com.example.test/MainActivity.java` 里面第137行的 `url` 改成你要打包的网页地址。

3.Actions中左侧选择andriod_build后，点击右侧Run Workflow开始编译。

4.等待编译完成后，重新进入Actions页面，编译好的APK在下面的Artifacts中。

5.自行下载签名。
