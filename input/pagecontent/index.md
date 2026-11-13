<!--
  Schritt 7: Startseite eures IG
  Ersetzt die TODOs durch eigenen Text. Markdown ist erlaubt.
  Diese Seite ist die erste, die man auf GitHub Pages sieht.
-->

### Use Case

IG um Allergien auf Medikamente abzubilden. Erfassung durch Arzt/Ärztin in Arztpraxis mit kritikalität der Reaktion. Daten könnten beispielsweise von anderen Leistungserbringern z.B. in Notsituation im ER abgerufen werden, um Falschbehandlungen zu vermeiden


### Scope

Dieses IG beschränkt sich auf Allergien gegen Arzneimittel. Es umfasst den klinischen Status, die Kritikalität, den Beginn der Allergie, die erfassende Person und mögliche Reaktionen.

Andere Allergien, welche die Person hat, sind Out of scope für dieses IG

### Artefakte

* [DG Arzneimittelallergie](StructureDefinition-dg-medication-allergy.html): Definiert das FHIR-Profil zur strukturierten Erfassung von Arzneimittelallergien basierend auf CH Core.
* [Penicillin Allergie](AllergyIntolerance-PenicillinAllergieAnna.html): Zeigt ein Beispiel einer bestätigten Penicillinallergie bei Anna Muster mit niedriger Kritikalität und Nesselsucht als Reaktion.

### Abhängigkeiten

Dieses IG baut auf [CH Core 6.0.0](https://fhir.ch/ig/ch-core/6.0.0/) auf.

### Autorin oder Autor

Oliver Sturzenegger

<p style="font-size:smaller">Erstellt im Lab des Moduls Data Standards in Healthcare, ZHAW, HS26. Kein offizieller Standard.</p>
