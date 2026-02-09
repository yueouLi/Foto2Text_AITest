# Foto2Text_AITest
# README – KI-Test zur Schadenbildbeschreibung

## 1. Ziel des Tests

Ziel dieses Tests ist es, die Leistungsfähigkeit verschiedener KI-Modelle bei der automatischen Beschreibung von Schadenfotos zu untersuchen.
Dabei soll insbesondere beantwortet werden:

* Wie präzise können die Modelle Schäden beschreiben?
* In welchen Situationen liefern sie ungenaue oder falsche Beschreibungen?
* Wo liegen die praktischen Grenzen der Modelle?

Der Fokus liegt nicht nur auf der besten Leistung, sondern auch auf der **Identifikation von Schwächen und Risikosituationen**.

---

## 2. Testaufbau

Der Test basiert auf einer Sammlung von Schadenbildern aus verschiedenen Objektkategorien und Schwierigkeitsstufen.

Jedes Bild wird mit demselben Prompt an verschiedene KI-Modelle gesendet.
Die erzeugten Beschreibungen werden anschließend anhand definierter Kriterien bewertet.

---

## 3. Objektkategorien

Die Bilder werden nach Objektart klassifiziert:

* **Fahrzeuge** (z. B. Autos mit Kratzern oder Dellen)
* **Elektronische Geräte** (z. B. Smartphones, Kameras)
* **Kücheneinrichtungen** (z. B. Arbeitsplatten, Schränke)
* **Optische Gegenstände** (z. B. Brillen)
* **Textilien** (z. B. beschädigte Kleidung)

Ziel dieser Einteilung ist es, die Modellleistung über verschiedene Sachbereiche hinweg zu vergleichen.

---

## 4. Schwierigkeitskategorien der Bilder

Die Testbilder werden in vier Kategorien eingeteilt:

### Kategorie A – Klare und eindeutige Schäden

* Deutlich sichtbare Schäden
* Gute Bildqualität
* Einfacher Hintergrund

Ziel: Test der Basisfähigkeit der Modelle.

---

### Kategorie B – Realistische Standardschäden

* Typische Alltagssituationen
* Komplexerer Hintergrund
* Mehrere Objekte im Bild möglich

Ziel: Simulation realer Schadensmeldungen.

---

### Kategorie C – Schwer erkennbare oder grenzwertige Schäden

* Kleine oder unscharfe Schäden
* Schlechte Beleuchtung
* Schwierige Perspektiven

Ziel: Identifikation der Leistungsgrenzen der Modelle.

---

### Kategorie D – Fallenbilder ohne echten Schaden

* Bilder ohne tatsächlichen Schaden
* Bilder mit irreführenden visuellen Effekten

Ziel: Prüfung, ob Modelle Schäden „halluzinieren“ oder Unsicherheit korrekt angeben.

---

## 5. Einheitlicher Prompt

Alle Modelle erhalten denselben Prompt:

> Beschreibe den sichtbaren Schaden auf dem Foto objektiv und detailliert.
> Nur sichtbare Fakten beschreiben, keine Vermutungen über Ursache oder Schuld.
> Wenn etwas nicht erkennbar ist, schreibe „nicht beurteilbar“.

---

## 6. Definition des Schweregrads

Der Schweregrad wird in drei Stufen eingeteilt:

### Leicht

Oberflächlicher oder kleiner Schaden ohne erkennbare Funktionsbeeinträchtigung.

### Mittel

Deutlicher Schaden, der sichtbar ist und möglicherweise die Funktion beeinträchtigt.

### Stark

Schwerer Schaden mit klarer Funktionsunfähigkeit oder struktureller Zerstörung.

### Sonderfall: Nicht beurteilbar

Der Schweregrad kann anhand des Bildes nicht zuverlässig bestimmt werden.

---

## 7. Bewertungskriterien

Jede KI-Beschreibung wird anhand folgender Kriterien bewertet (Skala 1–5):

1. **Richtigkeit**
   Wurde der Schaden korrekt erkannt?

2. **Detailgrad**
   Wie präzise und konkret ist die Beschreibung?

3. **Objektivität**
   Werden nur sichtbare Fakten beschrieben, ohne Spekulationen?

4. **Umgang mit Unsicherheit**
   Gibt das Modell korrekt an, wenn etwas nicht erkennbar ist?

---

## 8. Ziel der Auswertung

Am Ende des Tests sollen folgende Fragen beantwortet werden:

* Welche Modelle liefern die zuverlässigsten Beschreibungen?
* In welchen Bildkategorien treten die meisten Fehler auf?
* In welchen Situationen ist eine manuelle Prüfung notwendig?

Das Ergebnis dient als Grundlage für eine mögliche Integration von KI in den Schadenprozess.

你好
