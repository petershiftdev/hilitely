# Datenschutz — Hilitely

**Zuletzt aktualisiert:** 8. November 2026

Diese Richtlinie beschreibt, wie die Erweiterung **Hilitely** für Chrome und Firefox („die Erweiterung“) mit Informationen umgeht.

## Wer die Erweiterung bereitstellt

Die Erweiterung wird von **PeterShift** veröffentlicht.
Kontakt: **petershift.dev@gmail.com**

## Was die Erweiterung tut

Auf einer Website, die Sie einschalten, markiert die Erweiterung eine von Ihnen gewählte Textstelle und findet diese Markierung nach dem Neuladen oder nach einer Änderung der Seite wieder: anhand der Wörter, nicht anhand ihrer Position im Layout. Notizen, Tags und eine Zitatbibliothek bleiben auf diesem Computer.

## Was die Erweiterung speichert

Wenn Sie Text markieren, speichert die Erweiterung einen Eintrag auf Ihrem Computer:

- den zitierten Text und etwa 100 Zeichen davor und danach, damit die Markierung wiedergefunden werden kann;
- die Adresse der Seite, ihre kanonische Adresse, falls die Seite eine angibt, und den Seitentitel;
- die Farbe sowie eine Notiz und Tags, falls Sie welche eingeben;
- wann die Markierung erstellt und geändert wurde und ob sie beim letzten Mal auf der Seite gefunden wurde.

Einstellungen bleiben ebenfalls auf diesem Computer: die zuletzt gewählte Farbe, ob der Cursor in das Notizfeld gesetzt wird, wie die Bibliothek Websites sortiert und welche aktivierten Websites Sie ausgeschaltet haben.

## Wohin die Daten gehen

Nirgendwohin. Markierungen bleiben im Browser, in der eigenen Datenbank der Erweiterung auf diesem Computer. Die Erweiterung hat keinen Server, kein Konto und keine Analyse. Sie stellt keine Netzwerkanfragen. Wir erhalten Ihre Markierungen, Notizen und die Adressen der Seiten, die Sie lesen, nicht.

## Welche Websites sie lesen kann

Die Erweiterung verlangt nicht, jede Website zu lesen. Sie läuft nur auf Websites, die Sie über das Symbol in der Symbolleiste einzeln einschalten, über den eigenen Berechtigungsdialog des Browsers. In Chrome ist ein Host an einem ungewöhnlichen Port eine eigene Website. In Firefox gilt die Berechtigung für einen Host auf jedem Port. Bis dahin fügt sie der Seite nichts hinzu.

Eine Website auszuschalten setzt sie auf Pause. Die Markierungen verschwinden aus den offenen Tabs dieser Website, und das Skript startet dort erst wieder, wenn Sie die Website einschalten. Die Berechtigung des Browsers bleibt bestehen, deshalb fragt das erneute Einschalten nicht ein zweites Mal. „Remove access to this site“ entzieht die Berechtigung. Wenn Sie diese Website das nächste Mal einschalten, fragt der Browser erneut. Gespeicherte Zitate bleiben in beiden Fällen in der Bibliothek.

## Sicherungen

Eine Sicherungsdatei entsteht nur, wenn Sie Download backup wählen. Sie wird dort gespeichert, wo Ihr Browser Downloads ablegt. Der Import liest eine Datei, die Sie auswählen. Beides wird nirgendwohin hochgeladen.

## Daten löschen

Löschen Sie eine Markierung auf der Seite oder in der Bibliothek, oder verwenden Sie Delete all on this site in der Bibliothek. Wenn Sie die Erweiterung entfernen, löscht die übliche Bereinigung des Browsers alle ihre lokalen Daten.

## Berechtigungen

| Berechtigung | Warum sie angefordert wird |
| --- | --- |
| `storage` | Speichert Einstellungen auf diesem Computer: die letzte Markierungsfarbe, ob der Cursor in das Notizfeld gesetzt wird, welche aktivierten Websites Sie ausgeschaltet haben und wie die Bibliothek Websites sortiert. Zitate liegen in der eigenen Datenbank der Erweiterung; diese Berechtigung speichert sie nicht. |
| `activeTab` | Wenn Sie auf das Symbol in der Symbolleiste klicken, liest das Fenster die Adresse des aktuellen Tabs, um den Schalter für diese Website anzuzeigen und die Markierungen der Seite durchzugehen. |
| `scripting` | Startet die Markierung im aktuellen Tab direkt nach dem Einschalten der Website und in bereits geöffneten Tabs dieser Website, ohne die Seite neu zu laden. Beim Ausschalten entfernt sie die Markierungen aus diesen Tabs. |
| Zugriff auf Websites | Wird bei der Installation nicht erteilt. Der Browser fragt jeweils eine Website, wenn Sie sie zum ersten Mal einschalten. In Chrome ist ein Host an einem ungewöhnlichen Port eine eigene Website. In Firefox gilt die Berechtigung für einen Host auf jedem Port. Die Markierung läuft nur auf Websites, die Sie erlaubt und nicht ausgeschaltet haben. Ausschalten beendet sie dort und behält die Berechtigung. „Remove access to this site“ entzieht sie. |

## Fremder Code

Die Erweiterung führt nur die lokalen Dateien aus ihrem Paket aus. Sie lädt kein JavaScript aus dem Netz und führt keines aus.

## Eingeschränkte Nutzung

Die Daten dienen nur dazu, Ihre Markierungen wieder anzuzeigen und sie in der Bibliothek aufzulisten. Sie werden nicht verkauft, nicht an Dritte weitergegeben, nicht für Werbung oder zur Beurteilung der Kreditwürdigkeit verwendet, und niemand liest sie. Die Nutzung entspricht der Chrome Web Store User Data Policy (https://developer.chrome.com/docs/webstore/program-policies/limited-use), einschließlich der Limited-Use-Anforderungen.

## Änderungen

Wenn eine spätere Version beginnt, Daten irgendwohin zu senden, sagt diese Richtlinie das, bevor diese Version erscheint, und die Erweiterung fragt Sie zuerst.

## Kontakt

Fragen zu dieser Richtlinie: **petershift.dev@gmail.com**
