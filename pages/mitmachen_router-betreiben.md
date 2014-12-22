---
title: Freifunk-Router aufstellen
layout: page
permalink: /mitmachen/router-aufstellen/
---

Du willst gerne einen Freifunk-Knoten betreiben und weißt noch wie das funktioniert bzw. was du dafür benötigst? Dann gibt es hier einen kurzen Überblick, der hoffentlich einige Unklarheiten beseitigt.

After you have all the necessary equipment, you can [proceed to the firmware installation](firmware-installieren).

Am Ende der Seite gibt es eine Begriffserklärung. Nach dem bebilderten groben Überblickt gibt es auch noch eine textuelle Beschreibung.

## Was brauche ich dafür?

Some intro words...

### Freifunk-fähiger WLAN-Router

Natürlich darf der WLAN-Router nicht fehlen. Als Standort empfehlen sich Fenster, Balkone oder Dächer (I would generalize to places where it can be in range of users and other devices). Je näher er der Außenwelt ist desto wahrscheinlicher ist es, dass er sich mit anderen Routern verbindet und das sogenannte Mesh bildet.

### Strom

Um einen WLAN-Router optimal zu versorgen, braucht er auf jedenfall einen freien Steckplatz für das Netzteil. Ob in einer Steckerleister oder direkt aus der Wand ist egal, die sind nicht wählerisch!

Damit der Router sich mit seinen Artgenossen verständigen kann und seine Dienste den Nutzern zur Verfügung stellt, empfiehlt es sich, dass er rund um die Uhr an ist. Die aktuellen Geräte sind sehr sparsam und verbrauchen auch wenig.

### Netzkabel

Da die mitgelieferten Netzkabel recht kurz sind (ca. 1-2m) brauch man oft längere Netzwerkkabel, damit man die Verbindung zum Heimnetzwerk hinbekommt. Es gibt auch sogenannte Flachbandkabel, welche man problemlos Zwischen Türen und Fenster bekommt.

### Internetverbindung (optional)

Wenn man seinen Internetanschluss mit anderen Freifunkern teilen möchste, brauch man noch einen freien Netzwerkport an seinem DSL-, Kabelrouter oder was man sonst benutzt um sein Netzwerk zu verwalten.

It is important to explain that if there is no Internet connection nor a neighbouring node nearby, it will not work as expected.

Der ganze Datenverkehr von dem FF-Router wird durch einen virtuellen Netzwerktunnel (VPN) zu den Freifunk-Darmstadt-Servern übertragen und gelangt erst ab da ins freie Internet. Ängste vor der berüchtigten Störerhaftung sind daher unbegründet. Bei genaueren Fragen zum VPN-Tunnel und zur Konfiguration findest du <a href="sicherheit.html">hier</a> weitere Informationen oder kannst auf der Mailingliste oder beim Treffen nachfragen.


## Wie gelange ich zu einem Freifunk-Knoten?


Es gibt im Grunde drei Wege um zu einen das am Freifunknetz teilnimmt:

* ein vorhandenes Gerät recyclen und mit der Freifunkfirmware ausstatten
* ein unterstütztes Gerät erwerben und selbst mit der Freifunkfirmware ausstatten
* sich an uns wenden und einen vorkonfigurierten Wlanrouter zum Selbstkostenpreis adoptieren

### Vorhandene Geräte wiederverwenden

Falls du noch einen WLAN-Router rumstehen hast, der gerade nichts macht oder den du wiederverwerten möchtest, kann man überpüfen ob Firmware dafür existiert. Das kann man auf der <a href="http://update.freifunk-darmstadt.de/">Firmwaredownloadseite</a> oder einfach bei uns Nachfragen. Die Geräte die es vom DSL- oder Kabelprovider gibt sind dafür in der Regel nicht geeignet.

### Ein neues Gerät erwerben

Falls du lieber ein neues Gerät erwerben willst und das vielleicht sowieso vor hattest weil ein WLAN-Router selten den ganzen Wohnraum abdecken kann, gibt es eine Vielzahl an möglichen Modellen. Je nach Anwendungsfall eignen sich unterschiedliche Geräte. Die unterstützten Geräte finden sich auch auf der Firmwaredownloadseite oder frag uns einfach auf der Mailingliste oder bei einem der Treffen vor Ort.

### Ein Gerät adoptieren

Falls du doch lieber einen der von uns vorkonfigurierten Geräte ein neues Zuhause geben willst, geht das natürlich auch. Die Geräte sind vorkonfiguriert und brauchen nur Strom (und Netzwerk). Sind quasi per Plug und Play bereit. Hierfür empfiehlt es sich auch vorher mit uns Kontakt aufzunehmen


## Weitere Informationen und Hinweise

### Wo stehen schon Freifunk-Router?

Schau mal auf der <a href="karte.html">Netzkarte</a> nach. Wenn es bei dir noch keinen Freifunk-Router in der Nachbarschaft gibt, dann sei die oder der Erste!

### Benötige ich einen Router für 2.4 GHz oder 5 GHz?

Damit sich ein Freifunk-Router mit einem anderen Freifunk-Router über WLAN verbinden kann, müssen beide Router im gleichen Frequenzband (2.4 GHz oder 5 GHz) arbeiten. Bitte vorher prüfen!

### Können mehrere Freifunk-Router an einem Ort miteinander verbunden werden?

Mehrere Freifunk-Router können über ein Switch mit Netzwerk-Kabeln verbunden werden. Der im Starter-Kit empfohlene Router hat z.B. ein integriertes Switch.