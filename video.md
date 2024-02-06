## Beispiel: Wiedergabe von Untertiteln

Implementieren Sie Untertitelspuren in Ihre Videoelemente mittels <track>-Tags.

```html
	<video controls>
		<source src="movie.mp4" type="video/mp4">
		<track src="subtitles_de.vtt" kind="subtitles" srclang="de" label="Deutsch">
	</video>
```

## Beispiel: Untertitel-Anpassung

Erlauben Sie Benutzern, die Einstellungen für Untertitel über CSS zu ändern, zum Beispiel Schriftgröße und Farbe.

```css
::cue {
    font-size: 16px;
}
```

## Beispiel: Wiedergabe von Audiodeskription

Erlauben Sie Benutzern, die Einstellungen für Untertitel über CSS zu ändern, zum Beispiel Schriftgröße und Farbe.

```html
<audio controls>
    <source src="audio_description.mp3" type="audio/mpeg">
</audio>
```
