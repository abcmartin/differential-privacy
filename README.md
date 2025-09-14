# Unterschiedliche Privatsphäre

> **NEU:**

> [Treten Sie unserer DP-Community in Slack bei](https://join.slack.com/t/dp-open-source/shared_invite/zt-35hw483tz-nS5YOtGjxCHk3Ek7WiXvlg)!

Dieses Repository enthält Bibliotheken, um ε- und (ε, δ)-differenzial zu generieren

Private (DP) Statistiken über Datensätze. Es enthält die folgenden Werkzeuge:

* [Privacy on Beam](privacy-on-beam) ist eine End-to-End-differenzierte Privatsphäre

Framework für Go, das auf

[Apache Beam](https://beam.apache.org/documentation/). Es soll sein

Einfach zu bedienen, auch von Nicht-Experten.

* [PipelineDP4j](pipelinedp4j) ist ein differenziertes End-to-End-Datenschutz-Framework

Für JVM-Sprachen (Java, Kotlin, Scala). Es unterstützt verschiedene Daten

Verarbeitungsrahmen wie

[Apache Beam](https://beam.apache.org/documentation/) und

[Apache Spark](https://spark.apache.org/). Es soll einfach zu bedienen sein,

Sogar von Nicht-Experten.

* Drei "DP-Baustein"-Bibliotheken in [C++(cc), [Go](go) und

[Java](java). Diese Bibliotheken implementieren grundlegende Rauschadditionsprimitive und

Differenziell private Aggregationen. Datenschutz bei der Nutzung von Beam und PipelineDP4j

Diese Bibliotheken.

* Ein [stochastische Tester](cc/testing), der verwendet wird, um Regressionen zu fangen, die

Machen Sie die differenzierte Datenschutz-Eigenschaft nicht mehr.

* Eine [differenzielle Datenschutz-Buchhaltungsbibliothek](python/dp_accounting), verwendet für

Verfolgung des Datenschutzbudgets.

* Eine [Befehlszeilenschnittstelle](examples/zetasql) für den unterschiedlichen Betrieb

Private SQL-Abfragen mit [ZetaSQL](https://github.com/google/zetasql).

* [DP Auditorium](python/dp_auditorium) ist eine Bibliothek für die Prüfung von Differentialen

Datenschutzgarantien.

Zusätzlich zu den oben aufgeführten Tools sind zwei verwandte

Projekte, die von [OpenMined](https://www.openmined.org/) entwickelt wurden, die

Unsere Bibliotheken:

* [PipelineDP](https://pipelinedp.io/) ist eine End-to-End-differenzierte Privatsphäre

Framework für Python. Es ist die Python-Version von PipelineDP4j und ist ein

Zusammenarbeit zwischen Google und OpenMined. Sein Quellcode befindet sich in

Das [OpenMined-Repository](https://github.com/OpenMined/PipelineDP).

* [PyDP](https://github.com/OpenMined/PyDP) ist ein Python-Wrapper unseres C++ DP

Bausteinbibliothek.

Die DP-Bausteinbibliotheken, Privacy on Beam, PipelineDP4j und PipelineDP

Eignen sich für Forschungs-, Versuchs- oder Produktionsfälle, während die

Andere Werkzeuge sind derzeit experimentell und können sich ändern.

## Erste Schritte

Wenn Sie neu in der differenzierten Privatsphäre sind, sollten Sie vielleicht

["Eine freundliche, nicht-technische Einführung in den differenzierten Datenschutz"](https://desfontain.es/privacy/friendly-intro-to-differential-privacy.html).

Es ist hilfreich, die Grundlagen zu verstehen, auch wenn Sie unsere übergeordneten Tools wie

Datenschutz auf Beam und PipelineDP4j. Wenn Sie planen, mehr Low-Level-Bibliotheken zu verwenden

Wie DP-Bausteinbibliotheken oder andere experimentelle Tools, benötigen Sie möglicherweise

Ein tieferes Verständnis der differenzierten Privatsphäre. Sie können einen Blick auf
