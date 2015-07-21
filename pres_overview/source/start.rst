datablocks overview
===================

.. revealjs:: What is datablocks

    A rough overview about its functions

 .. rv_small::

    Created by the `useblocks team <http://useblocks.github.io>`_

.. revealjs::

    .. revealjs:: How a metric becomes a Business Indicator

        .. rv_small::
            Our datablocks vision

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

        .. rv_small::
            - What is good? What is bad?
            - Which Team is in the lead?
            - For what is it good for?
            - Who is interested in this?

    .. revealjs:: datablocks BI Extensions


        .. uml::

            !include ../diagrams/datablocks_bi.puml


.. revealjs::

    .. revealjs:: metric service landscape

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

            And do not forget: IBM, SAP, Oracle, Microsoft, Qlik, ...


    .. revealjs:: datablocks Service Integration

        datablocks integrates in existing service landscapes and extends them with special functions.

        .. uml::
            !include ../diagrams/datablocks_services.puml

        .. rv_small::
            And it provides an overall Web User Interface for all services.

            Without disabling direct access to their specific Interfaces (Browser, APIs, ...)

.. revealjs::

    .. revealjs:: Current meaning of Reporting

        E-Mail me!

        .. uml::

           !include ../diagrams/current_distribution.puml


    .. revealjs:: datablocks Report Distribution

        .. uml::

           !include ../diagrams/datablocks_distribution.puml


.. revealjs:: datablocks USP

    .. rv_small::

        We have three...

    datablocks BI Extensions

    datablocks Service Integrations

    datablocks Report Distribution

