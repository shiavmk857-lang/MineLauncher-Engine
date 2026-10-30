# Mine Launcher (Pojav-based)

Minecraft: Java Edition launcher for Android, built on the **PojavLauncher** engine (LGPL-3.0).

## Kya badla gaya
- App name, applicationId (`com.minelauncher.app`), launcher icons, signing keys.
- Java namespace `net.kdt.pojavlaunch` jaan-boojhkar nahi badla, kyunki native (JNI) code isi naam par nirbhar hai.
- Engine (JNI, LWJGL, GL4ES, Forge installer, offline account, skin, file manager) jyon ka tyon.

## Build (GitHub Actions)
1. Repo par push karo, Actions tab -> "Android CI" chalao.
2. Workflow JRE 8/17/21 aur LTW khud download karta hai.
3. APK `app-debug` artifact mein milega.
Google Play (.aab) ke liye apni keystore banao aur `signingConfigs` mein jodo. Keystore ya password kabhi repo mein mat daalo.

## Credits / License
Yeh project PojavLauncher (PojavLauncherTeam) par aadharit hai, jo LGPL-3.0 mein hai (`LICENSE` dekho). PojavLauncher discontinued hai; uska successor Amethyst-Android hai. Pojav ke copyright notices aur credit banaye rakho aur apna modified source public rakho.
Mine Launcher, Mojang ya Microsoft se jura nahi hai. "Minecraft" Mojang ka trademark hai.

## design_reference/
Naye UI ka prototype (HTML) aur preview. Yeh abhi sirf design guide hai, native screens mein banana baaki hai.
