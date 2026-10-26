# Dexters Crystal Cheat — Starter

Starterprojekt für eine Minecraft-Java-Client-Mod mit einer GUI, die sich am bereitgestellten Prestige-Screenshot orientiert.

## Enthalten
- Fabric-Mod-Projektstruktur für Minecraft Java 1.21.11
- Client-Einstiegspunkt
- erste ClickGUI-Struktur mit Kategorien und drei Themes
- HTML-Design-Prototyp zum schnellen Testen des Layouts im Browser

## Hinweis
Dies ist ein Startgerüst, kein fertig getesteter Minecraft-Build. Versionsnummern für Fabric Loader, Fabric API und Loom können sich ändern. Prüfe sie vor dem ersten Build im offiziellen Fabric-Setup.

## GUI-Prototyp öffnen
Öffne `prototype/index.html` im Browser. Links lassen sich Kategorien wählen; oben rechts kann zwischen Rot, Lila und Blau gewechselt werden.

## Minecraft-Projekt
1. Installiere JDK 21.
2. Öffne den Projektordner in IntelliJ IDEA.
3. Prüfe `gradle.properties` und aktualisiere bei Bedarf Fabric Loader/API/Loom auf kompatible Releases.
4. Starte `gradle build`.
5. Die Mod-JAR liegt nach erfolgreichem Build unter `build/libs/`.

Die Combat-Module sind zunächst nur UI-Platzhalter. AutoCrystal/AutoAnchor/SafeAnchor sollten erst in einer privaten Testwelt oder Umgebung mit ausdrücklicher Erlaubnis implementiert und getestet werden.
