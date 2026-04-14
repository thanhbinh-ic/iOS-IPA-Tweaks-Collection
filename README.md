# [ ϟ⚡ϟ ] iOS IPA Tweaks Collection

A curated collection of iOS tweaks (.dylib, .deb) designed for injection into IPA files. This repository serves as a centralized hub for users who want to enhance or customize their iOS applications without needing a full Jailbreak.

---

## [ ⊶⊷⊶ ] Tweak Repository List

Here is a detailed list of all tweaks available in this repository, categorized by their functionality.

| Tweak Name | Description |
| :--- | :--- |
| **[ 🔓 Free iAP ]** | |
| `SatellaJailed(prettynewversion).dylib` | Advanced iAP unlock tool for non-jailbroken devices |
| `SatellaJailed.dylib` | Standard iAP unlock tool for non-jailbroken devices |
| `iAPCracker.deb` | Classic tweak to "unlock" in-app/game purchases |
| **[ ⚙️ Modding & Utilities ]** | |
| `MaxCheat_v2.7.57.deb` | Memory scanner & game editor (cheat engine style) |
| `com.ios.libtool_...arm.deb` | Find hidden/offset values in Unity-based games |
| `com.test.h5gg_...arm.deb` | H5GG mod engine with JS APIs & HTML5 UI |
| `hideiconH5gg-iGameGod.dylib` | Hides floating icons for H5GG & iGameGod from screen |
| `iOS Gods Popup Gone.dylib` | Removes annoying login/social pop-ups when opening games |
| `iOSGods.com.DA2...arm.deb` | Specific game mod binary from the iOSGods source |
| `xyz.cypwn.autorc...arm64.deb`| Automation scripts and configs related to CyPwn |
| `zxautorc.deb` | Automation scripts and configs related to CyPwn |
| **[ 🛡️ Privacy & Clean UI ]** | |
| `DisableNetwork.dylib` | Completely blocks the specific app's network connection |
| `NetworkBlocker(adblocker).dylib` | Blocks connections to known ad and tracking servers |
| `StopReviews.dylib` | Disables the "Rate this app on the App Store" pop-ups |
| **[ 🛠️ System Fixes & Bypasses ]** | |
| `ExtensionFix.dylib` | Fixes bugs related to app extensions (widgets/shares) after modding |
| `FilePickerFix.dylib` | Fixes issues where the document/file picker fails to open |
| `Sideloadbypass1.org.dylib` | Bypasses advanced application sideload detection |
| `blatantsPatch.dylib` | Fixes crashes for VPN apps, widgets, and various other reasons |
| **[ 📺 YouTube Enhancements ]** | |
| `YTLitePlus.dylib` | Comprehensive mod: Ad-blocking, background playback, and more |
| `YouPiP.dylib` | Force-activates the native Picture-in-Picture feature |
| `YouTubeDislikesReturn.dylib` | Brings back the dislike counter on the YouTube interface |
| `iSponsorBlock.dylib` | Automatically skips sponsored segments inside videos |
| **[ 🩹 Crash Fixes (IPA) ]** | |
| `alternativeIPAfix.dylib` | Alternative patch to fix sideloaded app crashing on launch |
| `fixipa1.dylib` | Generic fix for sideloaded app stability |
| `fixipa2.dylib` | Generic fix for sideloaded app stability (v2) |

---

## [ ⊶⊷⊶ ] Prerequisites

To use these tweaks, you will typically need:

1. **Decrypted IPA:** A "cracked" or decrypted version of the target app (encrypted App Store IPAs will not work).
2. **Injection & Sideloading Tools:**
    * **Windows/macOS:**
        * [Sideloadly](https://sideloadly.io/) (Recommended for injection)
        * [AltStore](https://altstore.io/) (Classic sideloading)
        * [SideStore](https://sidestore.io/) (Sideload via Wi-Fi without a PC)
        * [Azule](https://github.com/Al4ise/Azule) (CLI tool for macOS/Linux)
    * **On-Device:**
        * [ESign](https://esign.yyyue.xyz/) (Powerful in-app injection)
        * [LiveContainer](https://github.com/khanhduytran0/LiveContainer) (Run IPAs without installation)
        * [Scarlet](https://usescarlet.com/)
        * [Bullfrog Assistant](https://ios222.com/)
3. **Signing Certificate:** A valid developer certificate (.p12) and provisioning profile, or a standard Apple ID for 7-day sideloading.

---

## [ ⊶⊷⊶ ] Injection Procedures

### 1. Sideloadly Method (PC Required)
1. **Download** the desired `.dylib` or `.deb` file.
2. **Open Sideloadly** on your computer and connect your iOS device.
3. **Drag and drop** your **Decrypted IPA** into the Sideloadly window.
4. Navigate to the **Advanced Options** tab.
5. In the **Tweaks** section, click the **+** button and select the tweak file you downloaded.
6. Enter your **Apple ID** and click **Start**. The app will be injected, signed, and installed automatically.

### 2. ESign Method (On-Device)
1. **Import** both your **Decrypted IPA** and the **Tweak file** into the ESign app library.
2. Tap on the IPA file and select **"Signature"**.
3. In the signature settings, look for **"More Settings"** or **"Add Library"**.
4. Select the `.dylib` or `.deb` file you want to inject.
5. Tap **"Signature"** to process.

> **Pro Tip:** If the app crashes on launch, ensure you have included necessary dependencies like `CydiaSubstrate.framework` or `Substitute.framework` if the tweak requires them.

---

## [ ⊶⊷⊶ ] Disclaimer

* **Educational Purpose:** This project is for educational and research purposes only.
* **Account Safety:** Use these tweaks at your own risk. I am not responsible for banned accounts, data loss, or any issues arising from the use of these files.
* **Ownership:** All rights to the original applications belong to their respective developers.

---

## [ ⊶⊷⊶ ] Contributing

Contributions are welcome! If you have a high-quality tweak or a bug fix, please:

1. **Fork** the project.
2. Create your **Feature Branch** (`git checkout -b feature/NewTweak`).
3. **Commit** your changes (`git commit -m 'Add NewTweak'`).
4. **Push** to the Branch (`git push origin feature/NewTweak`).
5. Open a **Pull Request**.

---
