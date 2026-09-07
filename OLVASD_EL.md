# Forint időgép — Android apk generálása GitHubbal

Ez a mappa egy teljes, kész Android projekt. Neked nincs más dolgod, mint feltölteni egy GitHub repóba — a build (fordítás) automatikusan lefut a GitHub szerverén, és a végén letölthető apk fájlt kapsz.

## Lépések

1. Regisztrálj (ha még nincs) egy ingyenes fiókot: https://github.com/join

2. Jelentkezz be, majd a jobb felső "+" ikonnal hozz létre egy **új repository-t** (New repository). Neve legyen pl. `forint-idogep`. Legyen "Public". Ne pipáld be a "README" létrehozását. Kattints "Create repository".

3. Az új, üres repo oldalán keresd meg az **"uploading an existing file"** linket (vagy: Add file → Upload files).

4. Tömörítsd ki ezt a ZIP-et a saját géped valamelyik mappájába, majd az egész **ForintIdogepApp** mappa TARTALMÁT (ne magát a mappát, hanem ami benne van: `app`, `.github`, `build.gradle`, `settings.gradle`) húzd rá a feltöltő ablakra. A GitHub megtartja a mappaszerkezetet.

5. Lent kattints "Commit changes".

6. Menj a repo tetején az **"Actions"** fülre. Látnod kell egy "Build APK" nevű futást, ami automatikusan elindult (sárga = fut, zöld pipa = kész, kb. 3-5 perc).

7. Ha zöld, kattints rá a futásra, görgess le az **"Artifacts"** részhez, és töltsd le a `forint-idogep-apk` nevű csomagot (egy .zip, amiben az `app-debug.apk` van).

8. Ezt az apk-t küldd át a telefonodra (email, Drive, bármi), és koppints rá — a telefon fel fogja ajánlani a telepítést (esetleg egyszer engedélyezni kell "ismeretlen forrásból telepítés"-t, ezt a telefon magától kéri egy gombbal).

Kész — utána ugyanúgy ott lesz az ikon a telefonodon, mint bármelyik más telepített appod.
