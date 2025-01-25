# 👋 Die Grundlagen von GitHub

## 🤓 Kursübersicht und Lernziele

Das Ziel dieses Kurses ist es, Ihnen eine kurze Einführung in GitHub zu geben. Wir stellen Ihnen auch Materialien für weiterführendes Lernen zur Verfügung und geben Ihnen einige Ideen, wie Sie auf unserer Plattform starten können. 🚀

## 🐙 Git und GitHub

Git ist ein **verteiltes Versionskontrollsystem (VCS)**, das ein nützliches Werkzeug ist, um Änderungen an Ihrem Code einfach zu verfolgen, zusammenzuarbeiten und zu teilen. Mit Git können Sie die Änderungen, die Sie an Ihrem Projekt vornehmen, verfolgen, sodass Sie immer eine Aufzeichnung dessen haben, woran Sie gearbeitet haben, und bei Bedarf leicht zu einer älteren Version zurückkehren können. Es erleichtert auch die Zusammenarbeit – Gruppen von Personen können gemeinsam am selben Projekt arbeiten und ihre Änderungen zu einer finalen Version zusammenführen!

GitHub ist eine Möglichkeit, die gleichen Funktionen von Git online mit einer benutzerfreundlichen Oberfläche zu nutzen. Es wird in der gesamten Softwarewelt und darüber hinaus genutzt, um zusammenzuarbeiten und die Historie von Projekten zu pflegen.

GitHub ist die Heimat einiger der fortschrittlichsten Technologien der Welt. Egal, ob Sie Daten visualisieren oder ein neues Spiel entwickeln, es gibt eine ganze Community und eine Reihe von Tools auf GitHub, die Sie zum nächsten Schritt bringen können. Dieser Kurs beginnt mit den Grundlagen von GitHub, aber wir werden später tiefer in die Materie eintauchen.

## 🐙 Verständnis des GitHub-Workflows

Der GitHub-Workflow ist ein schlanker Arbeitsprozess, der es Ihnen ermöglicht, an Ihren Projekten zu experimentieren und zusammenzuarbeiten, ohne das Risiko einzugehen, Ihre bisherigen Arbeiten zu verlieren.

### Repositories

Ein Repository ist der Ort, an dem Ihre Projektarbeit stattfindet – denken Sie daran wie an Ihren Projektordner. Es enthält alle Dateien Ihres Projekts und die Versionshistorie. Sie können alleine in einem Repository arbeiten oder andere einladen, mit Ihnen an diesen Dateien zu arbeiten.

### Klonen

Wenn ein Repository mit GitHub erstellt wird, wird es remote in der ☁️ gespeichert. Sie können ein Repository klonen, um eine lokale Kopie auf Ihrem Computer zu erstellen, und dann Git verwenden, um die beiden zu synchronisieren. Dies erleichtert es, Probleme zu beheben, Dateien hinzuzufügen oder zu entfernen und größere Änderungen vorzunehmen. Sie können auch das Bearbeitungswerkzeug Ihrer Wahl verwenden, anstatt die GitHub-Oberfläche zu nutzen. Das Klonen eines Repositories lädt außerdem alle Repository-Daten herunter, die GitHub zu diesem Zeitpunkt hat, einschließlich aller Versionen jeder Datei und jedes Ordners des Projekts! Dies kann hilfreich sein, wenn Sie mit Ihrem Projekt experimentieren und dann feststellen, dass Ihnen eine frühere Version besser gefallen hat.

Mehr über das Klonen erfahren Sie im Artikel ["Ein Repository klonen"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).

### Committen und Pushen

