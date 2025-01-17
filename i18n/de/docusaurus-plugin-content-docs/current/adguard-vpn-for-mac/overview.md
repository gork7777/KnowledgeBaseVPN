---
title: Funktionsübersicht
sidebar_position: 1
---

AdGuard VPN für Mac ist ein Desktop-VPN-Dienst. AdGuard VPN ist vollständig kompatibel mit AdGuard Werbeblocker, sie können zusammen verwendet werden und funktionieren nahtlos. Erfahren Sie, welche Funktionen die App zu bieten hat.

Beachten Sie, dass **Sie AdGuard VPN für Mac nur verwenden können, wenn Sie sich bei Ihrem AdGuard-Konto angemeldet haben**. Sie können sich entweder mit Ihrem AdGuard-Konto anmelden oder mit einem externen Konto, nämlich über Apple, Google oder Facebook. Stellen Sie sicher, dass Ihr externes Konto an dieselbe E-Mail-Adresse wie Ihr AdGuard-Konto gebunden ist. Wenn in Ihrem AdGuard-Konto ein passendes Abonnement vorhanden ist, wird es automatisch in der Desktop-App aktiviert. Haben Sie noch kein AdGuard-Konto? Erstellen Sie es [hier](https://auth.adguard.com/registration.html).

> AdGuard VPN für Mac wird derzeit auf macOS-Versionen ab macOS Sierra (10.12) unterstützt.

## Startbildschirm

![Startbildschirm](https://cdn.adguard.com/public/Adguard/Blog/mac-vpn-main.png)

Die erste Registerkarte ist der Bildschirm *Home*. Here you can see AdGuard VPN current status and [exclusions mode](#exclusions), chosen location (if enabled) and its ping. Ping ist die Reaktionszeit eines VPN-Servers. Je niedriger diese Zahl ist, desto schneller ist die Verbindung. Wenn VPN deaktiviert ist, wird unten der letzte Standort angezeigt, mit dem Sie verbunden waren. Die schnellsten Standorte mit den niedrigsten Pings werden in der oberen rechten Ecke des Bildschirms angezeigt. Unten sehen Sie die vollständige Liste der Standorte. Sie können den gewünschten Ort leicht mit der Suchfunktion finden.

> Kostenlose Benutzer können sich nur mit bestimmten Standorten verbinden, während andere blockiert sind. Außerdem gibt es in der kostenlosen Version ein monatliches Traffic-Limit von 3 GB.

## Ausschlüsse

![Ausschlüsse](https://cdn.adguard.com/public/Adguard/Blog/vpn/release/VPN_for_Mac/exclusions.png)

Als nächstes erscheint der Bildschirm *Ausschlüsse*. AdGuard VPN has several features that make it unique, and one of them is certainly switching between two exclusions modes. In the General mode, AdGuard VPN will run on all websites but the ones from the exclusions list. Im Selektiven Modus hingegen arbeitet das VPN nur auf den Sites aus der Liste. Sie können selbst entscheiden, wo VPN funktionieren soll.

![Abschnitt: Ausschlüsse](https://cdn.adguard.com/public/Adguard/Blog/services.png)

Außerdem können Sie nicht nur Websites zu Ausschlüssen hinzufügen, sondern auch aus den Listen beliebter Dienste auswählen. Die Listen sind in acht Kategorien unterteilt: Soziale Netzwerke, Messenger, Video- und Musik-Streaming-Dienste, Spiele, Shopping, Suchmaschinen und Tools für die Arbeitskommunikation. Jeder dieser Dienste kann mit einem Klick zu Ausschlüssen hinzugefügt werden. Dies ist besonders praktisch, wenn Sie den Selektiven Modus verwenden.

Ausschlussliste kann einfach konfiguriert werden. Wenn Sie eine Domain und einige ihrer Subdomains hinzugefügt haben, werden diese innerhalb der Root-Domain gruppiert. Beim Hinzufügen einer Root-Domain (`example.com`) wird auch ihre Maske hinzugefügt (`*.example.com`).

Wenn Sie einen Dienst hinzugefügt, etwas geändert oder entfernt haben und nun die ursprünglichen Einstellungen wiederherstellen möchten, drücken Sie einfach *Auf Standard zurücksetzen* neben der Domain – diese Aktion stellt alle fehlenden Domains wieder her und aktiviert alle Kontrollkästchen.

Außerdem können fertige Ausschlusslisten auf andere Geräte mit installiertem AdGuard VPN übertragen werden. Befolgen Sie zum Exportieren von Ausschlüssen die nachstehende Anleitung:

1. Öffnen Sie AdGuard VPN auf dem Gerät, von dem Sie Ihre Ausschlusslisten exportieren möchten. Suchen Sie den entsprechenden Abschnitt und klicken Sie auf die Schaltfläche *Exportieren*. Das Archiv `exclusions.zip` wird heruntergeladen.
2. There are two `.txt` files inside the archive, each for General and Selective lists. Fügen Sie ihnen weitere Ausschlüsse hinzu, löschen Sie die vorhandenen, benennen Sie Dateien um (mehr dazu — später) oder lassen Sie das Archiv mit den Dateien einfach unverändert.
3. Vergessen Sie beim Übertragen zwischen verschiedenen Geräten nicht, die `.zip`-Datei zum Importieren an das Gerät zu senden. Wenn Sie beispielsweise Ausschlusslisten von Ihrem Mac-Gerät auf Ihr iPhone importieren, stellen Sie sicher, dass Sie die `.zip`-Datei vorher an Ihr iPhone senden.
4. Öffnen Sie AdGuard VPN auf dem Gerät/im Browser, wo Sie das Archiv mit den fertigen Ausschlusslisten importieren möchten. Suchen Sie den entsprechenden Abschnitt, klicken Sie auf die Schaltfläche *Importieren* und wählen Sie das Archiv aus. Fertig!

> Archiv-Dateien von anderen Geräten können auf ähnliche Weise in Ihr AdGuard VPN für Mac importiert werden.

## Support

![Support-Bildschirm](https://cdn.adguard.com/public/Adguard/Blog/vpn/release/VPN_for_Mac/support.png)

Die dritte Registerkarte ist der Bildschirm *Support*. Finden Sie Antworten auf alle Fragen in den [FAQ](https://adguard-vpn.com/en/welcome.html#faq) oder in den Abschnitten der [Wissensdatenbank](/intro.md), melden Sie einen Fehler, wenn Sie auf einen stoßen, oder [diskutieren Sie AdGuard auf einer der Plattformen](https://adguard.com/en/discuss.html). Und zögern Sie nicht, [Feedback zu unserem Produkt zu hinterlassen](https://surveys.adguard.com/en/vpn_mac/form.html).

## Einstellungen

![Einstellungen](https://cdn.adguard.com/public/Adguard/Blog/vpn/release/VPN_for_Mac/settings.png)

Schließlich kommen wir zur Registerkarte Einstellungen. Im Abschnitt *Über das Programm* können Sie die aktuelle Version von AdGuard VPN sehen, nach Updates suchen, unsere offizielle Website besuchen und sich mit der EULA und Datenschutzrichtlinie von AdGuard vertraut machen. Im Abschnitt *Über Lizenz* können Sie von kostenlos auf unbegrenzt upgraden, Ihr Abonnement verwalten oder sich abmelden. Und vor allem können Sie von hier aus auf *Allgemeine Einstellungen* zugreifen.

### Allgemeine Einstellungen

![Allgemeine Einstellungen](https://cdn.adguard.com/public/Adguard/Blog/vpn/release/VPN_for_Mac/general-settings.png)

Die ersten vier Grundfunktionen machen die App bequemer und benutzerfreundlicher, d.h. *Kill Switch*, *Automatisch aktualisieren*, *AdGuard VPN bei der Anmeldung starten* und *Automatisch beim App-Start verbinden*. Darüber hinaus können Sie zwischen hellen, dunklen und Systemthemen wählen – letzteres entspricht dem Thema auf Ihrem Mac.

Eine weitere Option, die nicht übersehen werden sollte, ist, dass Sie AdGuard VPN erlauben können, anonymisierte Absturzberichte, technische und Interaktionsdaten zu sammeln und zu senden, um uns bei der Verbesserung unserer App zu helfen. Dank der Schaltfläche auf der rechten Seite können Sie Protokolle auf Ihren Mac exportieren. Dies kann nützlich sein, wenn Sie Protokolle an Ihre Nachricht an den Support anhängen möchten.

### DNS-Server

![DNS-Server](https://cdn.adguard.com/public/Adguard/Blog/vpn/release/VPN_for_Mac/dns.png)

Hier können Sie einen benutzerdefinierten DNS-Server (oder mehrere Server) hinzufügen, um nicht standardmäßig auf einen von Ihrem ISP bereitgestellten DNS-Server angewiesen zu sein. Wir empfehlen das Hinzufügen von AdGuard DNS, das nicht nur Ihren DNS-Verkehr verschlüsselt, sondern auch Anfragen an bösartige Websites identifiziert und sie an ein „Blackhole“ weiterleitet.

### Erweiterte Einstellungen

![Erweiterte Einstellungen](https://cdn.adguard.com/public/Adguard/Blog/vpn/release/VPN_for_Mac/advanced-settings.png)

Erweiterte Einstellungen sollten nicht angepasst werden. Ändern Sie sie nicht, es sei denn, Sie werden von unserem technischen Support dazu aufgefordert oder Sie sind sich sicher, was Sie tun.

#### Protokollierungsebene
Es gibt nur zwei Protokollierungsebenen, aber wir empfehlen dringend, dass Sie die erste Standardebene verwenden. Die zweite Option (erweiterte Protokollierung) sollte nur nach Rücksprache mit unserem technischen Support eingestellt werden, um ein ungewöhnliches Programmverhalten aufzuzeichnen. Auch wenn Sie die zweite Protokollierungsebene aktiviert haben, stellen Sie sicher, dass Sie nach dem Aufzeichnen von Protokollen zur Standardebene zurückkehren.

#### Menüleistensymbol ausblenden
Diese Option befindet sich zwar in *Erweiterten Einstellungen*, kann aber bedenkenlos aktiviert werden. Sie können das AdGuard VPN-Symbol in der Menüleiste ausblenden, es verhindert jedoch nicht, dass unsere App im Hintergrund läuft.

#### QUIC verwenden (experimentell)

Das QUIC-Kommunikationsprotokoll ist die neueste, hochmoderne Version von HTTP. Schalten Sie den Schalter um, um eine bessere Verbindungsqualität unter nicht idealen Bedingungen zu erhalten, z. B. bei der Verwendung mobiler Daten in der U-Bahn oder im Aufzug.
