# Webentwicklung Basic

Dieses Modul zeigt die ersten Grundlagen in ``HTML`` und geht auf die funktionale Trennung des Codes ein. Weiter geht es dann mit ``php`` und der Entwicklung dynamischer Websites.

## Inhalt

1. [HTML-Grundlagen](./docs/html_grundlagen.md)
2. [Webentwicklung](./docs/web_development.md)
    1. [Funktionale Trennung von Code](./docs/web_development.md#funktionale-trennung-von-code)

## Vorbereitungen

Um richtig durchstarten zu können, müssen wir zunächst unseren Computer mit einigen Tools versorgen. Neben einer IDE sind das vor Allem ein Testserver bzw. php.

### IDE

Die IDE ist unsere Entwicklungsumgebung, die unter anderem unseren Editor enthält. IDE steht übrigens für **Integrated Development Environment**. Obwohl ich persönlich sehr gern mit JetBrains PhpStorm arbeite, empfehle ich zum Einstieg lieber eine kostenfreie IDE wie Visual Studio Code.

### PHP

Um dynamische Websites zu entwickeln kommen wir nur schwer um php herum. Php ist eine sehr leicht zu lernende und dennoch äußerst mächtige Programmiersprache, die im Gegensatz zu Java oder Javascript serverseitig interpretiert wird. Java hingegen wird lokal kompiliert.

#### Windows

Am einfachsten gelingt die Installation über XAMPP, das neben php auch einen Apache Webserver sowie einen MariaDB-Datenbank-Server enthält.

Alternativ empfehle ich die Installation über einen Paketmanager wie Chocolately:
````bash
choco install php
````