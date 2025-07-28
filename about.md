---
layout: lecture
title: "Wofür dieser Kurs gut ist"
---

In Kursen und Vorlesungen wird dir alles über anspruchsvolle Themen der Informatik gelehrt: 
von Betriebssystemen bis hin zu maschinellem Lernen. Aber ein fundamentales Thema wird selten 
abgedeckt und stattdessen den Studierenden in Eigenarbeit überlassen: Die Befähigung, ihre 
eigenen Werkzeuge zu beherrschen. Im Folgenden lernst du, die Kommandozeile zu meistern, 
leistungsstarke Texteditoren zu benützen, hilfreiche Gimmicks von Versionskontrollsystemen 
auszunützen und vieles mehr!

Studierende verbringen im Laufe ihres Studiums viele Stunden, um mit diesen fundamentalen 
Tools umzugehen (und Tausende während ihrer Karriere), daher ist es sinnvoll, einen möglichst
reibungslosen Umgang mit diesen Werkzeugen zu erlernen. Dadurch verbringen Sie weniger Zeit
damit, herauszufinden, wie Sie Ihre Tools optimal nutzen können – und können sich stattdessen
auf die Lösung von Problemen konzentrieren, die zuvor unmöglich komplex oder unüberwindbar
schienen.

# Das fehlende Semester deines Informatikstudiums

Um dem entgegenzuwirken, bieten wir einen Kurs an, der alle Themen abdeckt, die wir für 
entscheidend halten, um ein effektiver Informatiker oder gewiefte Programmiererin zu sein.
Der Kurs ist praxisnah und anwendungsorientiert und bietet eine praktische Einführung in 
Werkzeuge und Techniken, die du sofort in einer Vielzahl von Situationen anwenden kannst,
denen du begegnen wirst.

Der Kurs findet während des „Independent Activities Period“ (IAP) im Januar 2020 am MIT
statt – ein einmonatiges Semester, in dem kürzere, oft von Studierenden organisierte Kurse
angeboten werden. Die Vorlesungen selbst sind nur für MIT-Studierende zugänglich, aber wir
stellen alle Kursmaterialien sowie Videoaufzeichnungen der Vorlesungen der Öffentlichkeit 
zur Verfügung.

Wenn das für dich interessant klingt, findest du hier einige konkrete Beispiele dafür, was 
in dem Kurs vermittelt wird:

## Eingabeaufforderung

Wie man gewöhnliche und sich wiederholende Aufgaben mit Aliases, Skripten und Build-Systemen
automatisieren kann. Kein Copy-Paste von Befehlen aus Textdateien mehr. Kein „Führe diese 15
Befehle nacheinander aus“ mehr. Kein „Du hast vergessen, diesen Befehl auszuführen“ oder 
„Du hast vergessen, dieses Argument zu übergeben“.

Zum Beispiel kann das schnelle Durchsuchen deiner Befehls-Historie enorm viel Zeit sparen.
Im folgenden Beispiel zeigen wir einige Tricks zum Navigieren durch die Shell-Historie für
convert-Befehle.

<video autoplay="autoplay" loop="loop" controls muted playsinline  oncontextmenu="return false;"  preload="auto"  class="demo">
  <source src="/static/media/demos/history.mp4" type="video/mp4">
</video>

## Versionskontrolle

Wie man Versionskontrolle richtig einsetzt – und wie sie dir helfen kann, Katastrophen zu vermeiden, 
mit anderen zusammenzuarbeiten und fehlerhafte Änderungen schnell zu finden und einzugrenzen. Kein
rm -rf; git clone mehr. Keine Merge-Konflikte mehr (naja, zumindest weniger davon). Keine riesigen 
Blöcke aus auskommentiertem Code mehr. Kein Rätselraten mehr, was den Code kaputt gemacht hat. Kein
„Oh nein, haben wir den funktionierenden Code gelöscht?!“ mehr. Wir zeigen dir sogar, wie du mit Pull
Requests zu Projekten anderer Leute beitragen kannst!

Im folgenden Beispiel verwenden wir git bisect, um herauszufinden, welcher Commit einen Unit-Test 
kaputt gemacht hat – und beheben ihn anschließend mit git revert.
<video autoplay="autoplay" loop="loop" controls muted playsinline  oncontextmenu="return false;"  preload="auto"  class="demo">
  <source src="/static/media/demos/git.mp4" type="video/mp4">
