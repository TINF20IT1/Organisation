#Userstorrys

|Titel | Customizing von Figuren|
| -------- |:----------------------------------------------|
|Beschreibung | Der Benutzer soll in der Lage sein, seine Figur anzupassen und Kosmetika wie Umhänge, Hüte oder generelle Klamotten ändern zu können.Hierzu wird vor dem Spielstart bzw. Runden-/Level-start im Menü eine Option zum Ändern vorhanden sein.Während des Spielfortschritts können durch Sammeln von Münzen/Items weitere Kosmetika freigeschaltet werden.Diese Daten lokal gespeichert. Beim Anmelden am Host werden die aktuell ausgewählten Items (via ID?) von lokal zu Host übertragen.Wahl von Items auf lokalem Gerät, Timer (für Änderung) zählt auf Host, dadurch nur was gerade ausgewählt  (Ids?) wird, wird an Host übertragen.Avatar: unterschiedliche Farben, Muster, Name über Figur, muss gut erkennbar sein, da viele Avatare auf dem Bildschirm, keine zwei gleichen Avatare|
|Schätzung| |
|Priorität| 20|

|Titel | Konzept Teammodus|
| -------- |:----------------------------------------------|
|Beschreibung |Alle Modi des Spiels sollen auch in 2-3 Teams gespielt werden können. Der Teammodus soll auf dem Startbildschirm auswählbar sein.Erst mal jeder gegen jeden. Es kann auf dem Startbildschirm ausgewählt werden ob man Teamsmodus spielen will und es kann den jeweiligen Teams beigetreten werden. Mitglieder des eigenen Teams können nicht durch Items der Teammitglieder verletzt werden. Errungenschaften werden im Team durch die Teammitglieder geteilt: 10 Münzen/3Teilnehmer = 3.4 Münzen pro Teammitglied|
|Schätzung| |
|Priorität| |

|Titel | Spielmodi|
| -------- |:----------------------------------------------|
|Beschreibung |Alle Levels können in verschiedenen Modi gespielt werden. Modibeispiele: Fight, Speed, Quest, Monster. Zwei Modi sollen erarbeitet werden. Zuerst wird der Hauptmodus umgesetzt, ob der zweite noch implementiert werden kann wird sich zeigen.
|Schätzung| |
|Priorität| |

|Titel |Modus: Speed |
| -------- |:----------------------------------------------|
|Beschreibung | Speed: Landschaft -> Bildschirm bewegt sich immer weiter zunehmen schneller. Hindernisse in der Landschaft, Sprunghindernisse, etc	Für Spieler endet Level, wenn er nicht mehr mitkommt und außerhalb des sichtbaren Bereichs gerät (Schlucht, zu langsam, etc.)Für Teammodus: last man standing Keine direkte Spielerinteraktion Turniermodus, Belohnung nach Zeit, kann Verbesserungen kaufen? Ist nur für das jeweilige Turnier gültig Für gewonnenes Turnier gibt's eine Anzahl Münzen für die wiederum generell für den Avatar etwas gekauft werden kann.

|Schätzung| |
|Priorität| |



|Titel |Modus Quest |
| -------- |:----------------------------------------------|
|Beschreibung | Aufgaben, die man ausführen kann Feste Welt wird angezeigt, man kann nicht raus. Z.B: Sammle gewisse Anzahl Münzen ein, Schubse gewisse Anzahl (Player) von Figuren vom Spielfeld Hier findet Spielerinteraktion statt (schubsen, abschiessen). Gewonnen hat wer aktuellen Quest als erster abgeschlossen hat. Belohnung Anzahl Münzen je nachdem wieviel gesammelt, geschubst, etc.
|Schätzung| |
|Priorität| |

|Titel | Modus Schnellster gewinnt|
| -------- |:----------------------------------------------|
|Beschreibung |Wer am schnellsten ist gewinnt, ein Level wird durchgerannt, Hindernisse müssen überwunden werden.Keine Spielerinteraktionen, Modus Splitscreen 1 bis 4 Spieler, Gewinn einer bestimmten Anzahl Münzen bei erster im Ziel,Weitere Münzen im Level abzugreifen.
|Schätzung| |
|Priorität| |

|Titel | Setting/Theme |
| -------- |:----------------------------------------------|
|Beschreibung | Moderne Scify-Welt, Verschiedene Teilabschnitte wechseln durch Portale  (Fremder Planet, Monde und Planet im Hintergrund, Raumstation/ Raumschiff, unterirdischer Bunker)
|Schätzung| |
|Priorität| 20 |

|Titel |Steuerung/Movement |
| -------- |:----------------------------------------------|
|Beschreibung | Links und Rechts via Joystick (linke Panelhälfte), Jump und Slide via Wischen (hoch und runter auf rechter Panelhälfte); Tastatur)  ggf. Items oder Attack via Tippen auf rechter Hälfte, Events mit Tastenkombination? (Debug für Host viaTastatur)
|Schätzung| |
|Priorität|10 |

