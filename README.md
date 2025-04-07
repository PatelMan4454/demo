# 📲 AdMob Ads Integration in Unity

This guide explains how to integrate **Banner Ads**, **Interstitial Ads**, and **Rewarded Ads** using Google AdMob in your Unity project.

---

## 🔗 Step 1: Download and Import AdMob Plugin

1. Open the official setup guide: [AdMob Unity Quick Start](https://developers.google.com/admob/unity/quick-start)  
2. Download the latest **Google Mobile Ads Unity plugin** and import it into your Unity project.
3. After importing:
   - **Close and reopen** your Unity project.
   - Then go to:  
     `Assets → External Dependency Manager → Android Resolver → Force Resolve`

---

## 📦 Step 2: Banner Ad Setup

1. Create an **empty GameObject** in your scene and name it `Banner`.
2. Create a new **C# script** named `Banner`.
3. Paste this code in the script:  
   🔗 [BannerAd Script](https://pastebin.com/raw/FX8YSTjP)
4. Attach the `Banner` script to the `Banner` GameObject.
5. Press **Play** — the banner ad will appear.

---

## 🎬 Step 3: Interstitial Ad Setup

1. Create an **empty GameObject** named `Interstitial`.
2. Create a new **C# script** named `Interstitial`.
3. Paste this code in the script:  
   🔗 [InterstitialAd Script](https://pastebin.com/raw/Q8dVi6hq)
4. Attach the `Interstitial` script to the `Interstitial` GameObject.
5. Press **Play** — the interstitial ad will appear.

---

## 🎁 Step 4: Rewarded Ad Setup

1. Create an **empty GameObject** named `Rewarded`.
2. Create a new **C# script** named `Rewarded`.
3. Paste this code in the script:  
   🔗 [RewardedAd Script](https://pastebin.com/raw/Qy1avYJt)
4. Attach the `Rewarded` script to the `Rewarded` GameObject.
5. Press **Play** — the rewarded ad will appear.

---

## ⚙️ Step 5: Setup AdMob in Unity

1. Go to [Google AdMob](https://admob.google.com/) and create a new app.
2. Enter your app name and choose your platform (Android/iOS).
3. In the **App Settings**, copy your **App ID**.
4. In Unity:  
   `Assets → Google Mobile Ads → Settings`  
   Paste the App ID into the appropriate Android/iOS field.
5. In AdMob, create the following **Ad Units**:
   - Banner Ad
   - Interstitial Ad
   - Rewarded Ad
6. Copy each **Ad Unit ID** and paste it into the correct script:
   - ✅ **Banner Ad ID** → in `Banner` script
   - ✅ **Interstitial Ad ID** → in `Interstitial` script
   - ✅ **Rewarded Ad ID** → in `Rewarded` script

---

✅ Done! Your Unity project is now ready to serve AdMob ads.
