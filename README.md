# Programmierkonventionen

Um eine hohe Codequalität aufrechtzuerhalten und sicherzustellen, dass unsere Codebasis wartbar bleibt, halten wir uns an einen Satz von Programmierkonventionen. Bitte folgen Sie diesen Richtlinien für alle Beiträge.

## Verbranchungsstrategie

- **Keine direkten Pushes auf `dev` oder `master`**: Direkte Pushes auf die `dev`- und `master`-Branches sind strengstens verboten. Diese Branches werden geschützt und können nur über Pull-Requests aktualisiert werden.
- **Feature-Branches**: Jedes neue Feature sollte in einem separaten branch entwickelt werden, der von der neuesten `dev`-Version abgebrancht ist.
- **Benennungskonvention für Branches**: Benennen Sie Ihre Branches mit einem Präfix, das die Art der Aufgabe beschreibt, gefolgt von einem Schrägstrich und einer kurzen Beschreibung des Features oder der Korrektur. Beispielhafte Formate umfassen:
  - `feature/add-login`
  - `bugfix/resolve-login-issue`
  - `refactor/improve-login-performance`

## Pull Requests (PRs)

- **Pull Requests für alle Features**: Alle Änderungen an der Codebasis sollten über Pull-Requests eingereicht werden. Dies schließt Fehlerbehebungen, Verbesserungen und Feature-Ergänzungen ein.
- **Review-Prozess**: Jeder Pull Request muss von mindestens einem Teammitglied und Protect 7 vor dem Zusammenführen überprüft werden. Dies stellt die Codequalität und die Einhaltung der Projektstandards sicher.
- **PR-Beschreibungen**: Fügen Sie eine detaillierte Beschreibung dessen hinzu, was der PR erreicht. Bilder sind ebenfalls willkommen. Verlinken Sie auf relevante Issues oder Tickets.

## Programmierstandards

- **Linting**: Führen Sie immer den Linter des Projekts durch, bevor Sie Ihren Code einreichen. Halten Sie sich an die im Projekt festgelegten Linting-Regeln, um Konsistenz zu gewährleisten.
- **Testing**: Schreiben Sie Tests für alle neuen Codes und Änderungen. Stellen Sie sicher, dass die gesamte Testsuite bestanden wird, bevor Sie einen Pull Request einreichen.
- **Vermeiden Sie häufige Fehler**:
  - Commiten Sie keinen auskommentierten Code. Wenn er nicht benötigt wird, entfernen Sie ihn. (alle Kommentare werden im Master-branch entfernt)
  - Befolgen Sie bewährte Praktiken für die Fehlerbehandlung. Unterdrücken oder ignorieren Sie keine Fehler.
  - Verwenden Sie aussagekräftige Variablen- und Funktionsnamen. Vermeiden Sie Ein-Buchstaben-Namen, außer in kurzen, lokalen Bereichen.
- **Funktionale Programmierung**: Wenden Sie die Prinzipien der funktionalen Programmierung wann immer möglich an.

## Bewährte Praktiken

- **Code-Review**: Nehmen Sie den Code-Review-Prozess ernst. Bieten Sie konstruktives Feedback und seien Sie offen dafür, Feedback von anderen zu erhalten.
- **Kontinuierliche Integration (CI)**: Nutzen Sie CI-Tools, um das Testen und Linting zu automatisieren. Nur Code, der alle CI-Tests besteht, sollte zusammengeführt werden.
- **Dokumentation**: Dokumentieren Sie Ihren Code. Verwenden Sie Kommentare, wo nötig, um das „Warum“ hinter bestimmten Entscheidungen zu erklären, nicht nur das „Wie“.

## Commit-Nachrichten

- Schreiben Sie klare und aussagekräftige Commit-Nachrichten. Eine gute Commit-Nachricht sollte beschreiben, was sich geändert hat und warum.
- Verwenden Sie den Imperativ für die Zusammenfassungszeile.

## Fazit

Indem wir diesen Konventionen folgen, können wir sicherstellen, dass unsere Codebasis sauber, verständlich und wartbar ist. Lassen Sie uns zusammenarbeiten, um etwas Großartiges zu bauen!