|Titel | Smartphone-App|
| -------- |:----------------------------------------------|
|Beschreibung | Autarke App, die die Steuerung des Clients via Steuerpanel ermöglicht und die Verbindung mit Host herstellt. Regelt Datenspeicherung  und Visualiserung (via GUI) für das Customizing und nutzerspezifische Daten. 
|Schätzung| |
|Priorität|10 |

|Titel | Host|
| -------- |:----------------------------------------------|
|Beschreibung | Levelbereitstellung und Visualisierung auf Monitor bzw. via Beamer, wobei alle Charaktere dargestellt werden (siehe "Customizing von Firguren"). Ein- und Ausgaben werden berechnet und die gesamte Spiellogik prozessiert. Kommuniziert mit Clients, läd zu Beginn Spielerdaten und on Runtime die Controls. Speichert nichts permanent, keine Datenbank (alles auf Clients).
|Schätzung| |
|Priorität| 10|

|Titel | Datenübertragung |
| -------- |:----------------------------------------------|
|Beschreibung | Connecting: Verbindungsaufbau zwischen Smartphone-App und Host.  In diesem Rahmen werden die Playerdaten (siehe "Customizing von Figuren") an den Host gesendet.  Die Verbindung soll kabellos erfoogen. Datenübertragung: Es muss eine möglichst geringe Verzögerung der Eingabesignale aller einzelnden Cleints (senden ohne Bestätigung?) gegeben sein. Rückinformationen müssen aus anderen User Stories zusammengeführt werden. 
|Schätzung| |
|Priorität| 10 |

|Titel | Hintergrundmusik |
| -------- |:----------------------------------------------|
|Beschreibung | Soll einladend und melodisch sein und sehr catchy sein und je nach Level unterschiedlich sein (einschließlich Main Theme). Soll auf Spielspannung reagieren 
|Schätzung| |
|Priorität| 20 |

|Titel |Main Theme |
| -------- |:----------------------------------------------|
|Beschreibung | Das gesamte Spiel sollte einem Thema unterliegen (z.B. Weltraum). Alle Designelemente sollen diesem Theme unterliegen
|Schätzung| |
|Priorität|10 |

|Titel |Feedbacksound |
| -------- |:----------------------------------------------|
|Beschreibung | größere Aktionen (z.B. im Menü einen Knopf auswählen, oder im Spiel ein Item einlösen) sollen mit einem Vibrationsfeedback im Controller bestätigt werden
|Schätzung| |
|Priorität|20 |

|Titel | Levelgeneration |
| -------- |:----------------------------------------------|
|Beschreibung | Die Level werden designed und werden mit verstreichender Zeit schwieriger. Die Level haben sich in ihrer  Gestaltung dem Theme zu unterwerfen
|Schätzung| |
|Priorität| 10 |

|Titel | Hintergründe|
| -------- |:----------------------------------------------|
|Beschreibung | verschiedene Level sollen unterschiedliche Hintergründe haben
|Schätzung| |
|Priorität| 40|

|Titel |Levelgröße |
| -------- |:----------------------------------------------|
|Beschreibung |Die Level sollten kurz, aber spielbar sein. Zeitrahmen ca. 3 Minuten
|Schätzung| |
|Priorität| 25|

|Titel |Schwierigkeit der Level |
| -------- |:----------------------------------------------|
|Beschreibung | Höhere bzw. weitere Level werden sind schwieriger zu spielen als die ersten Level
|Schätzung| |
|Priorität|25 |

|Titel | Host Startbildschirm|
| -------- |:----------------------------------------------|
|Beschreibung | Auf dem Startbildschirm des Hosts soll es Knöpfe für folgende Dinge geben: Levelauswahl, Teammodusauswahl, Musik-Muten, Einstellungen, Spielstart(?), Spiel-beenden
|Schätzung| |
|Priorität| 15 

|Titel | Controller Startbildschirm
| -------- |:----------------------------------------------|
|Beschreibung | Hier können Customizations ausgewählt werden, sowohl die Verbindung hergestellt werden (jeweils über eigene Menüs). Wird bei Start des Spiels automatisch durch den Spielbildschirm ersetzt.
|Schätzung| |
|Priorität| 15 |

|Titel | Items |
| -------- |:----------------------------------------------|
|Beschreibung | Sind Gegenstände, die im Spiel eingesammelt werden, verpassen dem Spieler besondere Fähigkeiten (erhöhte Geschwindigkeit, doppelter Sprung, etc). Wirken nach Einsammlung 15 Sekunden lang und verfallen danach
|Schätzung| |
|Priorität|40 |

|Titel | Abfolge des Spiels|
| -------- |:----------------------------------------------|
|Beschreibung | Nach Start des Anwendung öffnet sich das Menü. Von dort aus wird das Spiel gestartet. Nach Beendigung des Levels gibt es einen Bildschirm, der die Ergebnisse des Levels anzeigt. Von dort kann man zum Startbildschirm zurück
|Schätzung| |
|Priorität| 25 |

|Titel | Beispiel|
| -------- |:----------------------------------------------|
|Beschreibung | z. B.|
|Schätzung| vorschlag |
|Priorität| 22 |
