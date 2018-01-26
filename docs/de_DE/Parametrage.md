Wenn Sie das automatische Hinzufügen oder Importieren der ETS4 aktiviert haben, wurden die Geräte und Befehle erstellt, es sind jedoch noch einige Parameter zu konfigurieren.
Der nachfolgende Absatz wird Ihnen helfen.

=== Gerät

Als ersten Schritt müssen Sie ein neues Gerät erstellen und benennen.
Wie bei allen Jeedom Plugins haben Sie einen Schaltfläche zum hinzufügen, links neben Ihrem Fenster.

image::../images/Configuration_equipement.jpg[]

Dieses neue Gerät muss parametriert werden.

* KNX Gerätename : Der Name wurde bereits vorgeschlagen, aber Sie haben die Option ihn zu ändern.
* Physische Geräteadresse : Dieses Element ist nicht sehr wichtig und kann leer bleiben.
* Eltern Objekt : Dieser Parameter ermöglicht das hinzufügen von Geräten in einem Jeedom-Objekt.
* Kategorie : Ordnet das Gerät in eine Kategorie ein.
* Sichtbar : Erlaubt das Gerät auf den Armaturenbrett sichtbar zu machen.
* Aktivieren : Erlaubt das Gerät zu aktivieren.
* Max Zeitraum zwischen 2 Nachrichten : Dieses Feld ermöglicht die Verwendung von Geräten, die mit Batterie betrieben werden, es legt den Zeitraum fest, den Jeedom zwischen 2 Nachrichten warten muss, bevor es Sie über ein Gefährdung einer Fehlfunktion informiert.

=== Befehle

Nachdem Ihre Geräte erstellt und konfiguriert wurde, können Sie Befehle hinzufügen.

Beispielkonfiguration

image::../images/Configuration_commande.jpg[]

==== Hinzufügen von Befehlen nach Vorlage

include::cmdTemplate.asciidoc[]

==== Befehle manuell hinzufügen

include::cmdManual.asciidoc[]