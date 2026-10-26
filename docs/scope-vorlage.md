# Scope – Autorisierter WLAN-Sicherheitstest

> VORLAGE – nicht hier ausfüllen. Pro Auftrag eine Kopie ziehen.
> Ohne ausgefüllte und beidseitig bestätigte Erlaubnis wird nicht getestet.

## 1. Beteiligte
- Tester: ______________________
- Auftraggeber (Eigentümer des Netzes): ______________________  (Kontakt: __________)
- Verhältnis (Freund/Bekannter/Verwandter): ______________________
- Ort des Netzwerks: ______________________

## 2. Autorisierung
- [ ] Auftraggeber ist verfügungsberechtigt (eigener Anschluss, eigener Router)
- [ ] Erlaubnis liegt schriftlich vor (Foto/Chat mit Datum)
- [ ] Erlaubnis umfasst: Scan, Handshake-Mitschnitt, Passwort-Rückrechnung SEINES Netzes
- Ablage Nachweis: erlaubnis.jpg (im selben Ordner, nie ins Repo!)
- Datum Erlaubnis: __________   Gültig bis: __________

## 3. Ziel (In-Scope) – nur dieses eine Netz
- SSID: ______________________
- BSSID (Router-MAC): ______________________
- Band/Kanal: ______________________

## 4. NICHT erlaubt (Out-of-Scope)
- Jedes andere WLAN in Reichweite (auch Nachbarnetze)
- Deauth gegen fremde Geräte
- Zugriff auf Daten/Dienste/Geräte im Netz
- Dauerhafte Störung des Netzes

## 5. Methoden
1. Passiver Scan – nur Ziel-Netz
2. WPA2-Handshake-Mitschnitt (ggf. Deauth gegen EIGENES Testgerät des Auftraggebers)
3. Offline-Rückrechnung gegen Wortliste
4. Keine Online-Brute-Force gegen den Router
Hardware: externer WLAN-Adapter mit Monitor-Mode (internes Pi-5-WLAN kann das nicht)

## 6. Zeitfenster
- Datum/Zeitraum: __________
- Auftraggeber erreichbar: [ ] ja

## 7. Umgang mit Ergebnissen
- Passwort nur dem Auftraggeber mitteilen, nirgends speichern/teilen
- Mitschnitte danach löschen; fürs Portfolio nur anonymisiert (ohne echtes PW/SSID/MAC)
- Kurzbericht für den Auftraggeber: was war angreifbar, was empfehle ich

## 8. Rechtlicher Rahmen
- Nur eigenes Netz des Auftraggebers mit schriftlicher Erlaubnis
- Fremde Netze = strafbar (§§ 202a–202c, § 303b StGB)
- Im Zweifel: nicht testen

Tester: ______________, Datum ______, Unterschrift ______
Auftraggeber: ______________, Datum ______, Unterschrift ______
