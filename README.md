# Anwendungsfall-1.03: Alarm bei zu hoher Herzfrequenz

**Name und Identifikationsnummer:** UC 1.03. - Alarm bei zu hoher Herzfrequenz

**Beschreibung:** Eine bestimmte kritische Herzfrequenz überschritten, wird der Leistungstest sofort abgebrochen.

**Beteiligte Akteure:** Diagnostiker:in, Proband:in 

**Status:** Noch nicht begonnen. Nur Geplant.

**Verwendete Anwendungsfälle:** UC 1.01. - Probandin anlegen/ UC 1.02. - Leistungstest anlegen/ UC 1.06. - Anstrengungsbewertung mittels Borg-Skala/ UC 1.07 Abbruch Leistungstest

**Auslöser:** Zu hohe Herzfrequenz

**Vorbedingungen:** UC 1.01. - Probandin anlegen/ UC 1.02. - Leistungstest anlegen

**Invarianten:** Aufzeichung der bis zum Abbruch genommenen Daten

**Nachbedingung/Ergebnis:** Abbruch des Leistungstests (UC 1.07.)

**Standartablauf:** Der Leistungstest wird durchgeführt bis die Herzfrequenz einen Maximalwert erreicht. Dann wird der Test abgebrochen.

**Alternative Ablaufschritte:** Der Leistungstest kann erfolgreich und vollständig durchgeführt werden und muss nicht wegen zu hoher Herzfrequenz abgebrochen werden.

**Hinweise:**  Die Anwendung sollte in der Lage sein, die Herzfrequenz in Echtzeit zu überwachen. Die Anwendung basiert auf Sensoren wie einen Herzfrequenzmesser. Der Schwellenwert sollte Sinnvoll festgelegt sein (basierend auf Geschlecht, Alter…) 

**Änderungsgeschichte:** 0.01 - 15.03.2024 - Till Schröter
