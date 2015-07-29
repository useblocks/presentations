.. include:: includes.rst

datablocks Einleitung
=====================

.. revealjs:: datablocks Einleitung

    Eine kurze Einleitung in die Motivation von datablocks


 .. rv_small::
    Mit |right| geht es weiter...

    Erstellt vom `useblocks team <http://useblocks.github.io>`_

    Zu den anderen :ref:`start`

.. revealjs::

   .. revealjs:: Heutige Arbeitsweise Teil 1

      .. uml::
         package "Abteilung Entwicklung" {
            object Wertschöpfung {
            Zu kontrollierende Wertschöpfung
            }

            object Sammlung {
               Sammlung von Rohdaten
            }
            object Analyse {
               Analyse und Definition von Metriken
            }
            object Speicherung {
               Speicherung von Metriken
            }
            object Anzeige {
               Bereitstellung von Metriken
            }
         }

         Wertschöpfung .> Sammlung
         Sammlung -> Analyse
         Analyse -> Speicherung
         Speicherung -> Anzeige



   .. revealjs:: Heutige Arbeitsweise Teil 2

      Bei mehreren Wertschöpfungsketten in unterschiedlichsten Abteilungen
      finden sich zahlreiche, unterschiedlichste Toolketten im Einsatz.

      .. uml::
         package "Abteilung Entwicklung" {
            object Suite_1 #FFCC00
         }
         package "Abteilung Finanzen" {
            object Tool_A #434344
            object Tool_B #456723
         }
         package "Abteilung Personal" {
            object Tool_C #896344
            object Tool_D #134534
            object Tool_E #456345
         }
         package "Abteilung Vertrieb" {
            object Suite_2 #757883
            object Tool_F  #793564
         }


      Abteilungs- und toolübergreifende Verweise oder gar Analysen sind kaum möglich.


   .. revealjs:: Heutige Arbeitsweise Teil 3

      Auch die erhobenen Metriken und ihre weiterführende Informationen sind nicht einheitlich definiert und
      verwend- oder vergleichbar.

      .. rv_small::
         Unterschiedliche Definition von Qualität

         Unterschiedliche Formeln zur Berechnung von Reakationsgeschwindigkeiten

         Fehlende Hintergrundinformation zu: guten/schlechten Bereichen, Verantwortlichkeiten, Einfluss auf Firmenziele, ...


.. revealjs::

    .. revealjs:: Arbeitsweise mit datablocks Teil 1

       datablocks Integration

        .. rv_small::
           datablocks verbindet sich mit sämtlichen Kennzahlen-
           Tools und macht eine gemeinschaftliche Verwendung und Pflege
           möglich.

           Sie können für jeden Aufgabenbreich ein anderes Tools einsetzten,
           so dass Sie in der lage sind für die Erhebung das Tool von Abteilung A,
           die Überwachung etwas von Abteilung B und für die Steuerung ein Werkzeug der
           Abteilung C zu verwenden.

           BILD mit EBENEN von db

           (Spätere Punkte: open source, )


    .. revealjs:: Arbeitsweise mit datablocks Teil 2

       datablocks Data Extensions

       .. rv_small::
          Egal, ob ein tool sämtliche Daten schon selbst erhoben hat
          oder ob es nur die nackten Zahlen liefert. datablocks erlaubt ihnen
          sämtliche Kennzahlen mit Information zu verfeinern und diese für
          die nachgelagerte Tätigkeiten mitzuverwenden.

          Z.B den Aktions-Verantwortlichen bei schlechten Zahlen zu informieren.

          (spätere Punkte: Verständnis, Rollen, Verlinkung zu anderen Systemen, Statisitken und Verwendung)
