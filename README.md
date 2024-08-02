# Konzept für neue Website bislich.de

Neuauflage der Website für Bislich.

> Ein Dorf, eine Seite, viele Vereine

Neben einer Überarbeitung des Designs soll die neue Website vor allem als geteilte Plattform für alle Bislicher Vereine dienen.

## Grundlegende Struktur

Die Website ist unterteilt in zwei Bereiche bzw. Bereichskategorien: Den Gesamtbereich und die Vereinsbereiche.

### Gesamtbereich

In dem Gesamtbereich existieren zum einen Beiträge, die das Dorf im Gesamten betreffen oder vereinsübergreifend relevant sind.
Zum anderen laufen in diesem Bereich die Beiträge der Vereine zusammen, die von besonderer Relevanz sind.

Der Gesamtbereich wird zu finden sein unter `bislich.de`.

### Vereinsbereiche

Die Vereinsbereiche werden von den Vereinen selbst mit Beiträgen gefüllt und sind über eine Subdomain nach dem Schema `{verein}.bislich.de` erreichbar.

Beispiel: Der Vereinsbereich vom Tennisclub könnte unter `tc.bislich.de` erreichbar sein.

## Design und Flexibilität

Das Design muss noch erarbeitet werden.
Es ist grundsätzlich möglich, dass die Designs für die einzelnen Vereine voneinander abweichen.
Es sollte aber insgesamt ein einheitliches Design verwendet werden, wo es möglich ist.

## Tech Stack

Stand heute werden vermutlich folgende Technologien zum Einsatz kommen:

- Backend: AWS Lambda Functions (Python)
- Frontend: VueJS + Quasar
- File Storage: AWS S3
- Database: MongoDB
- Auth: Auth0 oder Keycloak

## URL Shortener

Die Domain `bisli.ch` kann für Kurz-URLs verwendet.
Es ist allen Vereinen möglich, Kurz-URLs zu erstellen und zu verwalten.

## Ablösung von Domains

Die heute vorhandenen Domains, die pro Verein angelegt wurden, können nach und nach abgelöst werden.
Das macht es einfacher, den Zusammenhang der Websites zu erkennen.
