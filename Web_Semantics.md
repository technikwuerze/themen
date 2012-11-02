# Web Semantics

## Leadtext

Microformats.org wird 7, Twitter veröffentlicht “Twitter Cards” und Google baut auf Schema.org... Aber was von den vielen Meta und Web-Semantiken braucht man nun wirklich?

## Inhalt

* Staffel 5 – Warum dauert das immer so lange bei euch?
* OpenWeb-Podcast nun Bestandteil von Technikwürze (Themen)
* Überblick
* Microformats v2
* Twitter Cards
* Microdata/RDFa und Schema.org
* OpenGraph Protocol
* Dublin Core
* klassische Meta-Tags
* Unterschied Websemantiken und Meta-Informationen
	* Websemantiken
		* Microformats und Schema.org zeichnen “sichtbare” Informationen aus
		* Hauptsächlich von Suchmaschinen benutzt
	* Meta-Informationen
		* Sprechen meist für die ganze Seite und müssen nicht im direkten Verhältnis zum Text stehen
		* klassiche Meta-Informationen & Dublin Core von Suchmaschinen
		* OGP und Twitter Cards von Social Networks.
	* Was braucht man und warum
		* Meta-Tags
			* Twitter Cards sind proprietär und Twitter, Google und Facebook unterstützen auch OGP
			* OpenGraph vs. Meta Tags
				* Meta-Tags/Dublin Core meistens SEO versäucht
				* OGP meist für Social-Networks um mehr über einen Link zu erfahren (Bild und Beschreibung)
		* Websemantics
			* Da Google, Yahoo und Microsoft Microdata/RDFa und Schema.org vorschlagen sollte man sich daran orientieren
			* Microformats “erziehen” Webentwickler, semantisches HTML zu schreiben und können ruhig auch zusätzlich zu Schema.org eingesetzt werden, sind aber zu fehleranfällig um noch ernsthaft mit Microdata und RDFa konkurrieren zu können
	* Empfehlungen
		* Meta-Tags wie gewohnt beibehalten (SEO)
		* Für Social-Networks das OpenGraph Protocol
		* Für Suchmaschinen Schema.org
		* Für schönes HTML Microformats

## Lose Ideen (in Form bringen)

* was ich mir zu dem semantik thema dachte: einen kleinen überblick geben, wie was funktioniert... was man einsetzen sollte (eine empfehlung) und was keinen sinn macht.
* also so in dem stil: microformats sind gut für semantisches html (sollten aber nicht für maschinenlesbare semantik benutzt werden, weil zu fehleranfällig), schema.org für suchmaschinen (microdata) und OGP für abstracts (google+ facebook, twitter)