# [ ϟ⚡ϟ ] iOS IPA Tweaks Collection

A curated collection of iOS tweaks (.dylib, .deb) designed for injection into IPA files. This repository serves as a centralized hub for users who want to enhance or customize their iOS applications without needing a full Jailbreak.

---

## [ >>> ] Features
* **Organized Library:** Categorized tweaks for Social Media, Gaming, and System utilities.
* **Compatibility Focused:** Regularly updated binaries to ensure they work with the latest app versions.
* **Beginner Friendly:** Step-by-step guides for various sideloading and injection methods.
* **Lightweight:** Focuses on optimized tweaks that don't cause significant battery drain or app instability.

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

## [ ◈◈◈ ] Injection Procedures

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

## [ !!! ] Disclaimer

* **Educational Purpose:** This project is for educational and research purposes only.
* **Account Safety:** Use these tweaks at your own risk. I am not responsible for banned accounts, data loss, or any issues arising from the use of these files.
* **Ownership:** All rights to the original applications belong to their respective developers.

---

## [ <=> ] Contributing

Contributions are welcome! If you have a high-quality tweak or a bug fix, please:

1. **Fork** the project.
2. Create your **Feature Branch** (`git checkout -b feature/NewTweak`).
3. **Commit** your changes (`git commit -m 'Add NewTweak'`).
4. **Push** to the Branch (`git push origin feature/NewTweak`).
5. Open a **Pull Request**.

---
