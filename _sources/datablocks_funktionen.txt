.. include:: includes.rst

datablocks Funktionen
=====================

.. revealjs:: datablocks Funktionen

    Ein kurzer Einblick in die Funktionsweise von datablocks

 .. rv_small::
    Mit |right| geht es weiter...

    Erstellt vom `useblocks team <http://useblocks.github.io>`_

    Zu den anderen :ref:`start`

.. revealjs::

    .. revealjs:: Metriken und Kennzahl: Teil 1

        .. linechart::

            teamA: 15, 35, 20, 40
            teamA.color: ffcc00
            teamA.axis: x
            teamA.axis_label: "2w ago", "today"
            teamB: 60, 75, 60, 30
            teamB.color: A2AB58
            teamC: 10, 26, 32, 26
            teamC.color: 67BCDB
            teamD: 20, 60, 50, 80
            teamD.color: E44424

        Beantworten Metriken alle Fragen?

        .. rv_small::
            - Wer misst die Metrik?
            - Wer braucht die Metrik?
            - Was sind gute/schlechte Zahlen?
            - Wie verbessert/verschlechtert man die Metrik?
            - Welches Ziel soll erreicht werden?
            - ...

    .. revealjs:: Metriken und Kennzahl: Teil 2

        datablocks BI Extensions

        .. rv_small::
            | datablocks erweitert Metriken um relevante Informationen und Funktionen.
            | Und sorgt so dafür, dass ein Unternehmen auf mehr Herausforderungen
            | schneller und zuverlässiger reagieren kann.

            Informationen und Referenzen, die datablocks verwaltet:
        .. uml::

            !include ../diagrams/datablocks_bi.puml

.. revealjs::

    .. revealjs:: Kennzahlen-SW-Landschaft: Teil 1

        .. uml::

            !include ../diagrams/metric_services.puml

        .. rv_small::

            =============  ==========  ================ ============
              Collectors    Storages    Dashboards       Suites
            =============  ==========  ================ ============
            logstash        influxdb     kibana          Prometheus
            TCollector      opentsdb     grafana         Jasper
            Heka            Graphite     Graphite-Web    Pentaho
            Zato            KairosDB     Dashing
            fluentd         SciDB
            Scrapy          graylog
            Nutch
            =============  ==========  ================ ============

            Und nicht zu vergessen: IBM, SAP, Oracle, Microsoft, Qlik, ...


    .. revealjs:: Kennzahlen-SW-Landschaft: Teil 2

        datablocks Service Integration

        .. rv_small::
            datablocks integriert sich in bestehende SW-Landschaften,
            ohne laufende Abläufe oder Prozesse zu gefährden.

            Dadurch spart ein Unternehmen hohen Umstellungskosten,
            kann unterschiedliche und bedarfsspezifische Lösungen einsetzen
            und kann auch in Zukunft bei der SW-Aufwahl frei agieren.

        .. uml::
            !include ../diagrams/datablocks_services.puml

        .. rv_small::
            datablocks bietet eine gemeinse Web-Oberfläche für alle verbundenen (Teil-)Lösungen an.


.. revealjs::

    .. revealjs:: Kennzahlen Reports: Teil 1

        Verbreiteste Lösung: E-Mails!

        .. uml::

           !include ../diagrams/current_distribution.puml


    .. revealjs:: Kennzahlen Reports: Teil 2

        datablocks Report Distribution

        .. rv_small::
            datablocks bietet zahlreiche Kanäle zum Erreichen der notwendigen Kennzahlen-Empfänger an.

            Dadurchch sparen Unternehmens-Mitarbeiter viel Zeit, da sie nur die Zahlen bekommen, die sie interessieren, und
            weil die Zahlen in ihre täglichen Arbeitswerkzeugen geliefert werden.

        .. uml::

           !include ../diagrams/datablocks_distribution.puml


.. revealjs:: datablocks Funktionen

    datablocks BI Extensions

    datablocks Service Integrations

    datablocks Report Distribution

