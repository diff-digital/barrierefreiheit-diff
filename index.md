## Beispiel: Alternativtexte für Links

Link mit klarer Beschreibung für Screenreader-Nutzer

```html
<a href="info.html" aria-label="Mehr Informationen über unser Produkt">
	Mehr Info
</a>
```

## Beispiel: Alternativtexte für Bedienelemente

Button mit Alternativtext

```html
<button aria-label="Suchen">
	<img src="search_icon.png" alt="" />
</button>
```

## Beispiel: Alternativtexte für Grafiken und Objekte

Bild mit Alternativtext

```html
<img src="dog.jpg" alt="Ein fröhlicher Hund im Park" />
```

Objekt ohne relevante visuelle Information

```html
<img src="decoration.png" alt="" />
```

## Beispiel: Alternativen für CAPTCHAs

CAPTCHA mit alternativen Zugangsmethoden

```html
<div>
	<img src="captcha.jpg" alt="CAPTCHA Bild" />
	<button onclick="requestAudioCaptcha()">Audio-CAPTCHA anfordern</button>
</div>

<p>
	Neben dem visuellen CAPTCHA sollte eine alternative Methode wie ein
	Audio-CAPTCHA zur Verfügung gestellt werden.
</p>
```

Neben dem visuellen CAPTCHA sollte eine alternative Methode wie ein Audio-CAPTCHA zur Verfügung gestellt werden.

## Beispiel: Formulare und Eingabefelder

Formular mit beschrifteten Eingabefeldern für Screenreader-Nutzer

```html
<form>
	<label for="name">Name:</label>
	<input type="text" id="name" name="name" required />

	<label for="email">E-Mail:</label>
	<input type="email" id="email" name="email" required />

	<button type="submit">Registrieren</button>
</form>
```

## Beispiel: Vorlesefunktion

```html
<script>
	// JavaScript-Funktion, um Text vorzulesen
	function readAloud(text) {
		const speech = new SpeechSynthesisUtterance(text);
		window.speechSynthesis.speak(speech);
	}
</script>

<p>HTML-Element, das vorgelesen werden soll</p>
<p id="textToRead">Dies ist ein Beispieltext.</p>
<button onclick="readAloud(document.getElementById('textToRead').innerText)">
	Text vorlesen
</button>
```

## Beispiel: Kontrasterhöhung und Farbschemata

```html
<script>
	// JavaScript zum Umschalten des Farbschemas
	function toggleHighContrast() {
		document.body.classList.toggle('high-contrast');
	}
</script>

<style type="text/css">
	// CSS für das hohe Kontrast-Schema
	.high-contrast {
		background-color: black;
		color: white;
	}
</style>
```

## Beispiel: Anpassung der Schriftgröße

```html
<button onclick="toggleHighContrast()">Kontrast erhöhen</button>

<h2>Beispiel: Anpassung der Schriftgröße</h2>
<script>
	// JavaScript zum Ändern der Schriftgröße
	function changeFontSize(size) {
		document.body.style.fontSize = size + 'px';
	}
</script>

<p>HTML-Steuerung für die Schriftgröße</p>
<button onclick="changeFontSize(18)">Schriftgröße: Groß</button>
<button onclick="changeFontSize(12)">Schriftgröße: Klein</button>
```
