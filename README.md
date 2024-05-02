# ID Austria / Digitales Amt mit Root und/oder entsperrtem Bootloader nutzen

1. [Ohne Root](#ohne-root)
    1. [Schritt 1: APK downloaden/extrahieren](#schritt1-1)
        1. [Schritt 1.1: Welche Methode soll ich verwenden?](#schritt1-1-1)
        2. [Schritt 1.2: APK downloaden](#schritt1-1-2)
        3. [Schritt 1.3: APK extrahieren](#schritt1-1-3)
    2. [Schritt 2: ReVanced installieren](#schritt1-2)
    3. [Schritt 3: APK patchen](#schritt1-3)
    4. [Schritt 4: App installieren](#schritt1-4)
2. [Mit Root](#mit-root)
    1. [Schritt 1: APK downloaden](#schritt2-1)
    2. [Schritt 2: ReVanced installieren](#schritt2-2)
    3. [Schritt 3: App patchen](#schritt2-3)
3. [Fragen](#fragen)
    1. [Ist das ganze legal?](#fragen-1)
    2. [Wie kann ich mir sicher sein, dass ich mir hier keine Viren oder ähnliches einfange?](#fragen-2)
    3. [Welche Versionen werden unterstützt?](#fragen-3)
    4. [Wie sieht's mit Updates aus?](#fragen-4)
    5. [Wie kann ich überprüfen ob eine heruntergeladene APK ein Original ist und nicht mit Schadware verseucht wurde?](#fragen-5)
    6. [Die E-Ausweis App funktioniert nicht](#fragen-6)
    7. [Die FinanzOnline App funktioniert nicht](#fragen-7)

# Ohne Root

<div id="schritt1-1" />

## Schritt 1: APK downloaden/extrahieren

<div id="schritt1-1-1" />

### Schritt 1.1: Welche Methode soll ich verwenden?

Wenn du APKPure vertraust, kannst du [Methode 1](#schritt1-1-2) verwenden, solltest du absolut sicher gehen wollen, nimm [Methode 2](#schritt1-1-3).

<div id="schritt1-1-2" />

### Schritt 1.2: APK downloaden

Ihr könnt die APK über [APKPure](https://apkpure.com/digitales-amt/at.gv.oe.app/download) beziehen. Am besten gehts über [**diesen Direktlink**](https://d.apkpure.com/b/APK/at.gv.oe.app?versionCode=2024041541) (Version `3.1.1`), oder sonst über den obrigen APKPure Link (die folgenden Screenshots zeigen alle die Version `2.5.2`, der Prozess für neuere Versionen ist jedoch der gleiche):

![image](https://user-images.githubusercontent.com/58902674/216638576-c81ba4bf-dc20-4f04-a7df-b2ea59f7a0bf.png)

**ACHTUNG**: Das hier ist Werbung, die müsst ihr über das `x` in der Ecke wegklicken, dann beginnt der Download:

![image](https://user-images.githubusercontent.com/58902674/216639361-0d1cd48e-edc3-4965-99ad-2b5148fd067b.png)

<div id="schritt1-1-3" />

### Schritt 1.3: APK extrahieren

Solltet ihr extrahieren wollen, ladet ihr die App ganz normal über den [Google Play Store](https://play.google.com/store/apps/details?id=at.gv.oe.app). Danach braucht ihr noch [ML Manager](https://play.google.com/store/apps/details?id=com.javiersantos.mlmanager). Nachdem ihr beide Apps über den PlayStore bezogen habt, öffnet ihr den ML Manager.

Dort sucht ihr nun nach "Digitales Amt" und wählt "Extract":


![Screenshot_20230118-171339](https://user-images.githubusercontent.com/58902674/213244805-8d118bfc-7041-48e8-a364-b4cad5123795.png)

**Wichtig**: Nach dem Extrahieren müsst ihr die App wieder deinstallieren, sonst könnt ihr die gepatchte Version später nicht installieren.

<div id="schritt1-2" />

## Schritt 2: ReVanced installieren

Nun geht ihr auf die [Github-Seite von ReVanced](https://github.com/revanced/revanced-manager/releases) und ladet euch die neuste Version herunter:

![image](https://user-images.githubusercontent.com/58902674/213244932-7b086ac9-24e7-40ff-8339-fb2a1ff21531.png)

<div id="schritt1-3" />

## Schritt 3: APK patchen

Nachdem ihr ReVanced installiert habt, öffnet ihr es und tippt unten auf "Patcher":

![image](https://user-images.githubusercontent.com/58902674/213245035-ec9c798e-2a86-4a4c-a0d1-578823101e65.png)


Nun wählt ihr "Select an application":

![image](https://user-images.githubusercontent.com/58902674/213245105-ade7696a-0f2b-48b4-bec5-cc8eb990d0ef.png)

Danach geht ihr auf "Storage":

![image](https://user-images.githubusercontent.com/58902674/213245182-11c162fa-9cf3-4b5f-b0dc-0b385a489c45.png)


Solltet ihr die App extrahiert haben, liegt die APK unter "Android" -> "media" -> "com.javiersantos.mlmanager":

![image](https://user-images.githubusercontent.com/58902674/213245247-22bc3a72-6abd-49cd-9a49-9167b548d133.png)


Solltet ihr sie von APKPure gedownloadet haben, liegt sie unter "Download":
![image](https://user-images.githubusercontent.com/58902674/213245320-1edd693d-496a-47c1-b4d4-2f8031b40cd4.png)



Nun wählt ihr die App aus. Danach tippt ihr auf "Select patches":

![image](https://user-images.githubusercontent.com/58902674/213245393-a30539ec-3502-4f22-af2d-b4be87c9971c.png)


Dort wählt ihr dann "Remove Root Detection" und "Spoof Signature" aus:
![image](https://user-images.githubusercontent.com/58902674/213245445-27f8efb0-7508-4cc9-93b2-c007835f55e5.png)



Danach tippt ihr auf "Done". Als nächstes wählt ihr "Patch" aus:

![image](https://user-images.githubusercontent.com/58902674/213245497-1e2aaee8-ce63-46c3-9640-0e25ea48b94f.png)


<div id="schritt1-4" />

## Schritt 4: App installieren

Sobald der Vorgang abgeschlossen ist, tippt ihr auf "Install":

![image](https://user-images.githubusercontent.com/58902674/213245566-b1083d3c-6c2b-41a2-9d0c-3c19e6d19a36.png)


Eventuell werdet ihr gefragt, ob ihr zulassen wollt, dass ReVanced Apps installiert. Hier tippt ihr auf "Settings" / "Einstellungen"

![image](https://user-images.githubusercontent.com/58902674/213245621-fad3189e-61a3-4f39-9a9c-88356817e7c6.png)


Hier setzt ihr nun den Haken bei "Allow from this source" / "Aus dieser Quelle erlauben":

![image](https://user-images.githubusercontent.com/58902674/213245696-45b667ae-8ae1-4724-8d1a-00f0f3c97eb6.png)


Daraufhin solltet ihr sofort gefragt werden, ob ihr die App installieren wollt:

![image](https://user-images.githubusercontent.com/58902674/213245758-ea5fd538-5667-42f5-8127-cb45771a84fd.png)


Hier bestätigt ihr mit "Install" / "Installieren". Eventuell kann es vorkommen, dass Play Protect sich meldet. Hier besteht kein Grund zur Sorge, und ihr könnt einfach mit "Install anyway" / "Trotzdem installieren" fortfahren:

![image](https://user-images.githubusercontent.com/58902674/213245811-214349a9-e917-40d7-b2fb-777567880cf6.png)

Eventuell fragt Play Protect ein weiteres mal nach, undzwar, ob die App zum scannen eingesendet werden soll. Dies könnt ihr mit "Don't Send" / "Nicht senden" ablehnen:

![image](https://user-images.githubusercontent.com/58902674/213246446-b9dec13f-bb1f-4a17-a7a1-3304045d03c4.png)



Glückwunsch. Ihr habt nun den Root/Bootloader-Check gebypasst und könnt euch normal in der App anmelden.

# Mit Root

<div id="schritt2-1" />

## Schritt 1: APK downloaden

Installiert die App über [Google Play](https://play.google.com/store/apps/details?id=at.gv.oe.app). 

<div id="schritt2-2" />

## Schritt 2: ReVanced installieren

Nun geht ihr auf die [Github-Seite von ReVanced](https://github.com/revanced/revanced-manager/releases) und ladet euch die neuste Version herunter (im Screenshot ist Version `v0.0.52` zu sehen, möglicherweise existiert bereits eine neuere Version, hier einfach ebenfalls die `.apk` Datei herunterladen):

![image](https://user-images.githubusercontent.com/58902674/213244932-7b086ac9-24e7-40ff-8339-fb2a1ff21531.png)

<div id="schritt2-3" />

## Schritt 3: App patchen

Beim ersten Start von ReVanced werdet ihr nach Superuser-Rechten gefragt. Bestätigt mit "Grant":

![image](https://user-images.githubusercontent.com/58902674/213247378-c34ea025-3c48-44d2-941d-334448f393aa.png)

Danach werdet ihr nach Installationsberechtigungen gefragt, setzt den Haken hier bei "Allow from this source" / "Aus dieser Quelle erlauben":

![image](https://user-images.githubusercontent.com/58902674/213245696-45b667ae-8ae1-4724-8d1a-00f0f3c97eb6.png)

Nun tippt ihr unten auf "Patcher":

![image](https://user-images.githubusercontent.com/58902674/213245035-ec9c798e-2a86-4a4c-a0d1-578823101e65.png)


Nun wählt ihr "Select an application":

![image](https://user-images.githubusercontent.com/58902674/213245105-ade7696a-0f2b-48b4-bec5-cc8eb990d0ef.png)

Hier wählt ihr nun die installierte "Digitales Amt"-App aus:

![image](https://user-images.githubusercontent.com/58902674/213247958-93ac36ab-c0e7-4516-8820-d7e44fc9ad66.png)

Danach tippt ihr auf "Select patches":

![image](https://user-images.githubusercontent.com/58902674/213245393-a30539ec-3502-4f22-af2d-b4be87c9971c.png)


Dort wählt ihr dann "Remove Root Detection" und "Spoof Signature" aus:
![image](https://user-images.githubusercontent.com/58902674/213245445-27f8efb0-7508-4cc9-93b2-c007835f55e5.png)



Danach tippt ihr auf "Done". Als nächstes wählt ihr "Patch" aus:

![image](https://user-images.githubusercontent.com/58902674/213245497-1e2aaee8-ce63-46c3-9640-0e25ea48b94f.png)

Als letztes tippt ihr nun auf "Install as Root":

![image](https://user-images.githubusercontent.com/58902674/213248596-436e7f73-9ef6-41b1-adf9-0f4fa1237ca7.png)


Glückwunsch, die bestehende Installation wurde nun mit der gepatchten Version überschrieben.


# Fragen

<div id="fragen-1" />

## Ist das ganze legal?

Ja, hier wird nur lokal ein Patch auf die bestehende App angewandt.

<div id="fragen-2" />

## Wie kann ich mir sicher sein, dass ich mir hier keine Viren oder ähnliches einfange?

[ReVanced](https://github.com/revanced) ist komplett quelloffen. Das heißt, dass jeder den Quellcode auf Schadware untersuchen kann. Das macht es sehr unwahrscheinlich, dass die Entwickler Schadware mitliefern. Der konkrete Quellcodes des Patches, den ReVanced installiert, kann [hier](https://github.com/revanced/revanced-patches/tree/main/src/main/kotlin/app/revanced/patches/idaustria/detection) eingesehen werden.

<div id="fragen-3" />

## Welche Versionen werden unterstützt?

Aktuell wird Version `3.1.1` unterstützt. Zukünftige Versionen werden höchstwahrscheinlich Updates erhalten, alte nicht.

<div id="fragen-4" />

## Wie sieht's mit Updates aus?

Das ist etwas kompliziert. Da nun eine gepatchte Version installiert ist, können Updates über Google Play nicht einfach so eingespielt werden. Um ein Update durchzuführen, muss die neueste APK heruntergeladen werden (z.B. von APKPure), und dann neu gepatcht werden (also ab [Schritt 3](#schritt1-3)). Alternativ kann die aktuelle Version deinstallieren, und dann den ganzen Prozess von vorne beginnen (was natürlich den Nachteil hat, dass man sich erneut einloggen muss)

<div id="fragen-5" />

## Wie kann ich überprüfen ob eine heruntergeladene APK ein Original ist und nicht mit Schadware verseucht wurde?

Grundsätzlich sind Seiten wie [APKMirror](https://www.apkmirror.com/) (APKMirror verfügt leider noch nicht über Digitales Amt) und [APKPure](https://apkpure.com) seriös. Solltet ihr trotzdem sicherstellen wollen, dass ihr eine echte APK heruntergeladen habt, könnt ihr das wie folgt überprüfen:

Ladet euch [Apk Analyzer](https://play.google.com/store/apps/details?id=sk.styk.martin.apkanalyzer) herunter. Öffnet die App, und wählt rechts unten den Dateiselektor aus:

![image](https://user-images.githubusercontent.com/58902674/213252451-6ac1d0ab-38e2-4c09-b0cb-780499dcc141.png)

Nun wählt ihr die APK aus fragwürdiger Quelle aus:

![image](https://user-images.githubusercontent.com/58902674/213252620-88559a37-9ff8-476b-bc96-0a6ca2c6b421.png)


Dann tippt ihr oben auf "Certificate". Wenn nun alle Felder wie auf dem Screenshot aussehen, insbesondere die "Certificate MD5" (`658357a19e65b0cbe17ef178ab3521d9`), habt ihr eine legitime APK. 

![image](https://user-images.githubusercontent.com/58902674/213252918-8a65615b-f30a-4ccc-9911-cac0156ad27d.png)


<div id="fragen-6" />

## Die E-Ausweis App funktioniert nicht

Sollte nichts passieren, wenn ihr in der E-Ausweis App auf "Ich Nutze Digitales Amt" tippt:

![image](https://user-images.githubusercontent.com/58902674/214682606-277aadf1-cbc4-4a2d-b725-9043472d7ff2.png)

Macht ihr folgendes: Zuerst öffnet ihr die Einstellungen, danach wählt ihr Apps:

![image](https://user-images.githubusercontent.com/58902674/214682760-095fe59d-0389-44cc-8da6-c8e8b276d5a0.png)

Dann "Digitales Amt":

![image](https://user-images.githubusercontent.com/58902674/214682888-67d5ad6f-8b01-485e-9480-94120546896e.png)

Dort scrollt ihr etwas runter zur Option "Standardmäíg öffnen / Open by default":
![image](https://user-images.githubusercontent.com/58902674/214683071-948b391d-aa40-42b7-97c9-11133dd0ba09.png)

Hier wählt ihr nun "Link hinzufügen / Add link":

![image](https://user-images.githubusercontent.com/58902674/214683405-cc6cb652-6e74-4d3b-8b06-522c38b8a962.png)

Im folgenden wählt ihr nun alle Domains an und klickt auf "Hinzufügen / Add":
![image](https://user-images.githubusercontent.com/58902674/214683666-d33f87ef-ce02-4cfc-97a5-84a4f85324dd.png)


Die E-Ausweis-App sollte nun funktionieren.


<div id="fragen-7" />

## Die FinanzOnline App funktioniert nicht

Zuerst öffnet ihr die Einstellungen, danach wählt ihr Apps:
 
![image](https://user-images.githubusercontent.com/58902674/214682760-095fe59d-0389-44cc-8da6-c8e8b276d5a0.png)

Danach tippt ihr auf FON [+]:

![image](https://user-images.githubusercontent.com/58902674/214826346-f6c69579-8fce-44c7-84c7-4b774c19ca56.png)

Nach einem Klick auf "Standardmäíg öffnen / Open by default":

![image](https://user-images.githubusercontent.com/58902674/214827595-eea82efb-d16b-4229-80ce-d74a176504ae.png)

Tippt ihr auf "Link hinzufügen / Add link":

![image](https://user-images.githubusercontent.com/58902674/214827783-d979cd16-5288-45a9-b9ed-b632406f95b9.png)

Hier wählt ihr nun die Domain aus und tippt auf "Hinzufügen / Add":

![image](https://user-images.githubusercontent.com/58902674/214827975-d654020b-de58-4415-8ec6-d63d1c9044ad.png)


Fertig, ihr solltet nun die FinanzOnline App benutzen können.