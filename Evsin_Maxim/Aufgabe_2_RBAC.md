# Role Based Access Control (RBAC)

## Begriffserklärung

**Role Based Access Control**, kurz **RBAC**, ist ein Berechtigungsmodell, das den Zugriff auf digitale Ressourcen über Rollen organisiert. Dabei steht nicht die einzelne Person im Mittelpunkt, sondern ihre Funktion im System. Eine Rolle entspricht dabei typischerweise einer beruflichen Aufgabe oder Verantwortung – etwa „Netzwerkadministrator“ oder „Datenanalyst“.

Statt jeder Person individuell Rechte zuzuweisen, wird die Rolle mit den nötigen Berechtigungen ausgestattet. Benutzer:innen erhalten dann einfach die passende Rolle – was nicht nur übersichtlicher ist, sondern auch den Verwaltungsaufwand massiv reduziert.

## In welchem Kontext wird RBAC eingesetzt?

RBAC begegnet uns heute fast überall, wo mehrere Nutzer:innen kontrolliert auf Systeme zugreifen: in Unternehmen, in der Cloud, in DevOps-Umgebungen oder auch bei Softwareprodukten mit mehreren Benutzergruppen.

Ein paar typische Beispiele:

- **Cloud-Infrastrukturen** (z. B. Azure, AWS, Google Cloud): Kontrolle darüber, wer welche Ressourcen erstellen, verändern oder löschen darf.
- **Kubernetes-Cluster**: Zuweisung von Rollen für Entwickler:innen, Operatoren oder Admins.
- **Unternehmensnetzwerke**: Durchsetzung von Zugriffsregeln auf Ordner, Systeme oder Drucker über Gruppenrichtlinien (z. B. via Active Directory).
- **Applikationen mit Admin-/User-Oberflächen**: z. B. bei Content-Management-Systemen.

RBAC ist vor allem dort sinnvoll, wo:

- viele Personen beteiligt sind,
- Berechtigungen regelmäßig angepasst werden müssen oder
- regulatorische Anforderungen gelten (z. B. ISO 27001, DSGVO).

## Grundprinzip und Funktionsweise

RBAC arbeitet nach dem Prinzip: **Benutzer → Rolle → Berechtigung**. Die Struktur lässt sich in drei Ebenen unterteilen:

- **Benutzer:innen** (User): konkrete Personen oder Dienste
- **Rollen** (Role): definieren Funktionen im System, z. B. „Redakteur“ oder „Systemadmin“
- **Rechte** (Permission): legen fest, welche Aktionen erlaubt sind, z. B. „Datei löschen“ oder „Einstellungen ändern“

Ein Benutzer erhält über seine Rolle die zugehörigen Berechtigungen. So wird das Zugriffsmanagement deutlich einfacher.

### Beispiel

```
Nutzerin: Max
Rolle: Datenanalyst
Rechte: Abfragen ausführen, Reports exportieren
```

Wenn Max das Unternehmen verlässt, genügt es, ihm die Rolle zu entziehen – alle damit verbundenen Rechte werden automatisch entfernt.

## Vorteile und Nutzen

RBAC ist nicht nur ein Ordnungsinstrument – es bringt auch konkrete Vorteile:

- **Klarheit**: Wer darf was? Rollen geben eine klare Antwort.
- **Sicherheit**: Rechte lassen sich auf das Notwendigste beschränken („Least Privilege“).
- **Skalierbarkeit**: Neue Nutzer:innen bekommen Rollen statt individueller Rechte.
- **Zeitersparnis**: Rollen lassen sich wiederverwenden und leicht aktualisieren.
- **Compliance**: Einhaltung von Standards und Prüfanforderungen wird erleichtert.

## Fazit

RBAC ist ein robustes, gut etabliertes Modell, das in modernen Systemen eine entscheidende Rolle spielt. Gerade in Zeiten von Cloud Computing, DevOps und zunehmender Sicherheitsanforderungen ist es essenziell, Zugriffsrechte strukturiert zu vergeben.

Indem RBAC Verantwortung über Rollen abbildet, schafft es Transparenz und Effizienz – und ermöglicht dabei eine sichere Steuerung von Berechtigungen in komplexen IT-Landschaften.
