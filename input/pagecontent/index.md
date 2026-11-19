<!--
  Schritt 7: Startseite eures IG
  Ersetzt die TODOs durch eigenen Text. Markdown ist erlaubt.
  Diese Seite ist die erste, die man auf GitHub Pages sieht.
-->

### Use Case

TODO: Beschreibt in zwei bis drei Sätzen, welche Situation euer IG abbildet.
Wer erfasst die Daten, wer liest sie, und wofür werden sie gebraucht?

In einer Hausarztpraxis werden Arzneimittelallergien durch eine Ärztin oder einen Arzt strukturiert erfasst. Die Informationen werden von einer Notfallstation verwendet, um bekannte Allergien bei der Behandlung zu berücksichtigen und unerwünschte allergische Reaktionen auf Medikamente zu vermeiden.

### Scope

TODO: Was deckt dieses IG ab, und was bewusst nicht?

Dieser Implementation Guide beschreibt die strukturierte Erfassung von Arzneimittelallergien auf Basis der FHIR-Ressource AllergyIntolerance und CH Core. Er umfasst den klinischen Status, die Allergiecodes, die Kritikalität, den Beginn sowie mögliche Reaktionen und Symptome.
Andere Allergiearten, beispielsweise Lebensmittelallergien, und die Dokumentation der medikamentösen Behandlung sind nicht Bestandteil dieses Implementation Guides.

### Artefakte

TODO: Ergänzt pro Artefakt einen Satz, wofür es da ist.

* [DG Arzneimittelallergie](StructureDefinition-dg-medication-allergy.): DG Arzneimittelallergie: Dieses Profil definiert die Anforderungen an die strukturierte Erfassung von Arzneimittelallergien und basiert auf CH Core AllergyIntolerance.
* [Penicillinallergie bei Anna Muster](AllergyIntolerance-TODO_Name.html): Dieses Beispiel zeigt eine bestätigte Penicillinallergie mit hoher Kritikalität und Urtikaria als dokumentierter Reaktion.

<!-- TODO_Name ist der Name hinter "Instance:" in beispiele.fsh,
     z. B. AllergyIntolerance-PenicillinAllergieAnna.html -->

### Abhängigkeiten

Dieses IG baut auf [CH Core 6.0.0](https://fhir.ch/ig/ch-core/6.0.0/) auf.

### Autorin oder Autor

TODO: Sara Fotakis

<p style="font-size:smaller">Erstellt im Lab des Moduls Data Standards in Healthcare, ZHAW, HS26. Kein offizieller Standard.</p>
