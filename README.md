# PICO-Twig-Modul-Sticky-Post

Das Modul liest alle Beiträge der Webseite aus allen Unterordnern und Subkategorien aus, die mit dem Meta-Attribut `Sticky: true` gekennzeichnet sind. Ziel ist es, Beiträge für den Leser hervorzuheben und diese speziellen Beiträge auf der Startseite nach oben zu schieben (Artikel-Empfehlungen).

![](screenshot-sticky-posts.png)

## Installation ##

Das Modul kann einfach in das PICO Templateverzeichnis `templates` kopiert und von dort aus mittels:

    {% include 'sticky.twig' %}

in ein beliebiges Template eingebunden werden.

## Der PICO Beitrag ##

Damit ein Beitrag von diesem Modul verarbeitet werden kann, muss eine neues Metaattribut eingefügt werden. Setzen Sie das neue Attribut `Sticky: true` oder `Sticky: false` in den Meta-Bereich des Beitrags ein. So gekennzeichnete Beiträge können dann durch das Twig-Template nach oben auf die Startseite geschoben werden, egal in welchem Unterordner sie sich befinden
