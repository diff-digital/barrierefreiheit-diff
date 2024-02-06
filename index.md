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
