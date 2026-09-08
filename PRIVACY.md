# Roamote — Privacy / Datenschutz

Updated / Aktualisiert: 8 September 2026

## English

Roamote connects your own or authorized computer with your paired iPhone or iPad. This policy covers the iOS/iPadOS client.

### Remote sessions and local storage

Roamote processes screen frames, pointer and keyboard input, selected actions, optional clipboard text, pairing identifiers and credentials, saved computer details and Premium entitlement status to provide the features you request. Sessions travel directly between paired devices with application-level end-to-end encryption, over your local network or your separately configured private VPN. Roamote provides no cloud account or public relay and does not send your session content to a developer server. Pairing credentials are kept in Apple Keychain; saved-device records and preferences stay locally until removed.

### Terminal

Terminal uses SSH inside the existing encrypted Roamote connection. The macOS companion forwards its byte stream only to the computer’s local SSH service. You enable macOS Remote Login and authorize your Mac user during setup; full disk access for remote users is optional for protected files. Commands run with that account’s permissions, including sudo when separately authenticated.

The iOS client processes your Mac username and password for SSH authentication. If you choose Save login in Keychain, it stores them in the device-only Keychain until you forget the login or remove the saved computer. Roamote does not log passwords, commands or terminal output. Visible terminal history stays in memory for the open view; the Mac’s shell and operating system may separately save command history and login records according to their settings. The session closes on disconnect or when the iOS app enters the background. Terminal escape sequences cannot read or replace the device clipboard. Explicit paste actions send the text you select to your Mac.

### Advertising and analytics

