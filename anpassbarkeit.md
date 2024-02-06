## Beispiel: Korrekte Verwendung von Überschriften

Nutzen Sie h1 bis h6 Tags, um eine klare hierarchische Struktur zu schaffen.

```html
<h1>Titel der Seite</h1>
<h2>Untertitel Abschnitt 1</h2>
<h3>Untertitel Abschnitt 1.1</h3>
```

## Beispiel: HTML-Strukturelemente für Listen

Verwenden Sie ul für ungeordnete Listen und ol für geordnete Listen mit li für Listenelemente.

```html
<ul>
    <li>Listenelement 1</li>
    <li>Listenelement 2</li>
</ul>

<ol>
    <li>Erster Punkt</li>
    <li>Zweiter Punkt</li>
</ol>
```

## Beispiel: HTML-Strukturelemente für Zitate

Nutzen Sie das blockquote-Element für Zitate, um diese hervorzuheben.

```html
<blockquote>
    <p>Dies ist ein Zitat.</p>
    <cite>Quellenangabe</cite>
</blockquote>
```

## Beispiel: HTML-Strukturelemente für Datentabellen

Verwenden Sie table, tr, th, und td Tags. Nutzen Sie scope-Attribute für Kopfzellen, um die Beziehung zu Datenzellen zu definieren.

```html
<table>
    <tr>
        <th scope="col">Kopfzeile 1</th>
        <th scope="col">Kopfzeile 2</th>
    </tr>
    <tr>
        <td>Zelle 1</td>
        <td>Zelle 2</td>
    </tr>
</table>
```

## Beispiel: Formularelemente mit Beschriftung
Verwenden Sie label-Elemente mit der for-Attribut, um Formularfelder zu beschriften.
Bei Eingabefeldern, die persönliche Daten erfassen, verwenden Sie das autocomplete-Attribut, um den Zweck des Feldes anzugeben.

```html
<label for="name">Name:</label>
<input type="text" id="name" name="name" autocomplete="name">
```