</video>

## Textbearbeitung

Wie man Dateien effizient über die Kommandozeile bearbeitet – sowohl lokal als auch remote – und 
dabei die erweiterten Funktionen moderner Editoren nutzt. Kein ständiges Hin- und Herkopieren von
Dateien mehr. Kein mühsames, sich wiederholendes Editieren mehr.

Vim-Makros gehören zu den besten Funktionen von Vim. Im folgenden Beispiel wandeln wir mithilfe 
eines verschachtelten Vim-Makros eine HTML-Tabelle blitzschnell in das CSV-Format um.
<video autoplay="autoplay" loop="loop" controls muted playsinline  oncontextmenu="return false;"  preload="auto"  class="demo">
  <source src="/static/media/demos/vim.mp4" type="video/mp4">
</video>

## Remoteverbindungen

Wie man bei der Arbeit mit entfernten Maschinen mit SSH-Schlüsseln und Terminal-Multiplexing 
einen kühlen Kopf bewahrt. Kein Dutzend offener Terminalfenster mehr, nur um zwei Befehle 
gleichzeitig auszuführen. Kein ständiges Eintippen des Passworts bei jeder Verbindung. Kein
Totalverlust mehr, nur weil das Internet kurz weg war oder du deinen Laptop neu starten musstest.

Im folgenden Beispiel nutzen wir tmux, um Sitzungen auf entfernten Servern am Leben zu halten,
und mosh, um Netzwerk-Roaming und Verbindungsabbrüche problemlos zu überstehen.

<video autoplay="autoplay" loop="loop" controls muted playsinline  oncontextmenu="return false;"  preload="auto"  class="demo">
  <source src="/static/media/demos/ssh.mp4" type="video/mp4">
</video>

## Dateien finden

Wie man Dateien, die man sucht, schnell findet. Kein endloses Herumklicken mehr durch Projektordner,
bis man endlich die Datei mit dem gewünschten Code gefunden hat.

Im folgenden Beispiel suchen wir mit fd blitzschnell nach Dateien und mit rg nach Codeausschnitten.
Außerdem wechseln wir mit fasd schnell in kürzlich oder häufig verwendete Dateien und Ordner und
öffnen sie direkt mit cd oder vim.

<video autoplay="autoplay" loop="loop" controls muted playsinline  oncontextmenu="return false;"  preload="auto"  class="demo">
  <source src="/static/media/demos/find.mp4" type="video/mp4">
</video>

## Datenaufbereitung

Wie man Daten und Dateien direkt über die Kommandozeile schnell und einfach anzeigen, bearbeiten, 
parsen, plotten und berechnen kann. Kein Copy-Paste mehr aus Logdateien. Kein manuelles Berechnen
von Statistiken über Daten mehr. Kein Plotten mehr mit Tabellenkalkulationen.



## Virtuelle Maschinen

Wie man virtuelle Maschinen nutzt, um neue Betriebssysteme auszuprobieren, Projekte voneinander 
zu isolieren und den Hauptrechner sauber und ordentlich zu halten. Kein versehentliches Beschädigen 
deines Computers mehr während eines Security-Labs. Keine Millionen zufällig installierter Pakete 
mit unterschiedlichen Versionen mehr.

## IT-Sicherheit

Wie man im Internet unterwegs ist, ohne sofort alle seine Geheimnisse mit der Welt zu teilen. 
Kein ständiges Ausdenken von Passwörtern, die den verrückten Anforderungen entsprechen müssen. 
Keine unsicheren, offenen WLAN-Netzwerke mehr. Keine unverschlüsselten Nachrichten mehr.

# Zusammenfassung

Dies und vieles mehr wird in den 12 Vorlesungen des Kurses behandelt, jede mit einer Übung, damit
du die Werkzeuge selbst besser kennenlernen kannst. Du kannst dir auch die Vorlesungen von [Hacker
Tools](https://hacker-tools.github.io/lectures/) ansehen, die wir im letzten IAP angeboten haben. 
Dieser Kurs ist der Vorgänger des aktuellen Kurses und behandelt viele der gleichen Themen.

Happy hacking,<br>
Anish, Jose, and Jon
