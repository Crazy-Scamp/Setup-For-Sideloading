
## WHAT ARE WE DOING?
- ENABLING DEVELOPER MODE
- INSTALLING ADB DRIVER

---

# DEVELOPER MODE SETUP

A step-by-step guide to enabling Developer Mode on your Meta Quest headset, including account setup, verification, and optional configuration for sideloading apps or development work.

---

## 📋 Overview
To enable Developer Mode, you must first register as a Meta developer and verify your account.
Once verified, you can unlock the mode through the **Meta Horizon** mobile app. 
This mode unlocks advanced features such as installing third-party apps, testing custom builds, and developing your own VR content.

---

## 🚀 Step 1: Create a Meta Developer Account
1. Open a browser on your computer or smartphone and go to the [Meta Horizon Developer Center](https://developer.oculus.com/).
2. Log in using the **same Meta account** that is linked to your Meta Quest headset.
3. Navigate to **My Apps** (or click your profile icon in the top-right corner) and select **Create New Organization**.
4. Enter a unique name for your organization, accept the terms of service, and complete any required developer agreements.

---

## ✅ Step 2: Verify Your Account
Meta requires all developer accounts to be verified for security and compliance purposes.
1. Follow the on-screen prompts in the Meta Horizon Developer Dashboard to begin verification.
2. Choose one of the accepted verification methods:
   - **Phone number**: Add a valid number for two-factor SMS authentication.
   - **Credit card**: Used only for identity verification — no charges are made unless you publish paid applications.
3. Complete the process to confirm your account is verified.

---

## ⚙️ Step 3: Enable Developer Mode in the Mobile App
1. Make sure your Meta Quest headset is turned on and paired/connected to your phone via the Meta Horizon app.
2. Open the **Meta Horizon app** on your mobile device.
3. Tap the **Devices / Headset** icon in the toolbar.
4. Select your paired headset from the list of devices.
5. Tap **Headset Settings** to open advanced configuration options.
6. Locate **Developer Mode** and toggle the switch to **ON**.
7. **Restart your Meta Quest headset** to apply the changes.

---

## 🔌 Step 4: Allow USB Debugging
1. Turn on your Meta Quest and plug it into your computer using a **data-capable USB‑C cable** (charging-only cables will not work).
2. Put on the headset — you will see a system prompt asking to **Allow USB Debugging**.
3. Select **Always allow from this computer** to approve future connections without repeating this step.

---
---

## ⁉️ Troubleshooting
- **Developer Mode option missing**: Ensure your account is fully verified and you have created an organization in the Developer Center.
- **Headset not appearing in app**: Confirm both devices are on the same Wi‑Fi network and Bluetooth is enabled.
- **USB connection not working**: Use a high-quality data cable, not just a charging cable.

---
---

# ⏯️ DOWNLOAD THE DRIVERS

1. **Download Required Files**
   - **Official Oculus ADB Drivers**: [oculus-adb-driver-2.0.zip](https://developers.meta.com/horizon/downloads/package/oculus-adb-drivers/)  
     → Extract the ZIP file to an easy‑to‑find folder (e.g. `Downloads\oculus-adb-driver-2.0`).

---

## 🖥 Method 1: Quick Install (Recommended)
1. Open the extracted driver folder.
2. Right‑click **`android_winusb.inf`** → Select **Install**.
3. Click **Yes / Allow** on all security prompts.
4. Wait for the message: *“Operation completed successfully”*.
5. **Restart your PC** to apply changes.

---

## ⚙️ Method 2: Manual Install (If Method 1 Fails)
1. Keep your headset connected and awake.
2. Right‑click the Start menu → Open **Device Manager**.
3. Look under:
   - `Other devices`
   - `Portable Devices`
   - `Universal Serial Bus devices`
   - You will see **Meta Quest / Oculus / Unknown Device / ADB Interface** (marked with a yellow warning triangle ⚠️).
4. Right‑click that device → **Update driver**.
5. Choose **Browse my computer for drivers**.
6. Click **Browse** → Select the folder where you extracted the drivers → Check **Include subfolders** → Click **Next**.
7. If prompted, select **Oculus Composite ADB Interface** or **Android ADB Interface** → Proceed with installation.
8. Accept any security warnings — these are safe, official drivers.

✅ Success: The device will now appear under `Android Device` or `Universal Serial Bus devices` as **Oculus Composite ADB Interface**.

---

## 🛠️ Method 3: “Have Disk” Install (Windows 11 / Driver Issues)
1. In **Device Manager**, right‑click the unrecognized device → **Update driver** → **Let me pick from a list of available drivers on my computer**.
2. Click **Have Disk…** → **Browse** → Navigate to your extracted driver folder and select **`android_winusb.inf`** → Click **OK**.
3. Select the matching driver → Click **Next** → Complete installation.

---

## ✅ YOUR DEVICE SHOULD NOW BE READY FOR SIDELOADING

---
