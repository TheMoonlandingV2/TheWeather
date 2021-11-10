# --> TheWeather <--
<h1>Wetterstation auf Basis des Arduino</h1>

<h3> Inhalt </h3>
<ul style="list-stlye-type:none">
<li><a href="#kapitell">1. Einleitung</a></h2></li>
<li><a href="#kapitel2">2. Arduino und Sketch</a></h2></li>
<li><a href="#kapitel3">3. Projektentwicklung</a></h2></li>
<li><a href="#kapitel4">4. Vorstellung des Projekts</a></h2></li>
<li><a href="#kapitel5">5. Der Sketch</a></h2></li>
<li><a href="#kapitel6">6. Kritik</a></h2></li>
<li><a href="#kapitel7">7. Fazit</a></h2></li>
<li><a href="#kapitel8">8. Quellen</a></h2></li>
<br>
<h2 id="kapitell">1. Einleitung</h2>
<p>Für viele Menschen gehört es zu der Morgenroutine, nach dem Aufstehen aus dem Fenster zu gucken und die Temperatur zu schätzen, damit man sich passend anziehen kann. Oftmals verschätzt man sich und es kommt zu ungewolltem und unnötigen Stress am frühen Morgen, da es überraschend doch wärmer oder kälter ist.<br>
Für genau dieses Problem lässt sich einfache Abhilfe schaffen. Eine Wetterstation, die die Temperatur übermittelt, wäre hierfür ideal. Ein kurzer Blick auf das neben dem Bett stehende Display würde genügen, um Gewissheit über die Temperatur zu haben. Zudem könnte sie mit extra Sensoren ausgestattet sein, um für den Interessierten aktuelle Daten über die Wetterlage zu messen. 
Außerdem wäre es eine witzige Begegnung beim Aufstehen, den Vögeln mittels einer Kamera bei deren ausgibigen Körnerfrühstück zuzusehen und sich an der Natur zu erfreuen. Mit einem schönen Design stört das Futterhäuschen mit der Wetterstation und Kamera auch nicht beim Blick aus dem Fenster.
Unsere Wetterstation <b>(Name fehlt)</b> ist eine hervorragende Art das Aufstehen zu erleichtern und überflüssigen Stress zu vermeiden - so steht man gerne auf!<br></p>

<h2 id="kapitel2">2. Arduino und Sketch</h2>
<p>Der Arduino ist eine Physical-Computing-Platform, die aus Hardware- und Software besteht. Der eigentliche  Arduino besteht aus einer Platine mit Mikrocontroller, digitalen und analogen Ein- und Ausgängen. Um auf den Mikrocontroller ein Programm hochzuladen, benötigt es die Arduino-Software auf einem Computer. In diesem Programm lassen sich mit den Programmiersprachen C- und C++, die deutlich vereinfacht wurden, eigene Programme, sogenannte „Sketches“, erstellen, die dann via USB auf den Mikrocontroller hochgeladen werden können. Über diese Verbindung erhält der Arduino auch den Strom. Über diverse Ein- und Ausgänge lassen sich mit Hilfe eines Breadboards LEDs, Motoren, Sensoren und vieles mehr anschließen, mit Strom versorgen und steuern. Mit dem eingebauten Speicher lassen sich die Programme auch auf dem Mikrocontroller speichern, was damit  die Stromversorgung über einen Akku oder eine Batterie möglich macht und die Anwendungsmöglichkeiten des Arduino vervielfacht und somit den Gebrauch auch draußen ohne direkte Verbindung zum Computer ermöglicht. Für den Arduino gibt es weiteres Zubehör. Dazu zählen Sensoren aller Art, Motoren, Displays, Ethernet-Shields und Kameras. 
Von der Marke Arduino gibt es viele verschiedene Modelle des gleichnamigen Mikrocontrollers. 
In dem Projekt wurde ein Arduino UNO verwendet, der mit 7 bis 12 Volt arbeitet und 32 Kilobyte Speicherplatz hat. Zudem hat er 13 digitale Pins und 5 analoge Pins, die im Sketch sowohl als Eingang als auch als Ausgang belegt werden können. Mit verschiedenen Ground-Pins (GND) bzw. Minuspolen und den Pluspolen (5 Volt / 3,5 Volt) können Motoren, Sensoren und sonstiges auf einem Breadboard angeschlossen und mit Strom versorgt werden. Über die digitalen und analogen Pins werden diese Module ebenfalls verbunden, damit der Mikrocontroller mit diesen interagieren kann und den Sketch ausführen kann. Mit bestimmten Befehlen, zum Beispiel „Serial.print(), im Sketch lassen sich die Daten auf einem seriellen Monitor anzeigen, der im Prinzip der Monitor für den Arduino darstellt.<br></p>


<h2 id="kapitel3">3. Projektentwicklung</h2>
<p>Aller Anfang ist schwer - auch hier ist das Sprichwort uneingeschränkt anwendbar. In den ersten Stunden galt es ein passendes Projekt mit passendem Umfang zu finden.

<h2 id="kapitel4">4. Vorstellung des Projekts</h2>

<h2 id="kapitel5">5. Der Sketch</h2>

<h2 id="kapitel6">6. Kritik</h2>

<h2 id="kapitel7">7. Fazit</h2>

<h2 id="kapitel8">8. Quellen</h2>
<li>https://www.google.de/search?q=arduino+uno+layout&tbm=isch&ved=2ahUKEwidjen4lfzzAhXdg_0HHXK9Cj8Q2-cCegQIABAA&oq=Arduino+UNO+lay&gs_lcp=CgNpbWcQARgAMgUIABCABDIECAAQHjIGCAAQCBAeMgYIABAIEB4yBggAEAgQHjIGCAAQCBAeMgYIABAIEB4yBggAEAgQHjIGCAAQCBAeMgYIABAIEB46BwgAELEDEEM6BAgAEENQ9gpY3BhguyVoAHAAeACAATKIAeoBkgEBNZgBAKABAaoBC2d3cy13aXotaW1nwAEB&sclient=img&ei=eX2CYd3sKt2H9u8P8vqq-AM&bih=969&biw=1920&hl=de#imgrc=8y0v8UQcusgjCM</li>
