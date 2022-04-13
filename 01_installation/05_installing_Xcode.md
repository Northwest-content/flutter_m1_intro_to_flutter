1. Open **App Store**.

2. Type **Xcode**, then click **Install**.

![screenshot](https://lh5.googleusercontent.com/Ig84xfBPwMJ7rTRcEdd-pfn4m2JvdI6tgogSTjsdnpGLhC4PdCUQY0K5CL9zIOhXEexyZALLmbLw-GzqtZiDgbDkKlGmtRXMM7WdOcyCD705GAPhYJSv9gUdMT5bIaLSh_Vg2I3U)

3. Open **Xcode**, then close it.

4. Run the following command, it'll ask for your device's password.

   ```shell
   sudo xcode-select --switch /Applications/Xcode.app/Contents/Developer
   ```

5. Run the following command inside the **Terminal**

   ```shell
   sudo xcodebuild -runFirstLaunch
   ```

6. Run the following command, then click space until the end, type **agree**, and press **Enter**.

   ```shell
   sudo xcodebuild -license
   ```

7. Run the following command, then make sure that the simulator appears. After it appears you can close it.

   ```shell
   open -a Simulator
   ```

![screenshot](https://lh4.googleusercontent.com/xXqpDPzLGBBIoVuhg3vCBiL9pLRtXr-LvF9qFzBXHdhkSghewM62daxhN-IQ-qROppGY0RaIehGHTb57btdts_iNrWy0WEsj8QlQ3fw9drisfzpKGhR3QV8T5hBkQlg9MirSXFgH)

8.  Run the following command inside the **Terminal**.

    ```shell
    sudo gem install cocoapods
    ```
