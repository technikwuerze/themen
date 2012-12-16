# App vs Webapp

## Teilnehmer

* Max Mustermann
* John Appleseed
* John Doe
* Lieschen Müller

## Beschreibung

Es wurde bereits viel und oft über die Unterschiede von Apps und Webapps auf Smartphones und deren Vor- und Nachteile diskutiert, jedoch gibt es auch in diesem Bereich Entwicklungen und Fortschritte. Mobile Browser werden regelmäßig schneller und standardkonformer.
Ich (eine Person auf die hier aufgrund von Irrelevanz nicht näher eingegangen wird) habe vor langer Zeit sowohl Webapps als auch Apps für iOS programmiert. Damals gab es noch viele Dinge, die mit Webapps viel schwieriger waren. Um nur einige zu nennen, waren sogar einfache "position:fixed" CSS-Angaben auf mobilen Geräten nicht möglich. Auch im Bereich Offline-Speicher für Webseiten hat sich einiges getan. Ebenso waren Dateiuploads von mobilen Browsern bis vor kurzer Zeit nicht möglich.
Vor kurzem habe ich einen eigenen CSS3-Editor/Generator gebaut und auch mittels cache.manifest Offlinefähig gemacht. Mittels Media Queries ließ sich die Bedienbarkeit auf dem iPad sehr einfach um ein vielfaches vereinfachen. Jedoch gibt es noch immer viele Dinge, die nur mit einer echten App erledigt werden können. Dies bringt mich zu den Nachteilen von Webapps. Nicht nur, dass JavaScript Code um einiges langsamer ausgeführt wird als Objectiv-C oder dass Sensordaten in Nativen Apps deutlich genauer und schneller verarbeitet werden können. Auch lässt sich eine Webapp viel schwieriger monetarisieren, was mir bei meiner Webapp aber auch egal war. Auch die Aufmerksamkeit auf die App durch eine Platzierung im AppStore ist ein Vorteil Nativer Apps. Natürlich könnte die fehlende Aufmerksamkeit für meine Webapp auch an der Qualität meines CSS-Editors liegen oder an der relativ kleinen Zielgruppe, jedoch sind zwei bis drei Seitenaufrufe pro Tag zu wenig, um einen Webspace oder gar Server in einem Rechenzentrum zu rechtfertigen. Zwei bis drei Hits pro Tag würde auch einen Raspberry Pi oder einen Arduino mit Ethernetshield an der privaten DSL-Leitung nicht auslasten.
Ein weiteres damit zusammenhängendes Diskussionsthema wären die Fortschritte von Libs, die es ermöglichen Webapps in den AppStore einzureichen. Was soll man von Phonegap/Cordova, Titanium und Konsorten halten? Wann ist die Verwendung solcher Lösungen "sinnvoll"? Warum setzen selbst riesige Firmen wie Facebook auf diese Zwitterlösungen mittels einer UIWebView statt einer richtigen App oder einer richtigen WebApp? ...
Nun ja, das war es eigentlich auch schon. Ziel dieses Textes war es ja nur, euch für die Technikwürze ein zu diskutierendes Thema zu geben.

p.s. ich finde es Toll, dass es mit Technikwürze nun wieder etwas regelmäßiger weitergehen soll! Prima, macht weiter so! Danke! Falls Ihr weitere Themenvorschläge und Diskussionsansätze wünscht, kann ich gerne noch mehr Pull-Requests schicken.

## Überblick

* Cache Manifest
* Dateiupload
* position:fixed
* Viewport
* media queries
* Retina Displays
* apple-touch-icon
* apple-touch-startup-image
* *Phonegap / Apache Cordova*
* ...
