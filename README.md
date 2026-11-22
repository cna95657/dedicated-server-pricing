# Dedicated Server mieten günstig: Was der Einstieg wirklich kostet, wann ein vServer reicht und warum die Einrichtungsgebühr einen Monat extra bedeutet (mit Tarifvergleich)

Ein echter Dedicated Server, also eine komplette Maschine für dich allein, beginnt im deutschen Markt derzeit bei rund 35 bis 55 € im Monat. Wer „dedicated" als garantierte, exklusive CPU-Kerne liest, kommt schon ab 12,93 € netto monatlich rein, sitzt dann aber auf einer virtualisierten Maschine. AVA Hosting, dessen Preise ich hier durchgehe, hat zwei sehr verschiedene Einstiege: vCPU-Tarife ab 2,00 € im Monat und Bare Metal ab 85 €.

Der Rest des Textes sortiert, welche dieser Zahlen was bedeutet, was im ersten Vertragsjahr tatsächlich abgebucht wird und ab welcher Projektgröße sich welcher Weg lohnt.

> **Schnellentscheidung:** Du brauchst eine abgeschottete Umgebung mit garantierten Ressourcen und willst monatlich zahlen? Dann trägt der Power-Tarif von AVA Hosting mit 8 vCPU, 16 GB RAM und 200 GB NVMe für 40,00 € im Monat die meisten Projekte, die einem vServer entwachsen sind. Brauchst du Hardware-Zugriff, eigenes RAID oder dein eigenes Kernel-Setup, führt am Bare-Metal-Weg ab 85 € im Monat nichts vorbei.
> 👉 [Alle Tarife und aktuellen Preise auf der Bestellseite ansehen](https://my.ava.hosting/aff.php?aff=15562)

## Die aktuellen Tarife von AVA Hosting im Überblick

AVA Hosting führt auf seiner Bestellseite sechs Tarife der Reihe „Self-hosted Start". Sie arbeiten mit vCPU-Anteilen, was ein wichtiger Unterschied zu einer dedizierten Maschine ist (dazu weiter unten). Alle sechs enthalten unbegrenzten Transfer, die Preise sind als Monatspreis in Euro ausgewiesen.

| Tarif | vCPU | RAM | NVMe-Speicher | Preis pro Monat | Bestellen |
| --- | --- | --- | --- | --- | --- |
| Start | 1 vCPU | 1 GB | 15 GB | ab 2,00 € | [ Start-Tarif ansehen](https://my.ava.hosting/aff.php?aff=15562) |
| Mini | 1 vCPU | 2 GB | 25 GB | ab 5,00 € | [ Mini-Tarif ansehen](https://my.ava.hosting/aff.php?aff=15562) |
| Basic | 2 vCPU | 4 GB | 50 GB | ab 10,00 € | [ Basic-Tarif ansehen](https://my.ava.hosting/aff.php?aff=15562) |
| Pro | 4 vCPU | 8 GB | 100 GB | ab 20,00 € | [ Pro-Tarif ansehen](https://my.ava.hosting/aff.php?aff=15562) |
| Business | 6 vCPU | 12 GB | 150 GB | ab 30,00 € | [ Business-Tarif ansehen](https://my.ava.hosting/aff.php?aff=15562) |
| Power | 8 vCPU | 16 GB | 200 GB | ab 40,00 € | [ Power-Tarif ansehen](https://my.ava.hosting/aff.php?aff=15562) |

Was in der Tabelle nicht steht und beim Vergleich wichtig ist:

- **Abrechnung:** monatlich, Preise in Euro. Eine Mindestlaufzeit ist auf der Bestellseite nicht ausgewiesen, ebenso wenig eine Einrichtungsgebühr. Beides steht erst im Checkout verbindlich.
- **MwSt.:** ob die ausgewiesenen Beträge netto oder brutto sind, geht aus der Bestellseite nicht hervor. Das ist bei jedem Anbieter einzeln zu prüfen, sonst vergleichst du 2,00 € netto mit 136,99 € brutto.
- **Test:** für den Einstieg ist ein „Free Trial" ausgewiesen.
- **Bare Metal:** AVA Hosting nennt für seine dedizierten Maschinen Konfigurationen von 85 bis 149 € im Monat, standardmäßig unmanaged, mit optionalem Managed-Support für 20 € pro Stunde. Diese Konfigurationen sind auf der aktuellen Bestellseite nicht als einzelne Tarifzeilen hinterlegt, die Spanne stammt von der dedizierten Produktseite des Anbieters.

## Was „günstig" bedeutet: drei Produktarten, die alle Dedicated heißen

Der Suchbegriff führt regelmäßig zu Angeboten, die technisch drei verschiedene Dinge sind. Wer das nicht auseinanderhält, vergleicht 12 € mit 36 € und wundert sich über den Unterschied.

**Virtualisierte Maschine mit dedizierten Ressourcen.** netcup beschreibt seine Root Server als virtualisierte Umgebung, in der dir eine feste Zahl CPU-Kerne, RAM und Storage exklusiv zugeteilt wird, mit vollem Root-Zugriff und Betrieb in deutschen Rechenzentren. Der Einstieg RS 500 G12.5 mit 2 dedizierten Kernen, 4 GB RAM und 64 GB NVMe liegt bei 12,93 € netto, mit 19 % MwSt. bei 14,87 € im Monat, bei 12 Monaten Laufzeit und 30 Tagen Geld-zurück-Garantie. Nach oben geht es bis RS 16000 G12.5 mit 24 Kernen, 128 GB RAM und 2 TB NVMe für 289,46 € netto (332,88 € brutto).

**KVM-Server.** Datalix führt KVM- und Dedicated-Server in derselben Produktübersicht getrennt auf, was die Sache ehrlicher macht als die meisten Preislisten. Die KVM-Reihe startet bei 2,45 € (Ryzen), 4,95 € (Epyc) und 5,99 € (Xeon) im Monat, die dedizierten Maschinen bei 34,95 € (Sale Dedicated Server) und 54,95 € (Intel Dedicated Server). Alle Dienste laufen als Prepaid, nach der gebuchten Zeit wird der Server gelöscht.

**Bare Metal.** ZAP-Hosting schreibt es am deutlichsten hin: kein geteilter VM-Host, exklusive CPU, SATA-SSD oder NVMe je nach Angebot, 10 bis 25 Gbit/s Anbindung, Standort Frankfurt oder Eygelshoven. Dazu 99,5 % Uptime-SLA und DDoS-Schutz ohne Aufpreis.

Für AVA Hosting heißt das: die sechs Self-hosted-Start-Tarife gehören in die erste Kategorie, die Bare-Metal-Konfigurationen ab 85 € in die dritte. Wenn du eine ganze Maschine willst, ist der 40-€-Tarif nicht die günstigere Variante derselben Sache, sondern ein anderes Produkt.

## Der erste Vertrag kostet mehr als der Monatspreis

Zwei Posten tauchen in fast keiner Übersicht auf und verschieben die Rangliste: Einrichtungsgebühren und die Frage, ob Preise netto oder brutto sind.

Bei STRATO kostet die Einrichtung genauso viel wie ein Monat. Der CP4-03 SSD mit Xeon E3-1230v6 (4C/8T, bis 3,9 GHz Turbo), 16 GB DDR4 ECC und 2×480 GB SSD im Soft-RAID 1 steht mit „ab 36 €/Mon." plus 36 € Einrichtung. Im ersten Jahr sind das 36 × 13 = **468 €**. Der CP8-109 NVMe mit Xeon E-2478, 128 GB DDR5 ECC und 2×2 TB NVMe liegt bei ab 216 € plus 216 € Einrichtung, also 2.808 € im ersten Jahr.

OVHcloud rechnet in der Advance-Reihe genauso und weist die Preise inklusive MwSt. aus. Der ADVANCE-12024 (EPYC 4244P, 6c/12t, 32 GB DDR5-5200, 2×960 GB NVMe) kostet 136,99 € im Monat plus 136,99 € Installation, im ersten Jahr **1.780,87 €**. Der ADVANCE-12026 mit DDR5-5600 und Datacenter-Class-NVMe liegt bei 191,00 € und damit 54,01 € pro Monat über dem 2024er Modell.

Bei netcup ist keine Einrichtungsposition ausgewiesen, dafür brauchst du für einen sauberen Vergleich beide Preisspalten. Der RS 2000 G12.5 (8 Kerne, 16 GB, 256 GB NVMe) kostet 40,70 € netto monatlich, inklusive MwSt. 46,81 €. Aufs Jahr gerechnet sind das 488,40 € netto oder **561,72 € brutto**.

Für AVA Hosting gilt derselbe Vorbehalt: die Bestellseite zeigt keine Einrichtungsgebühr, was nichts darüber aussagt, ob im Checkout eine auftaucht.

👉 [Die sechs Self-hosted-Start-Tarife mit den aktuellen Monatspreisen prüfen](https://my.ava.hosting/aff.php?aff=15562)

## Laufzeit und Ausstieg: drei Modelle, die sich stark unterscheiden

Wer zum ersten Mal einen Dedicated Server mietet, will meist nach vier Wochen wieder raus können, wenn die Kiste nicht trägt. Wie teuer dieser Ausstieg wird, hängt vom Vertragsmodell ab.

netcup arbeitet mit 12 Monaten Laufzeit und gibt 30 Tage Geld-zurück. Du bist also ein Jahr gebunden, kannst aber in der ersten Zeit ohne Begründung raus. ZAP-Hosting lässt die Laufzeit wählen: 3, 30, 90, 180 Tage oder ein Jahr, automatische Verlängerung, Kündigung jederzeit zum Laufzeitende, danach werden Server und Daten gelöscht. Datalix geht den dritten Weg und verkauft ausschließlich Prepaid. Nach der gebuchten Zeit wird der Server gelöscht, eine Kündigung ist nicht nötig.

Das sind drei sehr verschiedene Risiken. Zwölf Monate mit Rückgabefenster passen zu jemandem, der die Maschine produktiv braucht. Prepaid passt zu jemandem, der erst testet. Und die monatliche Abrechnung, die bei AVA Hosting ausgewiesen ist, passt zu beiden, solange im Checkout keine Mindestlaufzeit auftaucht.

👉 [Tarife mit monatlicher Abrechnung und ausgewiesenem Free Trial ansehen](https://my.ava.hosting/aff.php?aff=15562)

## Welcher Tarif zu welchem Projekt passt

Die Entscheidung hängt an zwei Fragen: brauchst du die Hardware oder nur die Leistung, und wie viel davon?

**Einzelne Website, kleiner API-Endpunkt, Bot, Testumgebung.** Hier ist ein Dedicated Server Geldverbrennung. Die KVM-Klasse beginnt bei 2,45 bis 5,99 € im Monat, und AVA Hosting deckt dasselbe mit Start (1 vCPU, 1 GB, 15 GB NVMe, ab 2,00 €) und Mini (1 vCPU, 2 GB, 25 GB, ab 5,00 €) ab. Für einen Blog mit wenig Traffic oder einen einzelnen Dienst ist das die vernünftige Größe.

**Datenbank, mehrere Container, Spieleserver mit Mods, CI-Runner.** Ab hier stören Nachbarn. Der Pro-Tarif mit 4 vCPU, 8 GB RAM und 100 GB NVMe für 20,00 € ist der Punkt, an dem die meisten Umzüge von einem 5-€-vServer landen. Wer mehr Reserve will, nimmt Power mit 8 vCPU, 16 GB und 200 GB für 40,00 €.

**Eigenes RAID, eigener Kernel, Virtualisierung mit KVM, Spezialhardware.** Das geht nur mit Bare Metal. Bei AVA Hosting beginnt die Spanne bei 85 € im Monat, unmanaged. Wer keine eigene Systemadministration hat, sollte die 20 € pro Stunde für Managed-Support einkalkulieren, sonst steht die Maschine nach dem ersten Kernel-Update.

## Wann du besser woanders buchst

AVA Hosting ist nicht der billigste Weg zu Blech, und das gehört in einen Vergleich. Die Bare-Metal-Spanne ab 85 € liegt über den 34,95 €, die Datalix für einen Sale Dedicated Server aufruft, und über den ab 36 €, die STRATO für den CP4-03 verlangt. Wer ausschließlich den niedrigsten Monatspreis für eine physische Maschine sucht, findet ihn dort. Bei Standortvielfalt ist OVHcloud mit über 40 Rechenzentren und einer Netzwerk-SLA von 99,95 % breiter aufgestellt als ein Anbieter mit einem Standort.

Der Gegenwert liegt woanders: monatliche Abrechnung ohne ausgewiesene Bindung, unmanaged Bare Metal mit stundenweise buchbarem Managed-Support statt eines Managed-Pakets, und eine Preisspanne, die von 2 € bis 149 € reicht, ohne dass du für den Einstieg einen Vertrag über ein Jahr unterschreiben musst.

## Häufige Fragen

**Ist ein günstiger Dedicated Server manchmal virtualisiert?**
Ja, und zwar regelmäßig. netcup schreibt selbst, dass die Root Server keine klassischen Bare-Metal-Systeme sind, sondern virtualisierte Maschinen mit exklusiv zugeteilten Kernen, RAM und Storage. Wer volle Hardware-Kontrolle braucht, muss auf „Bare Metal" achten, nicht auf „dedicated".

**Kann ich die Einrichtungsgebühr umgehen?**
Das hängt am Anbieter. STRATO und OVHcloud verlangen in den genannten Reihen jeweils eine Monatsmiete als Installation, was das erste Jahr um einen Monat verteuert. Bei netcup ist keine solche Position ausgewiesen. Bei ZAP-Hosting fallen Einrichtungsgebühren je nach Konfiguration an und stehen erst im Shop. Bei AVA Hosting zeigt die Bestellseite keine, der Checkout ist maßgeblich.

**Sind die Preise inklusive Mehrwertsteuer?**
Nicht einheitlich. netcup weist beide Werte aus (12,93 € netto, 14,87 € brutto), OVHcloud rechnet inklusive MwSt., bei STRATO und Datalix geht aus den Preisangaben nicht hervor, ob MwSt. enthalten ist. AVA Hosting macht dazu auf der Bestellseite ebenfalls keine Angabe.

**Wie lange bin ich gebunden?**
netcup: 12 Monate mit 30 Tagen Geld-zurück. ZAP-Hosting: 3, 30, 90, 180 Tage oder ein Jahr, Verlängerung automatisch. Datalix: Prepaid ohne Kündigung, Löschung nach der gebuchten Zeit. AVA Hosting: monatliche Abrechnung ausgewiesen, Mindestlaufzeit nicht ausgewiesen.

**Was passiert, wenn der Traffic nicht reicht?**
AVA Hosting weist für alle sechs Tarife unbegrenzten Transfer aus. OVHcloud gibt in der Advance-Reihe 3 Gbit/s öffentliche Bandbreite ungemessen und garantiert an, dazu 25 Gbit/s im privaten vRack. Bei den übrigen Anbietern ist das von der Konfiguration abhängig.

## Bevor du bestellst: zwei Zahlen prüfen

Die erste Zahl ist die Einrichtungsgebühr im Checkout. Sie entscheidet darüber, ob ein 36-€-Tarif im ersten Jahr 432 € oder 468 € kostet. Die zweite ist die Mehrwertsteuer. Ein 40-€-Tarif netto und ein 40-€-Tarif brutto liegen fast 20 % auseinander, und genau in dieser Größenordnung verschieben sich die Platzierungen in jeder Vergleichstabelle.

Die kurze Entscheidungsregel: einzelner Dienst oder Website → Start oder Mini bei AVA Hosting. Garantierte Kerne für Datenbank, Container oder Spieleserver → Pro oder Power. Eigene Hardware, eigenes RAID, eigener Kernel → Bare Metal ab 85 €, mit einkalkuliertem Managed-Support, wenn niemand im Team Linux administriert.

👉 [Tarife vergleichen und den passenden Einstieg direkt buchen](https://my.ava.hosting/aff.php?aff=15562)
