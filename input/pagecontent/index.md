<!--
  Schritt 7: Startseite eures IG
  Ersetzt die TODOs durch eigenen Text. Markdown ist erlaubt.
  Diese Seite ist die erste, die man auf GitHub Pages sieht.
-->

### Use Case

Dieses Implementation Guide beschreibt die standardisierte Erfassung und den Austausch von Arzneimittelallergien zwischen einer Hausarztpraxis und einer Notfallstation. Die Allergieinformationen werden durch eine Ärztin oder einen Arzt dokumentiert und stehen der Notfallstation zur Verfügung, um bekannte Arzneimittelallergien bei der Behandlung und Medikamentenverordnung zu berücksichtigen.

### Scope

Dieses Implementation Guide konzentriert sich auf die Dokumentation von Arzneimittelallergien auf Basis der FHIR-Ressource AllergyIntolerance und des Schweizer Standards CH Core.

Es umfasst die Erfassung des klinischen Status, der Allergieauslöser, der Kritikalität, des Beginns sowie bekannter allergischer Reaktionen. Für die Codierung werden Schweizer ValueSets verwendet.

Nicht Bestandteil dieses Implementation Guides sind die Erfassung anderer Allergiekategorien, die Diagnostik von Allergien oder die automatisierte Überprüfung von Arzneimittelinteraktionen.

### Artefakte

- [DG Arzneimittelallergie](StructureDefinition-dg-medication-allergy.html): FHIR-Profil zur standardisierten Dokumentation von Arzneimittelallergien mit definierten Pflichtfeldern, Datentypen, Wertebereichen und einer zusätzlichen Validierungsregel.

- [Penicillinallergie bei Anna Muster](AllergyIntolerance-PenicillinAllergieAnna.html): Beispiel einer bestätigten Penicillinallergie mit hoher Kritikalität und dokumentierter Urtikaria als allergischer Reaktion.

### Abhängigkeiten

Dieses Implementation Guide baut auf [CH Core 6.0.0](https://fhir.ch/ig/ch-core/6.0.0/) auf. Zusätzlich wird CH Term 3.3.0 für die Schweizer Terminologien verwendet.

### Autorin

Isabel Eigenmann

<p style="font-size:smaller">Erstellt im Lab des Moduls Data Standards in Healthcare, ZHAW, HS26. Kein offizieller Standard.</p>
