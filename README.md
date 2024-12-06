# Completely Free Privacy Guide
- Hello 🤭. In this guide, you will be informed about **privacy** while using your **computer** or **mobile devices**.
- Nowadays, many companies such as **Microsoft** and **Google** collect **too much** personal information, so you might want to have more privacy while using your devices.
- For **100%** privacy, unfortunately you should either use one of your devices for hosting or pay for certain services.
  - What I mean by using a device for hosting can be using your own **e-mail domain** instead of using **@gmail.com, @outlook.com etc.** so your e-mails will be more secure and private or using your own **unlimited and encrypted cloud storage etc.** This is a free way since you're hosting everything locally but you have to keep your device running all the time and not everyone has additional devices for hosting.
  - If you don't want to do local hosting, there are services that deliver **100% unlimited and private features** but they are paid.
- However, I will show you **completely free** ways for privacy. So, let's begin!
## For Computers
- For privacy on computers, I suggest you to use **Linux**. Linux distributions **respect your privacy** and they are **free**. Using computer for **daily use** is 100% possible on Linux, gaming is also possible (not 100%). So, if your concern about switching to Linux is it being not good enough for gaming, you can check my [Linux Gaming Guide](https://github.com/cutiepenguins/Linux-Gaming-Guide) to feel relieved.
- However, you might not want to get out of your comfort zone. In this case:
  - If you're using **MacOS**, you can apply basic steps like [explained in this article](https://www.practicalmoneyskills.com/en/resources/data_privacy/device-privacy-tips/How-Protect-Privacy-Mac.html).
  - If you're using **Windows**, you can use [Chris Titus' Windows Utility](https://github.com/ChrisTitusTech/winutil), the utility also has cool features that increase performance.
## For Mobile Devices
- If you're using a device that has **iOS**, you can [follow this guide](https://github.com/iPrivacyGuides/iOS-Privacy-Guide)
- If you're using a device that has **Android**, I definitely suggest you to install a **custom ROM**. However if you don't want to install a custom ROM, you can [follow this guide](https://veepn.com/blog/10-android-privacy-settings/) basically and skip this step. If you will install a custom ROM, keep reading the step.
  - There are different kinds of custom roms. Those are:
    - `AOSP` - **Android Open Source Project :** This is the barebone android that Google shares the source code of. Those ROMs are generally lightweight. Some AOSP based ROM examples are:
      - `LineageOS`
      - `CrDroid`
      - `ArrowOS`
    - `CAF` - **Code Aurora Forum :** CAF ROMs are also **AOSP based** but they have specific optimizations for **Qualcomm devices (Snapdragon CPUs)** that deliver **smoothness, better performance, better RAM management** and **better battery life**. Some CAF based ROM examples are:
      - `Paranoid Android`
      - `ReloadedOS`
    - My personal suggestion is **CrDroid** since it is **not too barebone** that needs configuration and it has **highly customizable tools** and it has **some of the CAF optimizations**. Also from my personal experiences, my **Xiaomi Redmi Note 8** runs perfectly in terms of smooth performance and good battery life **only on CrDroid**. Also, CrDroid ROM **is maintained for lots of devices**. Assuming you installed CrDroid, let's continue.
    - CrDroid doesn't have **Google Play Services** installed which means you are **unable** to use **location services, google play applications and push notifications**. That's why, I suggest you to use **MicroG**

### MicroG
- MicroG is an **open source re-implementation of Google services and libraries** that respects your privacy and all you have to do is **installing .apk files from the** [website](https://microg.org/download.html). It is so easy! Also, **Huawei** devices can also use MicroG! However, if you want to use MicroG on **another custom ROM**, you should take a look at [this article](https://github.com/microg/GmsCore/wiki/Signature-Spoofing), otherwise, MicroG **won't work** on your device!!!
  - After installing MicroG, you should change **microG Settings app's** battery optimization to `Unrestricted`.
    - Next, simply log in your Google account inside the app and open your system's **Settings** app.
      - After opening settings, go to `Passwords, passkeys & autofill` and click on your google account. Next, go to `Account preferences` and enable the two options you see.
    - Now go back to **microG Settings app** and enable **Google device registration, Cloud Messaging and Google SafetyNet**.
      - For Location modules, you need to install `Nominatim` from **F-Droid**. This is mandatory to be able to use map.
      - For the network-based geolocation module, I suggest you to install `Apple UnifiedNlp Backend UnifiedNlp location provider (Apple Wi-Fi)` from **F-Droid**. After installing, go back to **microG Settings app** and go to `Location modules`, next, enable `Nominatim` and `Apple Wi-Fi`.
- The last step after configuring MicroG is installing a **store app**. My suggestion is [Aurora Store](https://auroraoss.com/), it's an **open source Play Store alternative** and it **doesn't send any telemetry to Google**.
- After these steps, that's all you could do for an android experience with privacy.
## Other Methods 
Now we can talk about easier steps.
- **Using A Private DNS:** My suggestion is [NextDNS](https://nextdns.io/)
- **Using A VPN:** while it doesn't hide anything from your internet provider, it can keep you private from websites. My suggestion is using [ProtonVPN](https://protonvpn.com/), it is **open source, free and really fast**.
- **Using An E-Mail Client:**. My suggestion is using [Thunderbird](https://www.thunderbird.net/en-US/).
- **Using A 2FA (Two Factor Authenticator)** My suggestion is using [Ente Auth](https://ente.io/auth/), it is **open source and free**.
- **Encrypting Your Personal Files In Your Google Drive:** I assume you're using Google Drive because it provides the most free storage. We can keep your files in Google Drive private. All you have to do are **archiving** and **encrypting** your folders using your archiver app on your computer and uploading them to Google Drive.
### Some Alternatives
- **Google Search Engine** `-` **DuckDuckGo**
- **Google Chrome** `-` **Firefox or any Firefox based browser. My suggestion is using Zen Browser**
- **Google Play Store** `-` **Aurora Store and F-Droid**
- **Gboard Keyboard** `-` **AOSP Keyboard**
- **Google Photos** `-` **Ente Photos**
- **Google Maps** `-` **Unfortunately, I don't think there is a better alternative. Sorry** 🥺
- **Microsoft Office / WPS Office** `-` **OnlyOffice**
- **YouTube Android App** `-` **YouTube ReVanced**
- **Discord Desktop App** `-` **Vesktop**
# Conclusion
This was my completely free privacy guide. I hope it was useful for you. Have a nice day! 🐧
