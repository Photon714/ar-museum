# AR Museum: build the APK in the cloud (no Unity)

1. github.com > sign in (free) > **New repository** > name it `ar-museum` > Create.
2. In the new repo: **Add file > Upload files**. Drag in **everything inside this folder**
   (`www`, `.github`, `package.json`, `capacitor.config.json`, ...), not the zip itself.
   Make sure the `.github` folder came along, then click **Commit changes**.
3. Open the **Actions** tab. A run called "Build APK" starts by itself (about 5-10 min).
   If it doesn't, click Build APK > **Run workflow**.
4. When it shows a green tick, open the run and download **ARMuseum-apk** at the bottom.
   Unzip it to get `app-debug.apk`.
5. Send the APK to your phone, install it (allow "install unknown apps"), allow the camera.
6. Open `hiro-marker.png` on your laptop screen (full screen, bright) or print it. Point the phone at it.

If the run fails (red cross), open it, copy the red error text and send it to me.
