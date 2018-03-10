# CKEditor 4 - The best browser-based WYSIWYG editor Plugins for DZCP

## Installation ( Test Runtime )

Zum Testen muss die CKEditor Version 4.8 in den Hauptordner des Projekts kopiert werden.

Achtung: 
Im Ordner Plugins befindet sich eine Modifizierte Version des bbcode Plugins vom CKEditor, dieser sollte nicht überschrieben werden.

## Tests

Zum Testen werden HTML Dateien angelegt die alle Anweisungen für den CKEditor enthalten sowie statische Texte usw.

Beispiele sind:

bbcode-dzcp-youtube-test-01.html => HTML to BBCode Test ( OK )

oder

bbcode-dzcp-youtube-test-02.html => BBCode to HTML Test ( OK )

## Tags die noch als Plugins/Menu in den CKEditor eingefügt werden sollen ( BBCode bereits in DZCP funktionsfähig )

## Youtube TAGs
[youtube]xxxxx[/youtube] //Standard Youtube Player

[youtube height=200 width=300]xxxxx[/youtube] //Mit Angabe von Höhe und Breite

[youtube autoplay=1]xxxxx[/youtube] //Startet das Video automatisch

[youtube allowfullscreen=1]xxxxx[/youtube] //Kann im Vollbild-Modus verwendet werden

[youtube nocookie=1]xxxxx[/youtube] //Keine Cookies von Youtube zugelassen

[youtube rel=0]xxxxx[/youtube] //Vorschläge am Ende des Videos einblenden

[youtube controls=0]xxxxx[/youtube] //Steuerungs Elemente wie Play & Stop usw. ausblenden

[youtube responsive=1]xxxxx[/youtube] //Verwende responsive style ( noch keine Idee wie das in bbcode umgesetzt werden kann )


Full Options example:

[youtube autoplay=1 allowfullscreen=1 nocookie=1 rel=0 controls=0 responsive=1 height=200 width=300]1MLRCczBKn8[/youtube]

## DivX Player TAG
[divx]http://xxx.xx/video123.divx[/divx] //Standard Player

[divx height=200 width=300]http://xxx.xx/video123.divx[/divx] //Mit Angabe von Höhe und Breite

[divx autoplay=1]http://xxx.xx/video123.divx[/divx] //Startet das Video automatisch

Full Options example:

[divx height=200 width=300 autoplay=1]http://xxx.xx/video123.divx[/divx]

## HTML 5 Video Player TAG
[video]http://xxx.xx/video123.mp4[/video] //Standard Player

[video height=200 width=300]http://xxx.xx/video123.mp4[/video] //Mit Angabe von Höhe und Breite

[video autoplay=1]http://xxx.xx/video123.mp4[/video] //Startet das Video automatisch

Full Options example:

[video height=200 width=300 autoplay=1]http://xxx.xx/video123.mp4[/video]

## Vimeo Player TAG
[vimeo]xxxxxxxx[/vimeo] //Standard Player

[vimeo height=200 width=300]xxxxxxxx[/vimeo] //Mit Angabe von Höhe und Breite

[vimeo autoplay=1]xxxxxxxx[/vimeo] //Startet das Video automatisch


Full Options example:

[vimeo height=200 width=300 autoplay=1]xxxxxxxx[/video]

## Golem Player TAG
[golem]xxxxxxxx[/golem] //Standard Player

[golem height=200 width=300]xxxxxxxx[/golem] //Mit Angabe von Höhe und Breite

[golem autoplay=1]xxxxxxxx[/golem] //Startet das Video automatisch


Full Options example:

[golem height=200 width=300 autoplay=1]xxxxxxxx[/golem]

## Text Hiden TAG
[hide]Text1234[/hide] //Text ist ab Level 1 zu sehen

[hide level=2]Text1234 show on >= level 2[/hide] //Text ist ab Level 2 zu sehen

[hide level=3]Text1234 show on >= level 3[/hide] //Text ist ab Level 3 zu sehen

[hide level=4]Text1234 show on == level 4[/hide] //Text ist ab Level 4 zu sehen

## License CKEditor

Copyright (c) 2003-2017, CKSource - Frederico Knabben. All rights reserved.

For licensing, see LICENSE.md or [https://ckeditor.com/legal/ckeditor-oss-license](https://ckeditor.com/legal/ckeditor-oss-license)

## License Youtube Embed Plugin

Jonnas Fonini <jonnasfonini@gmail.com>
