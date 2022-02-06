# REDAXO → 📦

**Ein Frontend-Workflow für REDAXO auf Basis von 📦 [Parcel](https://parceljs.org).**

Status: Leider noch nicht einsatzbereit.


## Häufige Fragen 🙋

### Worin unterscheidet sich der Workflow von [Bimmelbam](https://github.com/FriendsOfREDAXO/redaxo-mit-bimmelbam)?

Bimmelbam basiert auf der Idee, das Frontend einer Website *außerhalb* von REDAXO entwickeln zu können. Dazu wurde ein sehr generischer Workflow entwickelt, der entsprechend viel Konfiguration benötigt und damit nicht immer auf Anhieb verständlich ist. Zudem ist das Setup inzwischen sehr in die Jahre gekommen.

Das neue Parcel-Setup soll nun viel näher an REDAXO sein und die typischen Anforderungen der Community bedienen, die oftmals mit dem **Theme- oder Project-AddOn** arbeitet. Dabei ist Parcel eine flexible Basis, die einfach erweitert werden kann und noch immer die Idee unterstützt, das Frontend *außerhalb* von REDAXO zu entwickeln.

### Warum Parcel?

Parcel kombiniert mehrere Tools in einem Paket und ist für typische Anwendungsfälle bereits vorkonfiguriert. Das macht es für uns sehr übersichtlich und erleichtert den Einstieg.

Und falls ein Projekt wächst und komplexer wird, lässt sich Parcel einfach erweitern.

### Gäbe es auch Alternativen zu Parcel?

Ja, [Vite](https://vitejs.dev) ist toll und bündelt wie Parcel mehrere Tools in einem Paket.

Zudem besteht immer die Möglichkeit, die notwendigen Tools nach Bedarf selbst zusammenzustecken. Ein gutes Beispiel dafür sind die zahlreichen Skripte innerhalb der [package.json von Bootstrap](https://github.com/twbs/bootstrap/blob/main/package.json#L22).

### Wird ein Wechsel von Bimmelbam aufwendig?

Dieses Projekt ist bereits auf typische REDAXO-Umgebungen ausgerichtet wie Theme-AddOn, Project-AddOn und Strukturen wie bei [Bimmelbam](https://github.com/FriendsOfREDAXO/redaxo-mit-bimmelbam) oder [Yak](https://github.com/yakamara/yak). Dabei ist es deutlich schlichter und verständlicher als Bimmelbam, alles wichtige spielt sich bereits in der `package.json` ab.

Vermutlich wirst du also mit wenig Aufwand von Bimmelbam auf Parcel wechseln können.
