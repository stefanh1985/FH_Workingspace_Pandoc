<!--

author:   Stefan Hierholzer
email:    stefan.hierholzer@paedagogika.com
icon:     https://paedagogika-fachschule.de/media/paedagogika-fachschule-weblogo.png
version:  0.0.1
language: de
narrator: Deutsch Male
comment:  Dieses Dokument dient der Begrüßung neuer Studierender
tags:     Neue studierende, Pädagogika, Fachschule, Tutorial


@style

section {
    margin-top: 2rem;
}

iframe {
    min-height: 600px;
}

details {
    padding: 1em;
    border: 1px solid #ccc;
    border-radius: 4px;
    margin-bottom: 0.1em;
    display: block;
}

summary {
    font-weight: bold;
    cursor: pointer;
}

@keyframes details-show {
    from {
        opacity: 0;
        transform: translateY(-0.5em);
    }
}

details[open] > *:not(summary) {
    animation: details-show 500ms ease-in-out;
}

.person-img {
    margin-top: 1em;
    width: 250px;
}

@end

-->

# FH-Workingspace 🧑‍💼 -Pandoc
<div style="width:100%;height:0;padding-bottom:86%;position:relative;"><iframe src="https://giphy.com/embed/payr6u9f4Pa5zYGDid" width="100%" height="100%" style="position:absolute" frameBorder="0" class="giphy-embed" allowFullScreen></iframe></div><p><a href="https://giphy.com/gifs/jojo-joseph-raja-payr6u9f4Pa5zYGDid">via GIPHY</a></p>


# 📂 Was ist das für ein Programm?

