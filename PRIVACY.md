# Datenschutzhinweise für Metravilo

Stand: 17. November 2026.

## Anbieter und Kontakt

Herausgebername im Microsoft Store: WolleKr.

Anbieter und Ansprechpartner: Wolfgang Krenn, Karlstr. 18, 08451 Crimmitschau, Deutschland.

Kontakt für Support, Datenschutz und vertrauliche Sicherheitsmeldungen:
[Metravilo@outlook.com](mailto:Metravilo@outlook.com).

Metravilo ist eine lokal arbeitende Desktop-Anwendung. Es gibt kein Metravilo-Benutzerkonto und keinen Metravilo-Cloudspeicher. Zählerstände, Tarife, Zahlungen, Einstellungen, Exporte werden auf dem Gerät des Benutzers gespeichert.

## Netzwerkzugriffe

Metravilo greift nur für Funktionen auf externe Dienste zu, die eine Internetverbindung benötigen:

- Nicht paketverwaltete Entwicklungs- oder portable Builds können GitHub auf neue Versionen prüfen. Microsoft-Store- und Linux-Paketupdates werden durch den jeweiligen Distributionskanal verwaltet.

Bei einem GitHub-Updateabruf wird eine Verbindung zu GitHub hergestellt; dabei fallen technisch unter anderem IP-Adresse und Anfragemetadaten an. Verbrauchsdaten und Zahlungen werden durch diese Updatefunktion nicht übertragen. Für GitHub gilt die [GitHub-Datenschutzerklärung](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). Microsoft Store und die unter Windows verwendete WebView2-Laufzeit sind Microsoft-Komponenten; deren Datenverarbeitung richtet sich nach den jeweiligen Microsoft-Einstellungen und [Datenschutzhinweisen](https://privacy.microsoft.com/privacystatement).

Metravilo betreibt keine eigene Analyse-, Werbe- oder Telemetrieplattform.

## Lokale Daten und Löschung

Unter Windows liegen die Anwendungsdaten standardmäßig unter `%LOCALAPPDATA%\Maelir`. Unter Linux verwendet Metravilo `$XDG_DATA_HOME/maelir` oder ersatzweise `~/.local/share/maelir`. Eine Deinstallation kann lokale Nutzerdaten je nach Paketmanager beibehalten. Sie können diese Verzeichnisse nach einer gewünschten Sicherung selbst löschen.

Die lokale Datenbank und Einstellungen sind nicht durch Metravilo verschlüsselt. Ihr Schutz hängt auch vom Benutzerkonto, Dateizugriffsrechten und gegebenenfalls der Geräteverschlüsselung des Betriebssystems ab. Die eingebettete Weboberfläche kann außerdem lokale WebView-Profildaten speichern; deren Speicherort wird von der Laufzeit beziehungsweise Paketumgebung bestimmt.

Manuell erstellte `.metravilo-backup`-Dateien enthalten die vollständige Datenbank und Einstellungen. Der Speicherort wird vom Nutzer gewählt. Die Dateien sind nicht verschlüsselt. Vor einer Wiederherstellung erstellt die App zusätzlich eine lokale Rücksicherung im Unterordner `backups` des Datenverzeichnisses. Diese Dateien werden nicht automatisch gelöscht. Exporte und manuelle Backups außerhalb des Datenverzeichnisses müssen am gewählten Speicherort separat gelöscht werden.

## Support

Für allgemeine Fragen ist das öffentliche [Metravilo-Supportrepository](https://github.com/WolleKr/Metravilo-Support/issues) vorgesehen. Bitte niemals Datenbanken, Backups, private Exporte, Rechnungen, Anschriften oder vollständige Konfigurationsdateien an einen öffentlichen Fehlerbericht anhängen. Vertrauliche Datenschutzfragen gehören an die oben genannte Kontaktadresse.

Der Besuch der GitHub-Supportseiten ist von der lokalen Nutzung der App getrennt. GitHub verarbeitet dabei eigene Zugriffsdaten; bei einem öffentlichen Issue sind die dort eingegebenen Inhalte öffentlich. Verwende nur die für die Frage notwendigen Angaben und entferne personenbezogene Inhalte aus Screenshots.

Wenn du uns per E-Mail kontaktierst, erhalten wir deine Absenderadresse und den
Inhalt deiner Nachricht. Wir verwenden diese Angaben zur Bearbeitung deiner
Anfrage, gegebenenfalls zur Vertragsanbahnung oder Vertragserfüllung (Art. 6
Abs. 1 Buchst. b DSGVO), andernfalls auf Grundlage unseres berechtigten Interesses
an der Beantwortung von Anfragen (Art. 6 Abs. 1 Buchst. f DSGVO). Der E-Mail-Dienst
wird von Microsoft bereitgestellt. Wir bewahren Nachrichten nur so lange auf,
wie dies zur Bearbeitung und wegen gegebenenfalls bestehender gesetzlicher
Aufbewahrungspflichten erforderlich ist.

Soweit die gesetzlichen Voraussetzungen vorliegen, kannst du gegenüber uns
Auskunft, Berichtigung, Löschung, Einschränkung und Datenübertragbarkeit verlangen
sowie einer Verarbeitung auf Grundlage berechtigter Interessen widersprechen.
Du kannst dich bei einer Datenschutzaufsichtsbehörde beschweren. Die auf deinem
Gerät gespeicherten App-Daten liegen uns nicht automatisch vor; bitte sende für
solche Anliegen keine vollständigen Datenbanken oder Backups per E-Mail.

Die Anbieterangaben stehen auch im [Impressum](IMPRINT.md).

---

# Privacy information for Metravilo

Updated: 17 November 2026.

## Publisher and contact

Microsoft Store publisher display name: WolleKr.

Provider and contact: Wolfgang Krenn, Karlstr. 18, 08451 Crimmitschau, Germany.

Contact for support, privacy and confidential security reports:
[Metravilo@outlook.com](mailto:Metravilo@outlook.com).

Metravilo is a local-first desktop application. It has no Metravilo account and no Metravilo cloud storage. Meter readings, tariffs, payments, settings, and exports remain on the user's device.

## Network access

Non-packaged development or portable builds may check GitHub for updates. Microsoft Store and Linux package updates are managed by their respective distribution channels. Update requests disclose technical connection data such as an IP address and request metadata to GitHub; the app does not send consumption records or payments through this update feature. See [GitHub's privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

Microsoft Store and the Windows WebView2 runtime are Microsoft components, subject to their respective settings and [Microsoft privacy statement](https://privacy.microsoft.com/privacystatement). Metravilo does not operate its own analytics, advertising, or telemetry service.

## Local storage and deletion

Windows data is stored under `%LOCALAPPDATA%\Maelir`. Linux uses `$XDG_DATA_HOME/maelir` or `~/.local/share/maelir`. Depending on the package manager, uninstalling may leave local data in place. After saving any data you want to keep, you can delete these directories yourself.

Metravilo does not encrypt its local database or settings. Protection also depends on your operating-system account, file permissions and any device encryption. The embedded interface may store local WebView profile data at a location determined by the runtime or package environment.

Manual `.metravilo-backup` files contain the complete database and settings and are saved at a location you choose. They are not encrypted. Before restoring, the app creates an additional local recovery backup in the `backups` subdirectory of its data directory. These files are not automatically deleted. Exports and manual backups outside the data directory must be deleted separately from their chosen locations.

## Support

General questions can be posted to the public [Metravilo-Support issues](https://github.com/WolleKr/Metravilo-Support/issues). Do not attach databases, backups, private exports, invoices, addresses or complete configuration files. Use the contact address above for confidential privacy requests.

Visiting GitHub support pages is separate from local app use. GitHub processes its own access data, and anything you post in a public issue is public. Include only information necessary for your question and remove personal data from screenshots.

When you contact us by email, we receive your sender address and message content.
We use these details to handle your request, where applicable to take steps before
entering into a contract or perform a contract (GDPR Article 6(1)(b)), otherwise
based on our legitimate interest in answering requests (Article 6(1)(f)). Microsoft
provides the email service. Messages are retained only as needed to handle the
request and meet any applicable statutory retention obligations.

Subject to applicable conditions, you may request access, rectification, erasure,
restriction and portability, and object to processing based on legitimate
interests. You may complain to a data protection supervisory authority. We do not
automatically receive app data stored on your device; do not send complete
databases or backups with these requests.

See also the [legal notice](IMPRINT.md).
