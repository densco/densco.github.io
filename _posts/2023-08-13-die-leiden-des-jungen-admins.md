---
title: "Die Leiden des jungen* Admins"
layout: post
---

Ok, dieses Blog wird langsam sehr technik-lastig. Aber das liegt auch daran, dass mich solche Dinge gerade mehr interessieren als andere Themen. Seit langer Zeit beschäftige ich mich mit dem Thema Selfhosting, einerseits aus Lernwillen und andererseits um mich damit möglicherweise aus Abhängigkeiten von den Clouds Anderer zu lösen. Dabei versuche ich agnostisch zu sein und das Beste aus beiden Welten für mich nutzbar zu machen.

Das Thema Selfhosting bin ich gestern sehr konkret angegangen, indem ich beim Hoster meines geringsten Misstrauens einen günstigen vServer mit einem Monat "kostenlos testen" als Zugabe schoss. Originär war mein Plan, YunoHost zu verwenden und dort die eine oder andere Anwendung zu implementieren. Da die Bereitstellung des Servers beim Hoster immer etwas dauert, konnte ich erst heute Vormittag mit der Konfiguration starten. Im Folgenden hier die Dokumentation meiner Anläufe, damit andere Neulinge aus den von mir gemachten Fehlern lernen können:

#### Erster Anlauf
Passwort verbummelt. Peinlich. Server geflasht.

#### Zweiter Anlauf
Debian 12 installiert, Server abgesichert, YunoHost-Installation getriggert, Fehlermeldung bekommen (YunoHost arbeitet nur mit Debian 11). Server geflasht.

#### Dritter Anlauf
Debian 11 installiert, Server abgesichert, YunoHost-Installation getriggert. Alles lief soweit, ich konnte allerdings keine Apps auf Subdomains einrichten. Stattdessen warf mir YunoHost DNS-Konfigurationshinweise hin, mit denen ich wenig anfangen konnte. Auch intensive Recherche brachte mich nicht weiter. Nach zwei Stunden war ich ziemlich genervt und fasste einen Beschluss. Server geflasht.

#### Vierter Anlauf
Ubuntu 22.04. installiert, Server abgesichert, Cloudron-Installation getriggert. Was soll ich sagen: Gegen YunoHost fühlt sich Cloudron an, als würde man mich in einen weichen Sessel platzieren und abweichend Getränke und Speisen meiner Wahl reichen und die Füße massieren. Es ist so unfassbar einfach und es funktioniert alles, wie ich es mir vorgestellt habe. Ohne viel Einstellerei, sondern pragmatisch.

In den nächsten Tagen werde ich jetzt ausgiebig Integrationen testen und mir meine Selfhosting-Welt gestalten. Ein paar Ideen habe ich, aber ich muss mir dazu überlegen, wie meine Workflows dazu sein müssen. Jedenfalls ist der erste Schritt nun getan und darüber bin ich sehr glücklich.

*der nicht mehr so junge, aber das hatten wir ja schon.