![Pandoc-Logo](https://framalibre.org/images/logo/Pandoc.png)

Pandoc ist ein universelles Werkzeug zur Dokumentenkonvertierung, das es ermöglicht, Dateien von einem Markup-Format in ein anderes umzuwandeln. Es unterstützt eine Vielzahl von Formaten, darunter HTML, Markdown, LaTeX und viele mehr. Man kann es sich als Schweizer Taschenmesser für Textdateien vorstellen, das die Umwandlung zwischen unterschiedlichsten Formaten vereinfacht. Mit Pandoc können Benutzer beispielsweise ein Markdown-Dokument in ein PDF, eine HTML-Webseite in ein Word-Dokument oder eine LaTeX-Datei in eine PowerPoint-Präsentation umwandeln. Es ist besonders nützlich für Akademiker, Schriftsteller und jeden, der Dokumente zwischen verschiedenen Formaten austauschen muss. Die Bedienung erfolgt über die Kommandozeile, was zunächst einschüchternd wirken kann, aber durch die umfangreiche Dokumentation und Online-Community gut unterstützt wird. Pandoc erlaubt auch die Anpassung der Ausgabe durch Vorlagen, was besonders bei der Erstellung professionell aussehender Dokumente hilfreich ist. Es ist ein Open-Source-Projekt, was bedeutet, dass es kostenlos genutzt und von der Gemeinschaft weiterentwickelt wird. Kurz gesagt, Pandoc spart Zeit und Aufwand beim Umgang mit unterschiedlichen Dokumentformaten und erleichtert den Workflow in vielen Bereichen, von der akademischen Forschung bis zum Publizieren.


# 🧑‍🏫 Wozu wird es in der Lehre genutzt?
Pandoc ist ein universelles Dokumentenkonvertierungstool, das es ermöglicht, Dokumente von einem Format in ein anderes umzuwandeln. Für Dozierende und Studierende an Fachhochschulen bietet es eine Vielzahl von Anwendungsmöglichkeiten. Dozierende können beispielsweise Lehrmaterialien einfach zwischen verschiedenen Formaten wie Markdown, HTML und PDF wechseln, um sie auf verschiedenen Plattformen zugänglich zu machen. Studierende können ihre Arbeiten in dem Format erstellen, das ihnen am meisten zusagt, und sie dann in das von der Hochschule geforderte Format konvertieren. Dies erleichtert die Einreichung von Aufgaben und die Erstellung von Präsentationen. Mit Pandoc ist es auch möglich, Literaturverzeichnisse automatisch zu formatieren, was Zeit spart und die Einhaltung akademischer Standards erleichtert. Die Nutzung von Pandoc setzt keine tiefe technische Kenntnis voraus und kann durch einfache Befehle in der Kommandozeile gesteuert werden. Durch seine Flexibilität und Einfachheit ist Pandoc ein wertvolles Tool für die akademische Arbeit an Fachhochschulen, sowohl für Lehrende als auch für Lernende.

# 📀 Wie bedienen ich das Programm (Videoanaleitungen)

<div style="width:100%;height:0;padding-bottom:52%;position:relative;"><iframe src="https://giphy.com/embed/ENL5sbMUYeT2L9lDop" width="100%" height="100%" style="position:absolute" frameBorder="0" class="giphy-embed" allowFullScreen></iframe></div><p><a href="https://giphy.com/gifs/snl-saturday-night-live-season-48-ENL5sbMUYeT2L9lDop">via GIPHY</a></p>

## 🧑‍🦱Nutzer*innenperspektive
Zunächst muss sich der*die Nutzer*in auf: [Webseite einfügen] mittels Benutzername und Kennwort anmelden.

>Eine Online-Koverteroption betseht unter: https://pandoc.org/try/

>Es gibt die Möglichkeit deutsche Untertitel in Youtube einzufügen, wie folgender Link zeigt: https://www.youtube.com/watch?v=cvZo3TzTiqA 

**Using Pandoc (englisch version)**
<iframe width="560" height="315" src="https://www.youtube.com/embed/N31E_NZYQQY?si=1ogM5YRGA5coVEBA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

**Mit Pandoc Markdown datei in Presentation konvertieren**
<iframe width="560" height="315" src="https://www.youtube.com/embed/Uo3WBVT2NZc?si=VP7YHmUUAvoOAT-D" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

**Pandoc - das schweizer Taschenmesser für Dokumentverarbeitung!**
<iframe width="560" height="315" src="https://www.youtube.com/embed/eHVgUM-cAH8?si=zPTH54vDvHQ-sQDg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

# 📖 Wie bedienen ich das Programm (schriftliche Anleitung) 

<div style="width:100%;height:0;padding-bottom:73%;position:relative;"><iframe src="https://giphy.com/embed/WoWm8YzFQJg5i" width="100%" height="100%" style="position:absolute" frameBorder="0" class="giphy-embed" allowFullScreen></iframe></div><p><a href="https://giphy.com/gifs/cartoons-comics-sea-reading-WoWm8YzFQJg5i">via GIPHY</a></p>

## 🧑‍🦱Nutzer*innenperspektive
Es existieren unterschiedliche Zugangswege zu schriftlichen Anleitungen bezüglich Pandoc (und Markdown). 

**Offizielles Manual (englisch)**
https://pandoc.org/MANUAL.html

https://kofler.info/free-ebooks/pandoc2.pdf

https://elvis.inf.tu-dresden.de/wiki/index.php/Pandoc

https://www.datacodedesign.de dokumentationen-und-anleitungen-mit-markdown-pandoc/

https://www.schiedt.org/images/Dokumente/Anleitungen/pandoc/anleitung_pandoc_markdown.pdf


## ❓FAQ 
<div style="width:100%;height:0;padding-bottom:101%;position:relative;"><iframe src="https://giphy.com/embed/hGRlr5VjYsTVZOcWm3" width="100%" height="100%" style="position:absolute" frameBorder="0" class="giphy-embed" allowFullScreen></iframe></div><p><a href="https://giphy.com/gifs/wind-answer-question-mark-hGRlr5VjYsTVZOcWm3">via GIPHY</a></p>


<details>
<summary>Was ist Pandoc?</summary>
Pandoc ist ein Konvertierungsprogramm, das Textdateien von einem Format in ein anderes umwandeln kann. Du kannst damit zum Beispiel ein Word-Dokument in ein PDF umwandeln.
</details>

<details>
<summary>Wie installiere ich Pandoc?</summary>
Du kannst Pandoc auf der offiziellen Website herunterladen und installieren. Besuche dazu [pandoc.org](https://pandoc.org/installing.html) und folge den Anweisungen für dein Betriebssystem.
</details>

<details>
<summary>Wie benutze ich Pandoc?</summary>
Pandoc wird über die Kommandozeile (Terminal) benutzt. Nach der Installation öffnest du die Kommandozeile und gibst Befehle ein, um Dateien zu konvertieren. Ein Beispielbefehl ist `pandoc input.docx -o output.pdf`, der eine Word-Datei in eine PDF-Datei umwandelt.
</details>

<details>
<summary>Welche Dateiformate unterstützt Pandoc?</summary>
Pandoc unterstützt viele verschiedene Dateiformate, darunter Markdown, HTML, Word, PDF, EPUB, LaTeX und viele mehr. Eine vollständige Liste findest du auf der [Pandoc Website](https://pandoc.org).
</details>

<details>
<summary>Wie konvertiere ich ein Word-Dokument in ein PDF?</summary>
Nachdem du Pandoc installiert hast, öffnest du die Kommandozeile und gibst folgenden Befehl ein: `pandoc dein_dokument.docx -o dein_dokument.pdf`. Ersetze "dein_dokument.docx" mit dem Namen deiner Word-Datei.
</details>

<details>
<summary>Wie kann ich mehrere Dateien gleichzeitig konvertieren?</summary>
Du kannst ein Skript erstellen, das mehrere Pandoc-Befehle nacheinander ausführt. Alternativ kannst du eine Batch-Datei (Windows) oder ein Shell-Skript (Mac/Linux) erstellen, um mehrere Dateien gleichzeitig zu konvertieren.
</details>

<details>
<summary>Was mache ich, wenn ich eine Fehlermeldung erhalte?</summary>
Prüfe zuerst, ob du den Befehl korrekt eingegeben hast und ob die Dateien an den angegebenen Orten existieren. Falls du weiterhin Probleme hast, kannst du im Internet nach der spezifischen Fehlermeldung suchen oder auf der [Pandoc Website](https://pandoc.org) nach Hilfe suchen.
</details>

<details>
<summary>Gibt es eine grafische Benutzeroberfläche für Pandoc?</summary>
Ja, es gibt mehrere grafische Benutzeroberflächen (GUIs) für Pandoc, die die Nutzung erleichtern. Eine davon ist PanWriter, die du ausprobieren kannst, wenn du keine Befehle in der Kommandozeile eingeben möchtest.
</details>

<details>
<summary>Kann ich Pandoc mit anderen Programmen integrieren?</summary>
Ja, Pandoc kann mit vielen anderen Programmen und Texteditoren integriert werden, wie z.B. Microsoft Word, Markdown-Editoren und LaTeX-Editoren. Viele dieser Programme bieten Plugins oder Erweiterungen für Pandoc.
</details>

<details>
<summary>Wo finde ich weitere Informationen und Hilfe zu Pandoc?</summary>
Weitere Informationen und Hilfe findest du auf der [offiziellen Pandoc Website](https://pandoc.org), in der Dokumentation und in Online-Foren. Es gibt auch viele Tutorials und Videos, die dir den Einstieg erleichtern.
</details>

















# ❣️ Best Practice Beispiel(e)



# 📈 Alles ist im Wandel
Alles befindet sich immer im Wandel, dies gilt insbesondere für Updates von Software. Ist dir ein Fehler aufgefallen oder du hast etwas was sich verndert hat und dies soll eingearbeitet werden- Toll!! Dann melde dich bitte bei:

>stefan.hierholzer@paedagogika.com

<div style="width:100%;height:0;padding-bottom:56%;position:relative;"><iframe src="https://giphy.com/embed/KnK190zp5alz2wlRxU" width="100%" height="100%" style="position:absolute" frameBorder="0" class="giphy-embed" allowFullScreen></iframe></div><p><a href="https://giphy.com/gifs/transition-chang-change-management-KnK190zp5alz2wlRxU">via GIPHY</a></p>
