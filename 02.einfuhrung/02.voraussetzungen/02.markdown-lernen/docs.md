---
title: 'Markdown Lernen'
taxonomy:
    category:
        - docs
page-toc:
    active: true
---

Im Folgenden findet man eine Liste von Seiten, auf denen man Markdown lernen kann. 

* [MarkDown Guide](https://www.markdownguide.org?target=_blank) - Das Markdown-Handbuch ist ein kostenloses und quelloffenes Referenzhandbuch, das erklärt, wie man Markdown verwendet.
* [Learn Markdown](https://learnmarkdown.com?target=_blank) - Sehr zu emphelen (nur Englisch)
* [Markdown Tutorial](https://www.markdowntutorial.com?target=_blank) - auch in Spanish
* [Einführung und Syntax](https://cmsstash.de/website-praxis/markdown-fur-webseiten?target=_blank) - Theoretisch, aber interessant.
* [Wikipedia](https://de.wikipedia.org/wiki/Markdown?target=_blank) [^1]

Sicherlich findet man noch weitere Seiten und Ressourcen auf eigener Faust.
Eine einfachere Möglichkeit, Inhalte zu erstellen, besteht darin, einen Markdown-Editor auf dem Computer zu installieren und die Datei dann einfach an Ihren Administrator zu senden, der sie an die richtige Stelle kopiert. Wir empfehlen folgende App: [MarkText](https://marktext.app?target=_blank).
<br>
<br>
<br>

***
<br>

# Warum Markdown?
Einige der wichtigsten Vorteile sind:

1. Markdown ist einfach zu erlernen, mit minimalen zusätzlichen Zeichen, so dass es auch schneller ist, Inhalte zu schreiben.
2. Geringere Chance auf Fehler beim Schreiben in Markdown.
3. Erzeugt eine gültige XHTML.
4. Hält den Inhalt und die visuelle Darstellung getrennt, so dass Sie das Aussehen Ihrer Website nicht durcheinander bringen können.
5. Schreiben Sie in einem beliebigen Texteditor oder einer Markdown-Anwendung.
6. Markdown ist eine Freude zu benutzen!

John Gruber, der Autor von Markdown, drückt es folgendermaßen aus:

> Das übergeordnete Designziel für die Formatierungssyntax von Markdown ist es, sie so lesbar wie möglich zu machen. Die Idee ist, dass ein mit Markdown formatiertes Dokument als reiner Text veröffentlicht werden kann, ohne dass es so aussieht, als ob es mit Tags oder Formatierungsanweisungen versehen worden wäre. Während die Markdown-Syntax von mehreren existierenden Text-zu-HTML-Filtern beeinflusst wurde, ist die größte Inspirationsquelle für die Markdown-Syntax das Format von reinen Text-E-Mails.
> -- <cite>John Gruber</cite>


<br>
<br>
<br>
***
# Beispiele
Lassen Sie uns ohne weitere Verzögerung die wichtigsten Elemente von Markdown durchgehen und wie das resultierende HTML aussieht. der Stil wird durch das CSS diktiert und kann beliebig geändert werden, ohne den Seiteninhalt zu beeinträchtigen.

## Überschriften
Überschriften von `h1` bis `h6` werden mit einem `#` für jede Ebene aufgebaut:

```markdown
# h1 Überschrift
## h2 Überschrift
### h3 Überschrift
#### h4 Überschrift
##### h5 Überschrift
###### h6 Überschrift
```
Übergibt an:
# h1 Überschrift
## h2 Überschrift
### h3 Überschrift
#### h4 Überschrift
##### h5 Überschrift
###### h6 Überschrift

## Horizontale Linienführung

Das HTML-Element `<hr>` dient dazu, einen "thematischen Bruch" zwischen Elementen auf Absatzebene zu erzeugen. In Markdown können Sie ein `<hr>` mit einem der folgenden Elemente erstellen:

* `___`: drei aufeinanderfolgende Unterstriche
* `---`: drei aufeinanderfolgende Bindestriche
* `***`: drei aufeinanderfolgende Sternchen

werden alle übergeben als:

***


<br>
<br>
<br>
## Hervorhebung

### Fett
Zur Hervorhebung eines Textausschnitts durch eine stärkere Schriftart.

Der folgende Textausschnitt wird **fett übergeben**.

```Markdown
Dieser Text ist **Fett**
```
wird übergeben an:

Dieser Text ist **Fett**

### Kursiv
Zur Hervorhebung eines Textausschnittes mit Kursivschrift.

Der folgende Textausschnitt wird _als kursiver Text_ dargestellt.

```Markdown
Dieser Text ist _Kursiv_
```
wird übergeben an:

Dieser Text ist _Kursiv_


### Durchgestrichen
In GFM (GitHub flavored Markdown) können Sie Durchstreichungen vornehmen.

```Markdown
Dieser Text ist ~~durchgestrichen~~
```
Das wird übergeben an:

Dieser Text ist ~~durchgestrichen~~

<br>
<br>
<br>
***
## Blockzitate
Zum Zitieren von Inhaltsblöcken aus einer anderen Quelle innerhalb Ihres Dokuments.

Fügen Sie `>` vor jeden Text, den Sie zitieren möchten.

``` Markdown
> **Fusion Drive** kombiniert eine Festplatte mit einem Flash-Speicher (Solid-State-Drive) und stellt sie als ein einziges logisches Volume dar, das den Speicherplatz beider Laufwerke kombiniert.
```
Wird übergeben an:

> **Fusion Drive** kombiniert eine Festplatte mit einem Flash-Speicher (Solid-State-Drive) und stellt sie als ein einziges logisches Volume dar, das den Speicherplatz beider Laufwerke kombiniert.

<br>
<br>
<br>
***
## Hinweise

Wir haben vier Notizstile, die die Standard-Markdown-Syntax für Blockanführungszeichen erweitern.  Grundsätzlich erzeugen Ebenen von Anfühtungstriche Hinweise in 4 Farben, wie folgt:
### 1 `!` für Gelb/Orange

``` Markdown
! Diese Arten von Hinweise sind nützlich, um die Aufmerksamkeit des Lesers auf etwas Wichtiges, Gefährliches oder Interessantes zu lenken.
```
Übergibt an:

! Diese Arten von Hinweise sind nützlich, um die Aufmerksamkeit des Lesers auf etwas Wichtiges, Gefährliches oder Interessantes zu lenken.

### 2 `!!` für Rot

```Markdown
!! Diese Arten von Hinweise sind nützlich, um die Aufmerksamkeit des Lesers auf etwas Wichtiges, Gefährliches oder Interessantes zu lenken.
```
Übergibt an:

!! Diese Arten von Hinweise sind nützlich, um die Aufmerksamkeit des Lesers auf etwas Wichtiges, Gefährliches oder Interessantes zu lenken.

### 3 `!!!` für Blau

```Markdown
!!! Diese Arten von Hinweise sind nützlich, um die Aufmerksamkeit des Lesers auf etwas Wichtiges, Gefährliches oder Interessantes zu lenken.
```
Übergibt an:

!!! Diese Arten von Hinweise sind nützlich, um die Aufmerksamkeit des Lesers auf etwas Wichtiges, Gefährliches oder Interessantes zu lenken.

### 4 `!!!!` für Grün

```Markdown
!!!! Diese Arten von Hinweise sind nützlich, um die Aufmerksamkeit des Lesers auf etwas Wichtiges, Gefährliches oder Interessantes zu lenken.
```
Übergibt an:

!!!! Diese Arten von Hinweise sind nützlich, um die Aufmerksamkeit des Lesers auf etwas Wichtiges, Gefährliches oder Interessantes zu lenken.

<br>
<br>
<br>
***
## Listen

### Ungeordnet
Eine Liste von Elementen, in der die Reihenfolge der Elemente nicht explizit eine Rolle spielt.

Sie können jedes der folgenden Symbole verwenden, um Aufzählungszeichen für jeden Listeneintrag zu kennzeichnen:

```Markdown
* gültiges Zeichen
- gültiges Zeichen
+ gültiges Zeichen
```
Zum Beispiel

```Markdown
+ Lorem ipsum dolor sit amet
+ Consectetur adipiscing elit
+ Integer molestie lorem at massa
+ Facilisis in pretium nisl aliquet
+ Nulla volutpat aliquam velit
  - Phasellus iaculis neque
  - Purus sodales ultricies
  	* Vestibulum laoreet porttitor sem
 	* Ac tristique libero volutpat at
+ Faucibus porta lacus fringilla vel
+ Aenean sit amet erat nunc
+ Eget porttitor lorem
```
Rendert an:

+ Lorem ipsum dolor sit amet
+ Consectetur adipiscing elit
+ Integer molestie lorem at massa
+ Facilisis in pretium nisl aliquet
+ Nulla volutpat aliquam velit
  - Phasellus iaculis neque
  - Purus sodales ultricies
		* Vestibulum laoreet porttitor sem
  		* Ac tristique libero volutpat at
+ Faucibus porta lacus fringilla vel
+ Aenean sit amet erat nunc
+ Eget porttitor lorem

### Geordnet

Eine Liste von Elementen, in der die Reihenfolge der Elemente doch wichtig ist.

```Markdown
1. lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa
4. Facilisis in pretium nisl aliquet
5. Nulla volutpat aliquam velit
6. Faucibus porta lacus fringilla vel
7. Aenean sit amet erat nunc
8. Eget porttitor lorem
```
Rendert an:

1. lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa
4. Facilisis in pretium nisl aliquet
5. Nulla volutpat aliquam velit
6. Faucibus porta lacus fringilla vel
7. Aenean sit amet erat nunc
8. Eget porttitor lorem


!!!! **TIP**: Wenn Sie nur `1.` für jede Zahl verwenden, nummeriert Markdown automatisch jedes Element. Zum Beispiel:

```Markdown
Lorem ipsum dolor sit amet
1. Consectetur adipiscing elit
1. integer molestie lorem at massa
1. Facilisis in pretium nisl aliquet
1. Nulla volutpat aliquam velit
1. Faucibus porta lacus fringilla vel
1. Aenean sit amet erat nunc
1. eget porttitor lorem
```
Rendert an:

1. lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa
4. Facilisis in pretium nisl aliquet
5. Nulla volutpat aliquam velit
6. Faucibus porta lacus fringilla vel
7. Aenean sit amet erat nunc
8. Eget porttitor lorem

<br>
<br>
<br>
***
## Code

### Inline-Code
Inline-Code-Schnipsel mit `` ` `` umschließen.

```Markdown
In diesem Beispiel sollte `<section></section>` als **Code** dargestellt werden, der durch Klicken auf das Symbol des Papierhalters einfach immer kopiert werden kann.
```
Wird übergeben an:

In diesem Beispiel sollte `<section></section>` mit **code** dargestellt werden, der durch Klicken auf das Symbol des Papierhalters einfach immer kopiert werden kann.

### Eingerückter Code

Oder rücken Sie mehrere Codezeilen um mindestens vier Leerzeichen ein, wie in:

```markdown
    // Einige Kommentare
     Zeile 1 des Codes
     Zeile 2 des Codes
     Zeile 3 des Codes
```
Wird übergeben an:

    // Einige Kommentare
    Zeile 1 des Codes
    Zeile 2 des Codes
    Zeile 3 des Codes

<br>
<br>
<br>
***
## Tabellen
Tabellen werden durch Hinzufügen von Pipes als Trennzeichen zwischen den einzelnen Zellen und durch Hinzufügen einer Reihe von Strichen (ebenfalls durch Balken getrennt) unter der Kopfzeile erstellt. Beachten Sie, dass die Pipes nicht vertikal ausgerichtet sein müssen.

```Markdown
| Option | Beschreibung |
| ------ | ----------- |
| data | Pfad zu Datendateien, um die Daten zu liefern, die in Vorlagen übergeben werden. |
| Motor | Motor, der für die Verarbeitung von Vorlagen verwendet werden soll. Handlebars ist der Standard. |
| ext | Erweiterung, die für dest-Dateien verwendet werden soll. |
```

Übergibt an:

| Option | Beschreibung |
| ------ | ----------- |
| data | Pfad zu Datendateien, um die Daten zu liefern, die in Vorlagen übergeben werden. |
| Motor | Motor, der für die Verarbeitung von Vorlagen verwendet werden soll. Handlebars ist der Standard. |
| ext | Erweiterung, die für dest-Dateien verwendet werden soll. |

<br>
<br>
<br>
***
## Links

### Grundlegende Verknüpfung

```Markdown
[Assemble](http://assemble.io)
```
Übergibt an (mit dem Mauszeiger über den Link fahren, es gibt keinen Tooltip):

[Assemble](http://assemble.io)

### Einen Titel hinzufügen

```Markdown
[Upstage](https://github.com/upstage/ "Besuchen Sie Upstage!")
```
Übergibt an (mit dem Mauszeiger über den Link fahren, es sollte ein Tooltip erscheinen):

[Upstage](https://github.com/upstage/ "Besuchen Sie Upstage!")

<br>
<br>
<br>
***
## Bilder
Bilder haben eine ähnliche Syntax wie Links, enthalten aber ein vorangestelltes Ausrufezeichen.

```Markdown
![Open Source Initiative](https://opensource.org/files/OSI_Standard_Logo_0.svg)
```

Übergibt:
![Open Source Initiative](https://opensource.org/files/OSI_Standard_Logo_0.svg)


 [^1]: Wikipedia ist eben bekannt, kein Kommentar. Nur mit Markdown Fußzeile testen.