The free iOS/iPadOS app includes Google Mobile Ads (AdMob) and Google User Messaging Platform for advertising and consent. Ads appear outside screen control and Terminal, with occasional interstitials before manual connections. Google may process IP addresses, device identifiers, approximate location inferred from IP, ad interactions and diagnostics for ad delivery, fraud prevention and measurement. Consent is requested through Google’s consent interface where required; applicable privacy options remain available in Settings. Roamote does not request access to IDFA through App Tracking Transparency. Premium removes ads. See [Google’s partner-site privacy information](https://policies.google.com/technologies/partner-sites). Roamote adds no separate analytics service.

### Purchases

Apple processes the one-time, non-consumable Premium purchase and payment details. There is no subscription or automatic renewal. Roamote checks verified StoreKit entitlement status and sends the active product identifier to the paired companion. The developer receives no payment credentials through the app.

### Permissions and choices

Local Network access discovers and connects paired devices. On macOS, Screen Recording captures the selected display, Accessibility enables input, and Automation may be requested for confirmed system actions. The app does not request camera, microphone, photos, contacts or location access. You can disconnect, remove paired devices, disable clipboard reception or Terminal, forget saved terminal logins, revoke macOS permissions, disable Remote Login, restore purchases or uninstall the app. Removing a paired device terminates its Roamote connection and revokes that pairing. It does not revoke independent access previously configured in macOS Remote Login.

### Support and privacy requests

Use [Roamote support](https://github.com/LilaQ/RemoteTool-iOS-issues/issues). Do not post passwords, terminal output, personal data, pairing codes or diagnostic files in public issues. Roamote is a general utility, not directed to children. This policy will be updated when data handling changes.

## Deutsch

Roamote verbindet deinen eigenen oder einen zur Nutzung freigegebenen Computer mit deinem gekoppelten iPhone oder iPad. Diese Erklärung gilt für den iOS-/iPadOS-Client.

### Fernsteuerung und lokale Speicherung

Roamote verarbeitet Bildschirmbilder, Maus- und Tastatureingaben, gewählte Aktionen, optionalen Zwischenablagetext, Kopplungskennungen und Zugangsdaten, gespeicherte Computer und den Premium-Status für die angeforderten Funktionen. Sitzungen laufen direkt zwischen gekoppelten Geräten, Ende-zu-Ende-verschlüsselt im lokalen Netzwerk oder über dein separat eingerichtetes privates VPN. Roamote bietet kein Cloud-Konto und kein öffentliches Relay und übermittelt Sitzungsinhalte nicht an einen Entwicklerserver. Kopplungsdaten liegen im Apple-Schlüsselbund; Gerätelisten und Einstellungen bleiben bis zum Entfernen lokal gespeichert.

### Terminal

Das Terminal verwendet SSH innerhalb der bestehenden verschlüsselten Roamote-Verbindung. Die macOS-App leitet den Datenstrom ausschließlich an den lokalen SSH-Dienst des Computers weiter. Bei der Einrichtung aktivierst du die entfernte Anmeldung und erlaubst deinem Mac-Benutzer den Zugriff; für geschützte Dateien ist optional voller Festplattenzugriff für entfernte Benutzer nötig. Befehle laufen mit den Rechten dieses Kontos, einschließlich sudo nach gesonderter Authentifizierung.

Der iOS-Client verarbeitet Mac-Benutzername und Passwort zur SSH-Anmeldung. Bei Auswahl von „Anmeldung im Schlüsselbund speichern“ bleiben diese im gerätegebundenen Schlüsselbund, bis du die Anmeldung oder den gespeicherten Computer löschst. Roamote protokolliert keine Passwörter, Befehle oder Terminal-Ausgaben. Der sichtbare Terminal-Verlauf bleibt für die geöffnete Ansicht im Arbeitsspeicher; die Shell und das Betriebssystem des Macs können unabhängig davon Befehlsverläufe und Anmeldeereignisse gemäß ihren Einstellungen speichern. Beim Trennen oder Wechsel der iOS-App in den Hintergrund endet die Sitzung. Terminal-Steuersequenzen dürfen die Zwischenablage des Geräts weder lesen noch ersetzen. Bewusste Einfügeaktionen senden den ausgewählten Text an den Mac.

### Werbung und Analyse

Die kostenlose iOS-/iPadOS-App enthält Google Mobile Ads (AdMob) und Google User Messaging Platform für Werbung und Einwilligungen. Werbung erscheint außerhalb von Bildschirmsteuerung und Terminal; gelegentlich erscheint eine Vollbildanzeige vor einer manuellen Verbindung. Google kann IP-Adressen, Gerätekennungen, aus der IP abgeleitete ungefähre Standorte, Anzeigeninteraktionen und Diagnosedaten für Auslieferung, Betrugsabwehr und Messung verarbeiten. Wo erforderlich, wird eine Einwilligung über Googles Oberfläche eingeholt; die entsprechenden Datenschutzoptionen bleiben in den Einstellungen erreichbar. Roamote fordert keinen IDFA-Zugriff über App Tracking Transparency an. Premium entfernt die Werbung. Siehe [Googles Datenschutzhinweise für Partnerdienste](https://policies.google.com/technologies/partner-sites?hl=de). Roamote bindet keinen zusätzlichen Analysedienst ein.

### Käufe

Apple verarbeitet den einmaligen, nicht verbrauchbaren Premium-Kauf und die Zahlungsdaten. Es gibt kein Abo und keine automatische Verlängerung. Roamote prüft den verifizierten StoreKit-Kaufstatus und sendet die aktive Produktkennung an die gekoppelte Begleit-App. Der Entwickler erhält über die App keine Zahlungszugangsdaten.

### Berechtigungen und Wahlmöglichkeiten

Der Zugriff auf das lokale Netzwerk dient zum Finden und Verbinden gekoppelter Geräte. Unter macOS erfasst die Bildschirmaufnahme den gewählten Bildschirm, Bedienungshilfen ermöglichen Eingaben, und für bestätigte Systemaktionen kann eine Automationsfreigabe erforderlich sein. Die App fordert keinen Zugriff auf Kamera, Mikrofon, Fotos, Kontakte oder Standort an. Du kannst Verbindungen trennen, gekoppelte Geräte entfernen, Zwischenablageempfang oder Terminal deaktivieren, gespeicherte Terminal-Anmeldungen löschen, macOS-Berechtigungen entziehen, die entfernte Anmeldung abschalten, Käufe wiederherstellen oder die App deinstallieren. Das Entfernen eines gekoppelten Geräts beendet dessen Roamote-Verbindung und widerruft die Kopplung. Unabhängig eingerichtete Zugriffe über die entfernte Anmeldung von macOS werden dadurch nicht widerrufen.

### Support und Datenschutzanfragen

Nutze den [Roamote-Support](https://github.com/LilaQ/RemoteTool-iOS-issues/issues). Veröffentliche keine Passwörter, Terminal-Ausgaben, personenbezogenen Daten, Kopplungscodes oder Diagnosedateien in öffentlichen Issues. Roamote ist ein allgemeines Werkzeug und richtet sich nicht an Kinder. Bei Änderungen der Datenverarbeitung wird diese Erklärung aktualisiert.
