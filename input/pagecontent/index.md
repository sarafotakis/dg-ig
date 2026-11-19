
### Use Case

In einer Hausarztpraxis werden Arzneimittelallergien durch eine Ärztin oder einen Arzt strukturiert erfasst. Die Informationen werden von einer Notfallstation verwendet, um bekannte Allergien bei der Behandlung zu berücksichtigen und unerwünschte allergische Reaktionen auf Medikamente zu vermeiden.

### Scope

Dieser Implementation Guide beschreibt die strukturierte Erfassung von Arzneimittelallergien auf Basis der FHIR-Ressource AllergyIntolerance und CH Core. Er umfasst den klinischen Status, die Allergiecodes, die Kritikalität, den Beginn sowie mögliche Reaktionen und Symptome.

Andere Allergiearten, beispielsweise Lebensmittelallergien, und die Dokumentation der medikamentösen Behandlung sind nicht Bestandteil dieses Implementation Guides.

### Artefakte

- [DG Arzneimittelallergie](StructureDefinition-dg-medication-allergy.html): Dieses Profil definiert die Anforderungen an die strukturierte Erfassung von Arzneimittelallergien und basiert auf CH Core AllergyIntolerance.

- [Penicillinallergie bei Anna Muster](AllergyIntolerance-PenicillinAllergieAnna.html): Dieses Beispiel zeigt eine bestätigte Penicillinallergie mit hoher Kritikalität und Urtikaria als dokumentierter Reaktion.

### Abhängigkeiten

Dieses IG baut auf [CH Core 6.0.0](https://fhir.ch/ig/ch-core/6.0.0/) auf.

### Autorin oder Autor

Sara Fotakis

Erstellt im Lab des Moduls Data Standards in Healthcare, ZHAW, HS26. Kein offizieller Standard.
