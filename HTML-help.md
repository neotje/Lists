### handig html help dingetje

## HTML document

alle html documenten (.html bestanden) starten met `<!DOCTYPE html>`
    geeft aan wat voor soort html (versie/variant) het bestand bevat.

de content van de html document zelf start altijd met `<html>` en eindigt met `</html>`

het gedeelde wat je te zien krijgt staat tussen `<body>` en `<body>`


Voorbeeld (heel erg simpel voorbeeld)
```html

<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>

```


-------------------------------------------------------------------------------------------------------


## HTML Elements

Een HTML element wordt gedfineerd door een begin tag en een eind tag:
```html
<tagname>Element content...</tagname>
```

# Nested HTML elementen

HTML elementen kunnen genest worden (dit betekent dat elementen andere elementen kunnen bevatten)
```html
<tagname> --> parent
    <tagname></tagname> --> child
</tagname>
```
De eind tag is erg belangrijk anders weet HTML niet waar de parent/child eindigt.


-------------------------------------------------------------------------------------------------------


## HTML attributes

HTMl attributes geven extra informatie over een html element.

* alle html elementen kunnen attributen hebben.
* Attributes geven extra informatie over het element
* Attributes staan altijd in the begin tag.
* Attributes komen meestal voor in een naam/waarde paar bijv.: naam van attribute="waarde"

bijvoorbeeld
```html
   naam="waarde"
<a href="https://www.hop-it.nl">Leuk websijtje</a>
```
