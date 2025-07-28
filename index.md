---
layout: page
title: Das fehlender Semester deines Informatikstudiums 
nositetitle: true
---
 ``` Hinweis: Die Übersetzung ist noch in der Entstehung und daher ist der Kurs noch nicht vollständig übersetzt. Dieser Hinweis wird entfernt, sobald die Übersetzung vollständig ist. ```

In Kursen und Vorlesungen wird dir alles über anspruchsvolle Themen der Informatik gelehrt: von Betriebssystemen bis hin zu maschinellem Lernen. Aber ein fundamentales Thema wird selten abgedeckt und stattdessen den Studierenden in Eigenarbeit überlassen: Die Befähigung, ihre eigenen Werkzeuge zu beherrschen. Im Folgenden lernst du, die Kommandozeile zu meistern, leistungsstarke Texteditoren zu benützen, hilfreiche Gimmicks von Versionskontrollsystemen auszunützen und vieles mehr!

Studierende verbringen im Laufe ihres Studiums viele Stunden, um mit diesen fundamentalen Tools umzugehen (und Tausende während ihrer Karriere), daher ist es sinnvoll, einen möglichst reibungslosen Umgang mit diesen Werkzeugen zu erlernen. Dadurch verbringen Sie weniger Zeit damit, herauszufinden, wie Sie Ihre Tools optimal nutzen können – und können sich stattdessen auf die Lösung von Problemen konzentrieren, die zuvor unmöglich komplex oder unüberwindbar schienen.

Erfahre mehr über die [Motivation dieses Kurses](/about/).

# Vorlesungsverzeichnis

<ul>
{% assign lectures = site['2020'] | sort: 'date' %}
{% for lecture in lectures %}
    {% if lecture.phony != true %}
        <li>
        <strong>{{ lecture.date | date: '%d.%m.%y' }}</strong>:
        {% if lecture.ready %}
            <a href="{{ lecture.url }}">{{ lecture.title }}</a>
        {% else %}
            {{ lecture.title }} {% if lecture.noclass %}[no class]{% endif %}
        {% endif %}
        </li>
    {% endif %}
{% endfor %}
</ul>

Alle Vorlesungen sind verfügbar [auf
YouTube](https://www.youtube.com/playlist?list=PLyzOVJj3bHQuloKGG59rS43e29ro7I57J).

# Über diesen Kurs

**Dozierende**: Die Dozenten dieses Kurses sind [Anish](https://www.anishathalye.com/), [Jon](https://thesquareplanet.com/), und [Jose](http://josejg.com/).<br>
**Fragen**: Schreib uns eine Mail an: [missing-semester@mit.edu](mailto:missing-semester@mit.edu).

# Über das MIT hinaus

Wir haben diesen Kurs auch über das MIT hinaus veröffentlicht, in der Hoffnung das andere von diesen profitieren können.
Beiträge und Disskusionen darüber kannst du auf folgenden Webseiten finden:

 - [Hacker News](https://news.ycombinator.com/item?id=22226380)
 - [Lobsters](https://lobste.rs/s/ti1k98/missing_semester_your_cs_education_mit)
 - [/r/learnprogramming](https://www.reddit.com/r/learnprogramming/comments/eyagda/the_missing_semester_of_your_cs_education_mit/)
 - [/r/programming](https://www.reddit.com/r/programming/comments/eyagcd/the_missing_semester_of_your_cs_education_mit/)
 - [Twitter](https://twitter.com/jonhoo/status/1224383452591509507)
 - [YouTube](https://www.youtube.com/playlist?list=PLyzOVJj3bHQuloKGG59rS43e29ro7I57J)

{% comment %}
Some more URLs:

- https://news.ycombinator.com/item?id=27154577
- https://news.ycombinator.com/item?id=34934216
- https://www.reddit.com/r/learnprogramming/comments/nca1v3/mit_the_missing_semester_of_your_cs_education/
- https://www.reddit.com/r/compsci/comments/eyywv8/the_missing_semester_of_your_cs_education_from_mit/
- https://www.reddit.com/r/programming/comments/io7nq3/the_missing_semester_of_your_cs_education_mit/
- https://twitter.com/MIT_CSAIL/status/1349766980413263873
- https://twitter.com/MIT_CSAIL/status/1481676163491659780
- https://twitter.com/MIT_CSAIL/status/1581313961093484545
{% endcomment %}

# Übersetzungen

- [Chinesisch (vereinfacht)](https://missing-semester-cn.github.io/)
- [Chinesisch (traditionell)](https://missing-semester-zh-hant.github.io/)
- [Japanisch](https://missing-semester-jp.github.io/)
- [Koreanisch](https://missing-semester-kr.github.io/)
- [Portugisisch](https://missing-semester-pt.github.io/)
- [Russisch](https://missing-semester-rus.github.io/)
- [Serbisch](https://netboxify.com/missing-semester/)
- [Spanisch](https://missing-semester-esp.github.io/)
- [Türkisch](https://missing-semester-tr.github.io/)
- [Vietnamesisch](https://missing-semester-vn.github.io/)
- [Arabisch](https://missing-semester-ar.github.io/)
- [Italienisch](https://missing-semester-it.github.io/)
- [Persisch](https://missing-semester-fa.github.io/)
- [Deutsch](https://missing-semester-de.github.io/)

Hinweis: Es handelt sich um externe Links zu Übersetzungen, die von der Community erstellt wurden.
Wir haben diese nicht verifiziert.

Hast du eine Übersetzung der Notizen für diese Klasse? Erstelle einen 
[Pull Request](https://github.com/missing-semester-de/missing-semester-de.github.io/pulls) damit
wir diese der Liste anfügen können!

## Danksagungen

Wir Danken Elaine Mello, Jim Cain, und [MIT Open
Learning](https://openlearning.mit.edu/) es uns zu ermöglichen die Vorlesungen aufzunehmen;
Anthony Zolnik und [MIT
AeroAstro](https://aeroastro.mit.edu/) für Audio und Videoequipment; und Brandi Adams sowie
[MIT EECS](https://www.eecs.mit.edu/) für die Unterstüzung dieses Kurses.

---

<div class="small center">
<p><a href="https://missing-semester-de.github.io/">Quelltext</a>.</p>
<p>Lizensiert unter CC BY-NC-SA.</p>
<p>Schaue <a href="/license/">hier</a> um selber beizutragen &amp; für die Übersetzungsrichtlinien.</p>
</div>