**Committen** und **Pushen** sind die Schritte, mit denen Sie die Änderungen, die Sie auf Ihrem lokalen Computer vorgenommen haben, in das Remote-Repository auf GitHub hochladen können. So können Ihre Dozenten und/oder Teamkollegen Ihre neuesten Arbeiten sehen, sobald Sie bereit sind, diese zu teilen. Sie können einen Commit durchführen, wenn Sie Änderungen an Ihrem Projekt vorgenommen haben, die Sie als „Checkpoint“ speichern möchten. Sie können auch eine hilfreiche **Commit-Nachricht** hinzufügen, um sich oder Ihrem Team die vorgenommenen Änderungen in Erinnerung zu rufen (z. B. „README mit Informationen zu unserem Projekt hinzugefügt“).

Sobald Sie einen oder mehrere Commits haben, die Sie Ihrem Repository hinzufügen möchten, können Sie den Push-Befehl verwenden, um diese Änderungen in Ihr Remote-Repository hochzuladen. Committen und Pushen mag anfangs ungewohnt sein, aber wir versprechen Ihnen, dass Sie sich daran gewöhnen werden. 🙂

### Repositories

Wie bereits erwähnt, sind Repositories der Ort, an dem Ihre Projektarbeit stattfindet. Lassen Sie uns jedoch ein wenig mehr über die Details sprechen! Wenn Sie mehr mit GitHub arbeiten, werden Sie viele Repositories haben, was anfangs verwirrend sein kann. Zum Glück hilft Ihnen Ihr ["GitHub-Dashboard"](https://docs.github.com/en/github/setting-up-and-managing-your-github-user-account/about-your-personal-dashboard), um einfach durch Ihre Repositories zu navigieren und nützliche Informationen über sie zu sehen. Stellen Sie sicher, dass Sie eingeloggt sind, um darauf zugreifen zu können!

Repositories enthalten auch **READMEs**. Sie können eine README-Datei zu Ihrem Repository hinzufügen, um anderen zu erklären, warum Ihr Projekt nützlich ist, was sie mit Ihrem Projekt tun können und wie sie es verwenden können. Wir verwenden dieses README, um Ihnen zu zeigen, wie Sie Git und GitHub lernen können. 😄

Mehr über Repositories erfahren Sie im Artikel ["Erstellen, Klonen und Archivieren von Repositories"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-repositories) und ["Über READMEs"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-readmes).

### Branches

Sie können Branches auf GitHub verwenden, um Arbeiten zu isolieren, die Sie noch nicht in Ihr finales Projekt einfügen möchten. Branches ermöglichen es Ihnen, Funktionen zu entwickeln, Fehler zu beheben oder sicher mit neuen Ideen zu experimentieren, ohne den Hauptzweig Ihres Repositories zu beeinflussen. Normalerweise erstellen Sie einen neuen Branch vom Standard-Branch Ihres Repositories – `main`. Dies erstellt eine neue Arbeitskopie Ihres Repositories, in der Sie experimentieren können. Sobald Ihre Änderungen von einem Teamkollegen überprüft wurden oder Sie mit ihnen zufrieden sind, können Sie Ihre Änderungen in den Standard-Branch Ihres Repositories zusammenführen.

Mehr über Branches erfahren Sie im Artikel ["Über Branches"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-branches).

### Forks

Ein Fork ist eine weitere Möglichkeit, ein Repository zu kopieren, wird jedoch normalerweise verwendet, wenn Sie zu einem anderen Projekt beitragen möchten. Das Forken eines Repositories ermöglicht es Ihnen, Änderungen vorzunehmen, ohne das Originalprojekt zu beeinflussen. Dies ist besonders beliebt, wenn Sie zu Open-Source-Projekten beitragen!

Mehr über Forks erfahren Sie im Artikel ["Ein Repository forken"](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo).

### Pull Requests

Wenn Sie mit Branches arbeiten, können Sie einen Pull Request verwenden, um anderen die von Ihnen geplanten Änderungen mitzuteilen und um deren Feedback zu bitten. Sobald ein Pull Request geöffnet ist, können Sie die potenziellen Änderungen mit Ihren Mitwirkenden besprechen und bei Bedarf weitere Änderungen vornehmen. Sie können bestimmte Personen als Reviewer für Ihren Pull Request hinzufügen, um zu zeigen, dass Sie ihr Feedback zu Ihren Änderungen wünschen! Sobald ein Pull Request bereit ist, kann er in den Haupt-Branch Ihres Repositories zusammengeführt werden.

Mehr über Pull Requests erfahren Sie im Artikel ["Über Pull Requests"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests).

### Issues

Issues sind eine Möglichkeit, Verbesserungen, Aufgaben oder Fehler für Ihre Arbeiten auf GitHub zu verfolgen. Sie sind eine großartige Möglichkeit, alle Aufgaben zu organisieren, an denen Sie für Ihr Projekt arbeiten möchten, und anderen mitzuteilen, woran Sie planen zu arbeiten. Sie können Issues auch nutzen, um einem Lieblings-Open-Source-Projekt einen Fehler mitzuteilen oder eine Funktion vorzuschlagen, die Sie für sinnvoll halten!

Für größere Projekte können Sie viele Issues auf einem Projekt-Board verwalten. GitHub-Projekte helfen Ihnen, Ihre Arbeit zu organisieren und zu priorisieren. Mehr dazu erfahren Sie im Dokument ["Über Projekt-Boards"](https://docs.github.com/en/github/managing-your-work-on-github/about-project-boards). Sie werden wahrscheinlich kein Projekt-Board für Ihre Aufgaben benötigen, aber für größere Projekte sind sie eine großartige Möglichkeit, die Arbeit Ihres Teams zu organisieren!

Sie können auch Pull Requests und Issues miteinander verknüpfen, um zu zeigen, dass eine Fehlerbehebung im Gange ist, und das Issue automatisch zu schließen, wenn jemand den Pull Request zusammenführt.

Mehr über Issues und deren Verknüpfung mit Pull Requests erfahren Sie im Artikel ["Über Issues"](https://docs.github.com/en/github/managing-your-work-on-github/about-issues).

### Ihr Benutzerprofil

Ihre Profilseite erzählt anderen die Geschichte Ihrer Arbeit durch die Repositories, die Sie interessieren, die Beiträge, die Sie geleistet haben, und die Gespräche, die Sie geführt haben. Sie können der Welt auch einen einzigartigen Einblick in Ihre Person mit Ihrer Profil-README geben. Mit Ihrem Profil können Sie zukünftigen Arbeitgebern alles über sich erzählen!

Mehr über Ihr Benutzerprofil und das Hinzufügen und Aktualisieren Ihrer Profil-README erfahren Sie im Artikel ["Verwalten Ihrer Profil-README"](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme).

### Verwendung von Markdown auf GitHub

Vielleicht haben Sie es schon bemerkt, aber Sie können auf GitHub einige coole Formatierungen zu Ihren Issues, Pull Requests und Dateien hinzufügen. ["Markdown"](https://guides.github.com/features/mastering-markdown/) ist eine einfache Möglichkeit, Ihre Issues, Pull Requests und Dateien mit einfacher Syntax zu formatieren. Das kann helfen, Ihre Informationen zu organisieren und sie für andere leichter lesbar zu machen. Sie können auch GIFs und Bilder einfügen, um Ihre Argumente zu unterstreichen!

Mehr über das Verwenden von GitHubs Markdown erfahren Sie im Artikel ["Grundlegende Schreib- und Formatierungssyntax"](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax).

### Interaktion mit der GitHub-Community

Die GitHub-Community ist riesig. Es gibt viele verschiedene Personen, die GitHub täglich nutzen – Studierende wie Sie, professionelle Entwickler, Hobbyisten, die an Open-Source-Projekten arbeiten, und Entdecker, die eigenständig in die Welt der Softwareentwicklung eintauchen. Es gibt viele Möglichkeiten, mit der größeren GitHub-Community zu interagieren, aber hier sind drei Orte, an denen Sie beginnen können.

#### Repositories mit Sternen markieren

Wenn Sie ein Repository interessant finden oder es im Auge behalten möchten, können Sie es mit einem Stern markieren! Wenn Sie ein Repository mit einem Stern versehen, wird es auch als Signal verwendet, um bessere Empfehlungen auf github.com/explore anzuzeigen. Wenn Sie später zu Ihren markierten Repositories zurückkehren möchten, können Sie dies über Ihr Benutzerprofil tun.

Mehr über das Markieren von Repositories erfahren Sie im Artikel ["Repositories mit Sternen speichern"](https://docs.github.com/en/github/getting-started-with-github/saving-repositories-with-stars).

#### Nutzern folgen

Sie können Personen auf GitHub folgen, um Benachrichtigungen über deren Aktivitäten zu erhalten und Projekte in deren Communitys zu entdecken. Wenn Sie einer Person folgen, werden deren öffentliche Aktivitäten auf GitHub in Ihrem Dashboard angezeigt, sodass Sie alle interessanten Projekte sehen können, an denen sie arbeiten.

Mehr über das Folgen von Nutzern erfahren Sie im Artikel ["Personen folgen"](https://docs.github.com/en/github/getting-started-with-github/following-people).

#### GitHub Explore durchsuchen

GitHub Explore ist der perfekte Ort, um genau das zu tun – zu erkunden. 😄 Sie können neue Projekte, Veranstaltungen und Entwickler entdecken und mit ihnen interagieren.

Sie können die GitHub Explore-Website [hier besuchen](https://github.com/explore). Je mehr Sie mit GitHub interagieren, desto besser wird Ihre Explore-Ansicht auf Ihre Interessen zugeschnitten.

## 📝 Optionale nächste Schritte

* Öffnen Sie einen Pull Request und informieren Sie Ihren Lehrer darüber, dass Sie diesen Kurs abgeschlossen haben.
* Erstellen Sie eine neue Markdown-Datei in diesem Repository. Teilen Sie mit, was Sie gelernt haben und was Sie noch verwirrt! Experimentieren Sie mit verschiedenen Stilen!
* Erstellen Sie Ihre Profil-README. Lassen Sie die Welt ein wenig mehr über Sie erfahren! Was möchten Sie lernen? Woran arbeiten Sie? Was ist Ihr Lieblingshobby? Mehr über das Erstellen Ihrer Profil-README erfahren Sie im Artikel ["Verwalten Ihrer Profil-README"](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme).
* Gehen Sie zu Ihrem Benutzer-Dashboard und erstellen Sie ein neues Repository. Experimentieren Sie mit den Funktionen dieses Repositories, um sich mit ihnen vertraut zu machen.
* [Lassen Sie uns wissen, was Ihnen am Inhalt dieses Kurses gefallen oder nicht gefallen hat](https://support.github.com/contact/education). Was möchten Sie mehr sehen? Was würde Ihr Lernen interessanter oder hilfreicher machen?

## 📚 Ressourcen

* [Ein kurzes Video, das erklärt, was GitHub ist](https://www.youtube.com/watch?v=w3jLJU7DT5E&feature=youtu.be)
* [Git und GitHub Lernressourcen](https://docs.github.com/en/github/getting-started-with-github/git-and-github-learning-resources)
* [Verstehen des GitHub-Workflows](https://guides.github.com/introduction/flow/)
* [Wie man GitHub-Branches verwendet](https://www.youtube.com/watch?v=H5GJfcp3p4Q&feature=youtu.be)
* [Interaktive Git-Schulungsmaterialien](https://githubtraining.github.io/training-manual/#/01_getting_ready_for_class)
* [GitHubs Learning Lab](https://lab.github.com/)
* [Forum der Bildungsgemeinschaft](https://education.github.community/)
* [GitHub Community-Forum](https://github.community/)
