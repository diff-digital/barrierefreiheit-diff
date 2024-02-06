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

## Beispiel: Transkripte für Audiodateien

Stellen Sie ein schriftliches Transkript der Audiodatei zur Verfügung. Dies ermöglicht Personen mit Hörbeeinträchtigungen, den Inhalt zu verstehen.

```html
<audio controls src="audiofile.mp3"></audio>
<a href="transcript.txt">Download Transkript</a>
```

## Beispiel: Untertitel für stumme Videos:

Integrieren Sie Untertitel in stumme Videos, damit der Inhalt auch ohne Ton verständlich ist.

Beschreibende Audioüberlagerungen: Für stumme Videos könnten Sie auch eine beschreibende Audioüberlagerung hinzufügen, die den visuellen Inhalt erklärt.

```html
<video controls>
	<source src="stummfilm.mp4" type="video/mp4" />
	<track src="subtitles.vtt" kind="subtitles" srclang="de" label="Deutsch" />
</video>
```
