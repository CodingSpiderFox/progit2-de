#  Pro Git Übersetzung (2. Edition)

Die Übersetzungen werden dezentral verwaltet. Jedes Übersetzungsteam pflegt sein eigenes Projekt. Jede Übersetzung befindet sich in einem eigenen Repository, das Pro Git-Team zieht einfach die Änderungen und baut sie nach Fertigstellung in die Website https://git-scm.com ein.

## Allgemeine Hinweise zur Übersetzung von Pro Git

Pro Git ist ein Buch über ein technisches Werkzeug, daher ist die Übersetzung im Vergleich zu einer nicht-technischen Übersetzung schwierig.

Die folgenden Richtlinien sollen Ihnen auf Ihrem Weg helfen:
* Bevor Sie beginnen, lesen Sie das gesamte Git Pro Buch auf Englisch, damit Sie den Inhalt kennen und mit dem verwendeten Stil vertraut werden.
* Stellen Sie sicher, dass Sie über gute Grundkenntnisse in git verfügen, so dass die Erklärung der Fachbegriffe möglich ist.
* Halten Sie sich an einen gemeinsamen Stil und ein gemeinsames Format für die Übersetzung.
* Lesen und verstehen Sie unbedingt die Grundlagen der [Asciidoc-Formatierung](https://asciidoctor.org/docs/asciidoc-syntax-quick-reference/). Die Nichteinhaltung der asciidoc-Syntax kann zu Problemen beim Erstellen/Kompilieren der für das Buch benötigten pdf-, epub- und html-Dateien führen.

## Das Buch in eine andere Sprache übersetzen

### Mithilfe bei einem bestehenden Projekt

* Suchen Sie in der folgenden Tabelle nach einem bereits vorhandenen Projekt.
* Gehen Sie auf die GitHub-Projektseite.
* Eröffnen Sie ein Issue, stellen Sie sich vor und fragen Sie, wo Sie helfen können.

| Sprache     | GitHub Projektseite     |
| :------------- | :------------- |
| العربية | [progit2-ar/progit2](https://github.com/progit2-ar/progit2) |
| Беларуская  | [progit/progit2-be](https://github.com/progit/progit2-be) |
| български език | [progit/progit2-bg](https://github.com/progit/progit2-bg) |
| Čeština    | [progit-cs/progit2-cs](https://github.com/progit-cs/progit2-cs) |
| English    | [progit/progit2](https://github.com/progit/progit2) |
| Español    | [progit/progit2-es](https://github.com/progit/progit2-es) |
| فارسی | [progit2-fa/progit2](https://github.com/progit2-fa/progit2) |
| Français   | [progit/progit2-fr](https://github.com/progit/progit2-fr) |
| Deutsch    | [progit/progit2-de](https://github.com/progit/progit2-de) |
| Ελληνικά   | [progit2-gr/progit2](https://github.com/progit2-gr/progit2) |
| Indonesian | [progit/progit2-id](https://github.com/progit/progit2-id) |
| Italiano   | [progit/progit2-it](https://github.com/progit/progit2-it) |
| 日本語   | [progit/progit2-ja](https://github.com/progit/progit2-ja) |
| 한국어   | [progit/progit2-ko](https://github.com/progit/progit2-ko) |
| Македонски | [progit2-mk/progit2](https://github.com/progit2-mk/progit2) |
| Bahasa Melayu| [progit2-ms/progit2](https://github.com/progit2-ms/progit2) |
| Nederlands | [progit/progit2-nl](https://github.com/progit/progit2-nl) |
| Polski | [progit2-pl/progit2-pl](https://github.com/progit2-pl/progit2-pl) |
| Português (Brasil) | [progit2-pt-br/progit2](https://github.com/progit2-pt-br/progit2) |
| Русский   | [progit/progit2-ru](https://github.com/progit/progit2-ru) |
| Slovenščina  | [progit/progit2-sl](https://github.com/progit/progit2-sl) |
| Српски   | [progit/progit2-sr](https://github.com/progit/progit2-sr) |
| Tagalog   | [progit2-tl/progit2](https://github.com/progit2-tl/progit2) |
| Türkçe   | [progit/progit2-tr](https://github.com/progit/progit2-tr) |
| Українська| [progit/progit2-uk](https://github.com/progit/progit2-uk) |
| Ўзбекча  | [progit/progit2-uz](https://github.com/progit/progit2-uz) |
| 简体中文  | [progit/progit2-zh](https://github.com/progit/progit2-zh) |
| 正體中文  | [progit/progit2-zh-tw](https://github.com/progit/progit2-zh-tw) |

### Eine neue Übersetzung beginnen

Wenn es noch kein Projekt für Ihre Sprache gibt, können Sie eine eigene Übersetzung starten.

Grundlage Ihrer Arbeit ist die zweite Ausgabe des Buches, die [hier](https://github.com/progit/progit2) verfügbar ist. So sollten Sie vorgehen:
 1. Wählen Sie den richtigen [ISO 639-Code](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) für Ihre Sprache.
 1. Erstellen Sie eine [GitHub-Organisation](https://help.github.com/articles/creating-a-new-organization-from-scratch/), z.B. `progit2-[your code]` auf GitHub.
 1. Erstellen Sie ein Projekt ``progit2``.
 1. Kopieren Sie die Struktur von progit/progit2 (dieses Projekt) in Ihr Projekt und beginnen Sie mit der Übersetzung.

### Den Bearbeitungsstatus Ihrer Übersetzung aktualisieren

Auf https://git-scm.com sind die Übersetzungen in drei Kategorien eingeteilt. Sobald Sie eine dieser Levels erreicht haben, kontaktieren Sie die Betreuer von https://git-scm.com/, damit sie die Änderungen übernehmen können.

| Kategorie | fertiggestellt     |
| :------------- | :------------- |
| Übersetzung begonnen für | Einführung übersetzt, sonst nicht viel. |
| unvollständige Übersetzungen verfügbar in | übersetzt bis Kapitel 6. |
| Vollständige Übersetzung verfügbar in | das Buch ist (fast) vollständig übersetzt. |

## Kontinuierliche Integration mit Travis CI

Travis CI ist ein Dienst für [kontinuierliche Integration](https://en.wikipedia.org/wiki/Continuous_integration), der in GitHub integriert werden kann. Travis CI wird verwendet, um sicherzustellen, dass eine Pull-Anforderung den Build oder die Kompilierung nicht unterbricht. Travis CI kann auch kompilierte Versionen des Buches zur Verfügung stellen.

Die Einrichtung von Travis CI erfordert eine administrative Kontrolle über das Repository.

### Registrierung für die kontinuierliche Integration von Travis

1. Ein Travis-Konto [hier](https://travis-ci.org/) einrichten.
1. Registrieren Sie Ihr Projekt in Travis.
Weitere Informationen finden Sie in der [Travis-Dokumentation](https://docs.travis-ci.com/).

### Einrichten Ihres Repositorys für eine kontinuierliche Integration

Travis CI scannt das Stammverzeichnis Ihres Projekts nach einer Datei mit dem Namen `.travis.yml` und folgt dem darin enthaltenen „Rezept“. Die gute Nachricht ist: Es gibt bereits eine funktionierende `.travis.yml` Datei im Pro Git 2 Quellcode [hier](https://raw.githubusercontent.com/progit/progit2-pub/master/travis.yml).
Kopieren Sie diese Datei und legen Sie sie in Ihr Arbeitsverzeichnis. Commitieren Sie die .yml-Datei und verschieben Sie sie in Ihr Übersetzungs-Repository; das sollte eine Kompilierung und eine Überprüfung des Inhalts des Buches auslösen.

## Einrichtung einer Publikationskette für E-Books

Das ist eine technische Sache, bitte kontaktieren Sie @jnavila, um mit der Veröffentlichung von epub zu beginnen.

## Abgesehen von Pro Git

Die Übersetzung des Buches ist der erste Schritt. Sobald das fertig ist, können Sie die Benutzeroberfläche von Git selbst übersetzen.

Diese Aufgabe erfordert ein besseres technisches Wissen über das Tool als das Buch. Hoffentlich können Sie nach der Übersetzung des gesamten Buchinhalts die in der Anwendung verwendeten Begriffe verstehen. Wenn Sie sich der Aufgabe technisch gewachsen fühlen, ist das Repo [hier](https://github.com/git-l10n/git-po) und Sie müssen nur der [Anleitung](https://github.com/git-l10n/git-po/blob/master/po/README).

Beachten Sie jedoch, dass

 * Sie speziellere Tools verwenden müssen, um die Lokalisierungs-Po-Dateien zu handhaben (z.B. um sie mit [poedit](https://poedit.net/) zu bearbeiten) und sie zusammenzuführen. Möglicherweise müssen Sie git kompilieren, um Ihre Arbeit zu überprüfen.
 * ein grundlegendes Verständnis über die Übersetzung von Anwendungen erforderlich ist, die sich deutlich von der Übersetzung von Büchern unterscheidet.
 * das Core-Projekt Git strengere [Vorschriften](https://github.com/git-l10n/git-po/blob/master/Documentation/SubmittingPatches) für die Annahme von Beiträgen anwendet. Achten Sie darauf, diese einzuhalten.
