## HTML cheat sheet


## Text

- `<p>`...`</p>`: Normaler Text ("paragraph")
- Listen:
    - `<ul>` unordered list: Bulletpoints
    - `<ol>` ordered list: defaultmäßig mit Nummerierung; lässt sich mit Type-Argument zu a,b,c ändern: `<ol type="a">`


## Grafiken

- Grundmuster: `<img src="path/to/source" style="...">`
- Im `style`-Element können wir das Erscheinungsbild genauer festlegen, und zwar mit Hilfe von CSS-Code:
    - `width, height`: Breite und Höhe entweder in Pixel oder in % (der Bildschirmfläche). Um das Design responsiv zu halten, d.h. dynamisch an unterschiedliche Bildschirmgrößen anpassbar, empfiehlt es sich, mit relativen Werten (also %) zu arbeiten, wo immer möglich.
    - `float`: Positionierung, entweder `left` (links vom Text), `right` oder `center`.
    - `alt`: Alternativtext (falls Bild nicht geladen werden kann und für Screenreader; bitte immer hinzufügen)

Das Einfügen eines Bilds sähe dann z.B. so aus:

 `<img src="smiley.gif" alt="Smiley face" style="float:left;width:30%;">`


## Videos

Videos können sehr einfach eingebunden werden, indem man die Embed-Links der jeweiligen Mediathek (HHU Mediathek oder Youtube) copy&pastet.


## Ausklappbare Passagen

An einigen Stellen in den Tutorials gibt es vertiefende Passagen, die defaultmäßig "eingeklappt" (*collapsed*) sein sollen. Das geht recht einfach mit einem sog. Akkordeon:

```{html}
<button class="accordion">Mehr dazu</button>

<div class="panel">

    <p> Text Text Text</p>

</div>


```

Mehr dazu findet sich z.B. bei [W3 Schools](https://www.w3schools.com/howto/howto_js_accordion.asp).





