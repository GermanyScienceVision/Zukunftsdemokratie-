# Modul: Solidarische Versicherungen

**Leitformel:** *Alle tragen nach Leistungsfähigkeit. Alle erhalten nach Bedarf. Versorgung wird gesichert.*
**Teil der Gesamtkonzeption:** Zukunftsdemokratie
**Typ:** Fachmodul

Dieses Modul ist Teil des Konzepts Zukunftsdemokratie. Es behandelt die grundlegende Reform der Kranken-, Pflege- und Arbeitslosenversicherung als zusammenhängende Architektur und verzahnt sich mit den fünf Kapiteln, den anderen Modulen und den Anlagen. Die strukturellen Grundregeln finden sich in der `ARCHITEKTUR.md` im Repository-Root. Die finanzielle Detail-Architektur findet sich in der Anlage `anlagen/finanzierungslogik.md`.

---

## Hinweis zur Lesehilfe

Dieses Dokument enthält zwei Arten von eingerückten Hinweisboxen, die das Lesen erleichtern sollen.

**Juristische Einordnung**
Hier wird benannt, welche Verfassungs-, EU- oder Verwaltungsrechtsfragen sich an einer bestimmten Stelle stellen, welche Lösungswege existieren und wo juristische Grenzen liegen.

**Diskussionspunkt**
Hier werden Bedenken transparent benannt, die in der weiteren Diskussion zu klären sind. Sie sind nicht versteckt, sondern bewusst sichtbar gemacht, damit das Konzept ehrlich gegen seine eigenen Schwächen geprüft werden kann.

Der Hauptkonzepttext bleibt davon unberührt und kann separat gelesen werden. Die Hinweisboxen vertiefen, schmälern aber nicht die Argumentation.

---

## Inhaltsverzeichnis

- [Hinweis zur Lesehilfe](#hinweis-zur-lesehilfe)
- [Einordnung als Hochrisiko-Reform nach Architektur-Regel 1](#einordnung-als-hochrisiko-reform-nach-architektur-regel-1)
- [Teil A: Leitidee und gemeinsame Grundsätze](#teil-a-leitidee-und-gemeinsame-grundsaetze)
- [Teil B: Ausgangslage und Zwei-Szenarien-Argumentation](#teil-b-ausgangslage-und-zwei-szenarien-argumentation)
- [Teil C: Bürger-Gesundheits-Versicherung](#teil-c-buerger-gesundheits-versicherung)
- [Teil D: Arbeitslosenversicherung mit gleitender Brücke](#teil-d-arbeitslosenversicherung-mit-gleitender-bruecke)
- [Teil E: Gesamtbetrachtung und Zusammenwirken](#teil-e-gesamtbetrachtung-und-zusammenwirken)
- [Teil F: Risiken und ehrliche Begrenzungen](#teil-f-risiken-und-ehrliche-begrenzungen)
- [Verzahnung mit der Gesamtkonzeption](#verzahnung-mit-der-gesamtkonzeption)
- [Die Leitformel zum Schluss](#die-leitformel-zum-schluss)

---

<a id="einordnung-als-hochrisiko-reform-nach-architektur-regel-1"></a>
## Einordnung als Hochrisiko-Reform nach Architektur-Regel 1

Das Modul Solidarische Versicherungen ist nach Architektur-Regel 1 der `ARCHITEKTUR.md` als Hochrisiko-Reform eingestuft. Die Einstufung folgt aus der grundrechtlichen, demografischen und finanziellen Tragweite: Die Überführung der privaten Krankenvollversicherung, die Einbeziehung von Beamten und Selbstständigen, die Beitragspflicht auf alle Einkommensarten, die integrierte Pflegevollversicherung und die Behandlung der Altersrückstellungen greifen tief in etablierte Strukturen und in verfassungsrechtlich geschützte Positionen ein.

Die Einstufung bedeutet konkret: Diese Reformelemente unterliegen der Sechsstufen-Eskalations-Architektur aus Kapitel 4 — verbindliche Folgenabschätzung mit Generationenwirkung, parlamentarische Beratung mit den Folgenabschätzungs-Daten, suspensives Veto der zuständigen Fachkammer bei substantiellen Bedenken, Überstimmung durch qualifizierte Mehrheit, vier Mechanismen bei Abweichung (Berichtspflicht, Monitoring, Sunset-Klausel, Volksentscheid-Option) und Volksentscheid als letzte Instanz bei substantieller Persistenz des Konflikts.

Zusätzlich gelten die Pilotierungs-, Folgenabschätzungs-, Evaluations- und Sunset-Anforderungen aus Kapitel 4: Die Reform wird über klar definierte Phasen umgesetzt, mit Zwischenevaluationen durch den Wissenschafts- und Resilienzrat und mit Sunset-Klauseln, die zur regelmäßigen Neubewertung zwingen (siehe Teil C und E).

**Hauptzuständige Fachkammer:**

Die fachliche Aufsicht liegt bei der **Fachkammer Sozialstaat und Reziprozität** des Wissenschafts- und Resilienzrats (Architektur-Regel 1). Sie verantwortet die wissenschaftliche Begleitung, die Folgenabschätzungen und die methodische Aufsicht über die Versicherungsreform. Weitere zuständige Fachkammern sind die Fachkammer Öffentliche Grundversorgung, Infrastruktur und Tarife (für die Versorgungssicherheit als praktische Voraussetzung, Verzahnung mit Kapitel 2), die Fachkammer Generationenfragen (für die Generationenwirkung der Beitrags- und Leistungsstruktur) und die Fachkammer Digitale Souveränität (für die Datenarchitektur der erweiterten Bemessungsgrundlage und die getrennten Datenräume).

Der Gemeinsame Bundesausschuss bleibt als bestehende Institution für die operativen Leistungsbewertungen zuständig; seine Methodik wird am wissenschaftlichen Mindeststandard aus Kapitel 4 ausgerichtet und durch die Fachkammer Sozialstaat und Reziprozität geprüft (siehe Teil C, Leistungskatalog).


<a id="teil-a-leitidee-und-gemeinsame-grundsaetze"></a>
## Teil A: Leitidee und gemeinsame Grundsätze

### Die Leitidee

Die deutsche Sozialversicherung steht vor einer grundlegenden Strukturfrage. Sie wurde im späten 19. Jahrhundert aufgebaut, in einer Zeit klarer Erwerbsbiografien, einheitlicher Lebensläufe und einer demografischen Pyramide, die das System trug. Diese Voraussetzungen gelten nicht mehr. Erwerbsbiografien sind vielfältiger, Einkommensquellen verteilen sich auf mehrere Arten (Lohn, Kapital, Mieten, selbstständige Tätigkeit), die demografische Pyramide hat sich umgekehrt.

Gleichzeitig sind in mehreren Versicherungszweigen parallele Strukturen entstanden, die strukturelle Ungleichheiten erzeugen. In der Krankenversicherung existiert die gesetzliche neben der privaten Vollversicherung. In der Pflegeversicherung gilt dasselbe. In der Arbeitslosenversicherung sind Selbstständige weitgehend ausgeschlossen, Beamte sind nicht versichert. Diese Asymmetrien sind nicht historisch zwangsläufig, sondern Ergebnis politischer Pfadabhängigkeiten, die heute nicht mehr tragfähig sind.

Das Modul Solidarische Versicherungen ist die Antwort des Konzepts Zukunftsdemokratie auf diese Strukturfrage. Es behandelt die grundlegende Reform der Kranken-, Pflege- und Arbeitslosenversicherung als zusammenhängende Architektur, nicht als drei isolierte Reformen. Die zentrale Idee lautet: Solidarität funktioniert nur, wenn alle nach ihrer Leistungsfähigkeit beitragen und alle nach ihrem Bedarf Leistungen erhalten. Wo diese Logik durch parallele Strukturen unterlaufen wird, schwächt sie sich selbst.

### Drei gemeinsame Grundsätze

Alle Versicherungen in diesem Modul folgen drei gemeinsamen Grundsätzen:

**Erstens, Pflichteinbeziehung aller Erwerbstätigen.** Es gibt keine strukturelle Ausstiegsmöglichkeit aus der Solidargemeinschaft. Angestellte, Selbstständige, Beamte, Politiker, Künstler und Freiberufler sind alle einbezogen. Wahlfreiheit besteht nur bei Zusatzleistungen, nicht bei der Grundversicherung. Wer ein höheres Einkommen erzielt, kann sich nicht aus der Solidargemeinschaft herauskaufen. Dieser Grundsatz ist Teil des Reziprozitätspakets aus Kapitel 5 und dem Modul Reziproke Solidarität: Die Pflichtversicherung für alle Erwerbstätigen ist eines der sechs Elemente, mit denen Reziprozität auch nach oben wirkt.

**Zweitens, alle Einkommensarten als Bemessungsgrundlage.** Beiträge werden nicht nur auf Löhne und Gehälter erhoben, sondern auf das gesamte wirtschaftliche Einkommen einer Person. Kapitalerträge, Mieteinnahmen, Dividenden, Zinsen und selbstständige Einkommen sind beitragspflichtig. Diese Erweiterung der Bemessungsgrundlage ist die wichtigste strukturelle Veränderung gegenüber dem heutigen System. Sie verbreitert die Finanzierungsbasis substanziell und macht die Beitragslast unabhängig von der Art des Einkommens.

**Drittens, lineare Beitragsstruktur statt harter Beitragsbemessungsgrenze.** An die Stelle der heutigen Beitragsbemessungsgrenze (oberhalb derer keine Beiträge mehr fällig werden) tritt eine lineare Absenkung des Beitragssatzes ab einem definierten Schwellenwert bis zu einem festgelegten Endsockel. Damit zahlen auch sehr hohe Einkommen substanziell in die Solidargemeinschaft ein, ohne dass eine konfiskatorische Belastung entsteht.

### Was das Modul nicht ist

Das Modul ist keine Sammlung von Maximal-Forderungen. Es ist keine Lager-orientierte Programmatik. Es folgt der grundsätzlichen Linie der Zukunftsdemokratie: lösungsorientiert statt lager-orientiert. Die Positionen ergeben sich aus der Analyse der jeweiligen Problemstellung, nicht aus politischen Vorgaben.

Das Modul ist auch keine isolierte Reform. Es funktioniert nur in Verbindung mit anderen Bestandteilen der Gesamtkonzeption:

- **Kapitel 2 (Öffentliche Grundversorgung):** Die Versorgungssicherheit (kommunale Gesundheitszentren, öffentliche Krankenhäuser, ausreichendes Pflegepersonal) ist die strukturelle Voraussetzung. Ohne Versorgungssicherheit bleibt das Solidarversprechen formal, aber praktisch nicht eingelöst. Die Bürgerversicherung wird in Kapitel 2 operativ als Teil der Gesundheits-Grundversorgung behandelt.
- **Kapitel 4 (Agile wissenschaftsgetriebene Politik):** Die Mechanismen aus Kapitel 4 (Wissenschafts- und Resilienzrat mit der Fachkammer Sozialstaat und Reziprozität, Sechsstufen-Architektur, transparente Verfahren, messbare Wahlversprechen, Karenzzeiten) sind die politische Voraussetzung für die Durchsetzung der Reform gegen organisierte Interessen.
- **Kapitel 5 (Gesellschaftlicher Zusammenhalt):** Die generationelle Perspektive (Schuldenbremse-Sondermodell, Generationenrücklage, Rentenreform) bettet das Modul in die Generationengerechtigkeits-Architektur ein. Kapitel 5 nennt die Bürgerversicherung ausdrücklich als Teil der Generationengerechtigkeits-Reform (Säule 3).
- **Modul Reziproke Solidarität:** Die Mitwirkungs- und Schutzmechanismen aus diesem Querschnittsmodul greifen an mehreren Stellen (Familienmitversicherung, Übergang von Arbeitslosenversicherung in Bürgergeld). Die Pflichtversicherung für alle Erwerbstätigen ist in beiden Modulen als Element des Reziprozitätspakets verankert.

Wer Bestandteile dieses Moduls übernehmen will, muss die Verzahnung mit den anderen Kapiteln und Modulen prüfen. Eine selektive Übernahme ohne diese Prüfung kann das Konzept verfehlen.

> **Diskussionspunkt**
> Die strukturelle Reform der drei großen Sozialversicherungen ist seit Jahrzehnten in der politischen Debatte. Sie ist mehrfach in Koalitionsverhandlungen aufgegeben worden. Die Vermutung des Konzepts ist, dass dies nicht primär an inhaltlichen Mängeln der Reform-Konzepte liegt, sondern an einer politischen Architektur, die organisierten Interessen mehr Einfluss gibt als wissenschaftlicher Evidenz und Generationengerechtigkeit. Dieses Modul wird deshalb nicht isoliert vorgeschlagen, sondern in Verzahnung mit Kapitel 4, das die politische Architektur reformiert.


<a id="teil-b-ausgangslage-und-zwei-szenarien-argumentation"></a>
## Teil B: Ausgangslage und Zwei-Szenarien-Argumentation

### Ausgangslage

Die Bestandsaufnahme erfolgt nüchtern, ohne politische Dramatisierung.

**Demografische Entwicklung.** Die Erwerbsbevölkerung in Deutschland sinkt von etwa 51 Millionen heute auf etwa 43-44 Millionen bis 2035 und etwa 37-38 Millionen bis 2050. Diese Entwicklung beruht auf bereits gelebten Geburtsjahrgängen und kann durch Politik kurzfristig nicht verändert werden. Gleichzeitig steigt die Zahl der Rentner und Pflegebedürftigen substanziell. Das Verhältnis zwischen Beitragszahlern und Leistungsempfängern verschiebt sich deutlich.

**Beitragssatz-Entwicklung.** Der Gesamtbeitragssatz der gesetzlichen Krankenversicherung liegt heute bei etwa 14 Prozent (zuzüglich Pflegeversicherung). Ohne strukturelle Reform wird er nach Prognosen mehrerer Forschungsinstitute bis 2040 auf 18-22 Prozent steigen. Diese Entwicklung trifft die heute jüngeren Erwerbstätigen, die das System finanzieren.

**Eigenanteile in der Pflege.** Pflegebedürftige zahlen heute Eigenanteile von oft 2.000-3.000 Euro monatlich für die Heimunterbringung. Diese Eigenanteile sind in den vergangenen Jahren stark gestiegen und werden ohne Reform weiter steigen. Sie führen dazu, dass viele Familien finanziell ruiniert werden oder dass die Pflege zu einem Sozialhilfe-Fall wird.

**Parallele Strukturen.** Die gesetzliche und die private Krankenversicherung existieren nebeneinander. Etwa 9 Millionen Menschen sind in der privaten Vollversicherung, etwa 73 Millionen in der gesetzlichen. Diese Trennung erzeugt strukturelle Ungleichheiten: unterschiedliche Leistungen, unterschiedliche Wartezeiten bei Fachärzten, unterschiedliche Beitragslogiken. Die private Vollversicherung entzieht der Solidargemeinschaft die wirtschaftlich Leistungsfähigsten und konzentriert die Belastung auf die gesetzlich Versicherten.

**Strukturelle Ungerechtigkeit bei der Beitragsbemessung.** Ein Angestellter mit 50.000 Euro Jahreseinkommen zahlt Beiträge auf sein gesamtes Einkommen. Ein Bezieher von Kapitalerträgen oder Mieteinnahmen in gleicher Höhe zahlt keinen Sozialversicherungsbeitrag. Ein Angestellter mit 200.000 Euro Jahreseinkommen zahlt nur Beiträge bis zur Beitragsbemessungsgrenze (etwa 66.000 Euro), darüber nichts mehr. Diese Ungleichheit ist strukturell, nicht akzidentell.

**Generationenungleichheit.** Die heute jüngeren Erwerbstätigen finanzieren ein System, das ihnen voraussichtlich nicht in gleichem Umfang zugutekommen wird. Sie zahlen höhere Beiträge bei voraussichtlich niedrigeren Leistungen. Diese Generationenungleichheit ist im Konzept Zukunftsdemokratie eine zentrale Reform-Begründung und wird durch die Generationenbilanz aus Kapitel 5 (konsolidierte neun Bewertungsdimensionen) erfasst.

### Die zwei Wege

Vor diesem Hintergrund stehen Deutschland zwei strukturell unterschiedliche Wege offen.

**Szenario 1: Faktenbasierte Reform.**

Wenn die strukturelle Reform durchgeführt wird – Pflichteinbeziehung aller Erwerbstätigen, lineare Beitragsstruktur, alle Einkommensarten als Bemessungsgrundlage, integrierte Bürger-Gesundheits-Versicherung – bleibt der Beitragssatz für die breite Mitte stabil oder sinkt sogar. Die Pflegevollversicherung wird finanzierbar. Die Generationenlast wird gerechter verteilt. Die Versorgungssicherheit kann durch die Maßnahmen aus Kapitel 2 substanziell verbessert werden. Die strukturellen Ungleichheiten zwischen verschiedenen Berufsgruppen und Einkommensarten werden beseitigt.

Diese Reform erfolgt geordnet, mit langen Übergangsfristen, mit Bestandsschutz für bereits abgeschlossene Verträge, mit kompensierenden Mechanismen für die Versicherungswirtschaft. Sie ist verfassungsrechtlich tragfähig und politisch durchsetzbar, wenn die Mechanismen aus Kapitel 4 (wissenschaftlicher Mindeststandard, messbare Wahlversprechen, Karenzzeiten, transparente Verfahren, Sechsstufen-Architektur) wirken.

**Szenario 2: Ungeordneter Kollaps der gesetzlichen Krankenversicherung.**

Ohne strukturelle Reform steigen die Beitragssätze in den 2030er und 2040er Jahren auf ein Niveau, das die gesetzlich Versicherten überlastet. Gleichzeitig sinken die Leistungen, weil Eigenanteile steigen müssen, um das System überhaupt zu finanzieren. Die Pflege wird zunehmend zu einem Sozialhilfe-Fall. Pflegebedürftige müssen ihr Vermögen aufbrauchen, ihre Familien werden mitbelastet. Der Generationenkonflikt verschärft sich. Die politische Akzeptanz der Sozialversicherung erodiert.

Irgendwann erfolgt die strukturelle Reform auch in diesem Szenario – aber in einer Krise. Krisen-Reformen sind selten gut. Sie erfolgen unter Zeitdruck, mit weniger Sorgfalt, mit größeren Härten für die Betroffenen. Sie werden oft als politische Niederlage wahrgenommen und untergraben das Vertrauen weiter.

### Die Position des Konzepts

Das Konzept entscheidet sich für Szenario 1. Diese Entscheidung ist nicht ideologisch, sondern strukturell begründet: Eine geordnete Reform schützt die Solidargemeinschaft besser als ein ungeordneter Kollaps. Sie wahrt die Versorgungssicherheit, sie verteilt die Belastungen fair, sie sichert die Generationengerechtigkeit.

Die Reform ist anspruchsvoll. Sie greift in etablierte Strukturen ein. Sie wird politischen Widerstand erzeugen. Aber die Alternative – das Festhalten an einem System, das demografisch und strukturell nicht mehr trägt – ist die schlechtere Wahl. Wer humanitäre Verantwortung ernst nimmt, wer Solidarität nicht nur als Rhetorik verstehen will, wer die kommenden Generationen nicht überlasten will, muss die Reform wollen.

> **Diskussionspunkt**
> Die Zwei-Szenarien-Argumentation ist eine bewusste rhetorische und sachliche Wahl. Sie soll deutlich machen, dass es nicht um "Reform oder Stillstand" geht, sondern um "geordnete Reform oder ungeordneten Kollaps". Diese Sichtweise wird unterschiedlich gelesen. Kritiker können argumentieren, dass Szenario 2 dramatisiert ist und das heutige System anpassungsfähiger ist als hier dargestellt. Befürworter werden argumentieren, dass die demografischen und finanziellen Trends bereits absehbar sind und Verzögerung nur die Härte der späteren Anpassung verschärft. Beide Lesarten sind legitim. Das Konzept entscheidet sich bewusst für die strukturelle Reform.


<a id="teil-c-buerger-gesundheits-versicherung"></a>
## Teil C: Bürger-Gesundheits-Versicherung

### Die Position des Konzepts

Das Konzept entscheidet sich für eine **vollständige Bürger-Gesundheits-Versicherung**, die Krankenversicherung und Pflegeversicherung integriert. Sie umfasst alle in Deutschland lebenden Menschen, finanziert sich durch Beiträge aller Erwerbstätigen auf alle Einkommensarten, und folgt einer linearen Beitragsstruktur statt der heutigen harten Beitragsbemessungsgrenze.

Die Bürger-Gesundheits-Versicherung ist die Versicherungs-Architektur der Bürgerversicherung, die Kapitel 5 (Säule 3) als Teil der Generationengerechtigkeits-Reform und Kapitel 2 (Gesundheit als öffentliche Grundversorgung) operativ vorsehen. Dieses Modul liefert die strukturelle Ausgestaltung; die Versorgungsseite liegt in Kapitel 2, die generationelle Einbettung in Kapitel 5.

Die wichtigsten strukturellen Merkmale:

- **Pflichteinbeziehung aller Erwerbstätigen**: Angestellte, Selbstständige, Beamte, Politiker, Künstler, Freiberufler. Keine strukturelle Ausstiegsmöglichkeit aus der Solidargemeinschaft.
- **Integration von Kranken- und Pflegeversicherung**: Eine einheitliche Versicherung deckt die gesamte Lebensspanne ab – Vorsorge, Akutmedizin, Rehabilitation, Pflege. Die heutige institutionelle Trennung wird beendet.
- **Vollversicherungs-Logik für Pflege**: Keine substanziellen Eigenanteile mehr. Pflegebedürftigkeit ruiniert keine Familien mehr finanziell.
- **Lineare Beitragsstruktur**: Beiträge werden auf alle Einkommensarten erhoben. Bis zu einem ersten Schwellenwert gilt der volle Beitragssatz, dann sinkt der Satz linear bis zu einem zweiten Schwellenwert, ab dem ein fester niedriger Endsockel greift.
- **Vollständige Pflichtüberführung nach Übergangsfrist**: Die private Krankenvollversicherung wird nach Ablauf der Übergangsfrist als Geschäftsmodell beendet. Private Zusatzversicherungen bleiben möglich.
- **Wahlrecht über die Verwendung der Altersrückstellungen**: Bestandsversicherte entscheiden, ob ihre Altersrückstellungen als Gutschrift in die Bürger-Gesundheits-Versicherung übertragen oder ausgezahlt werden.

> **Juristische Einordnung**
> Die vollständige Pflichtüberführung greift in mehrere verfassungsrechtlich geschützte Positionen ein: Vertrauensschutz der Bestandsversicherten, Eigentumsgarantie für Altersrückstellungen (Art. 14 GG), Berufsfreiheit privater Versicherer (Art. 12 GG). Diese Eingriffe sind verfassungsrechtlich rechtfertigungsbedürftig, aber nicht ausgeschlossen. Die Rechtfertigung erfolgt über das Solidaritätsprinzip aus Art. 20 GG und über die zwingenden Gründe des Allgemeinwohls (Generationengerechtigkeit, Stabilität der Solidargemeinschaft, demografische Tragfähigkeit), die das Bundesverfassungsgericht in seiner Klimabeschluss-Rechtsprechung von 2021 als verfassungsrechtlich relevant anerkannt hat. Die Verfassungsmäßigkeit wird durch lange Übergangsfristen, Bestandsschutz und Kompensationsmechanismen gesichert. Die Detailausarbeitung erfolgt in der Anlage `anlagen/juristische-fragen.md`.

### Übergangsmechanismen: Das Phasenmodell

Die Reform wird über einen Zeitraum von 10-15 Jahren in drei klar definierten Phasen umgesetzt. Diese Phasenstruktur sichert die geordnete Umsetzung, gibt allen Beteiligten Planungssicherheit und reduziert die Disruption am Ende der Übergangsfrist. Die Phasen sind in Teil E mit der gemeinsamen Phasenarchitektur nach Architektur-Regel 3 abgeglichen.

**Phase 1: Vorbereitung (erste drei Jahre der Modul-Umsetzung)**

In der ersten Phase wird der gesetzliche Rahmen beschlossen und in Kraft gesetzt. Ab dem Stichtag werden keine neuen Verträge in der privaten Krankenvollversicherung mehr abgeschlossen. Alle Neuversicherten – Berufseinsteiger, Personen mit Statusänderung, Zuzügler – kommen in die Bürger-Gesundheits-Versicherung. Bestandsversicherte bleiben zunächst in ihren bestehenden Verträgen.

Parallel werden die erweiterten Bürgerversicherungs-Strukturen aufgebaut: das neue Beitragssystem mit linearer Logik, die Erfassung aller Einkommensarten, die integrierte Verwaltung von Kranken- und Pflegeversicherung. Erste Pilot-Übernahmen von Strukturen und Mitarbeitern aus der privaten Krankenversicherung beginnen. Die Versorgungssicherheit aus Kapitel 2 wird parallel vorbereitet (kommunale Gesundheitszentren, öffentliche Krankenhäuser, ausreichendes Pflegepersonal).

Der Wissenschafts- und Resilienzrat aus Kapitel 4 begleitet die Reform mit verbindlichen Folgenabschätzungen und wissenschaftlichen Empfehlungen über die zuständige Fachkammer Sozialstaat und Reziprozität.

**Phase 2: Übergang (mittlere Phase)**

In der zweiten Phase können Bestandsversicherte freiwillig in die Bürger-Gesundheits-Versicherung wechseln. Anreize fördern den freiwilligen Wechsel: attraktive Übertragung der Altersrückstellungen, vereinfachte Aufnahme, klare Beitragstransparenz. Mit jedem freiwilligen Wechsel und mit jeder natürlichen Reduktion der Bestandsversicherten schrumpft die private Krankenvollversicherung.

Parallel stellen die Versicherungsunternehmen ihre Geschäftsmodelle um. Sie haben mehrere Wege zur Auswahl: Übergang zu Zusatzversicherungen, Integration in Bürgerversicherungs-Träger, Übernahme durch bestehende gesetzliche Krankenkassen, oder geordnete Abwicklung. Diese Wahlfreiheit wahrt die Berufsfreiheit der Unternehmen.

Die Übernahme von Mitarbeitern in die neue Struktur erfolgt substanziell. Versicherungsmathematiker, Sachbearbeiter, IT-Fachkräfte und Verwaltung werden mit ihren Rechten nach Betriebsübergangs-Recht (§ 613a BGB) übernommen. Damit wird verhindert, dass bestehende Strukturen ungenutzt abgewickelt werden, während gleichzeitig die Bürgerversicherung neue Strukturen aufbauen muss.

Die integrierte Pflegevollversicherung wird in dieser Phase ausgebaut. Pflegegrade, Versorgungsformen und Anerkennung pflegender Angehöriger werden konsistent mit Kapitel 2 und dem Modul Reziproke Solidarität gestaltet.

Eine erste Zwischenevaluation nach fünf Jahren prüft die Wirkungen der Reform und identifiziert gegebenenfalls Korrekturbedarf. Diese Evaluation erfolgt durch den Wissenschafts- und Resilienzrat aus Kapitel 4, gemäß der Säule Agilität.

**Phase 3: Konsolidierung (Schlussphase)**

In der dritten Phase werden alle verbleibenden Bestandsversicherten in die Bürger-Gesundheits-Versicherung überführt. Die Behandlung der Altersrückstellungen erfolgt gemäß dem Wahlrecht der Versicherten (siehe unten). Die private Krankenvollversicherung wird formal beendet. Verbleibende Versicherungsunternehmen sind vollständig auf Zusatzversicherungen umgestellt oder in andere Strukturen integriert.

Eine abschließende Evaluation prüft die Gesamtwirkung der Reform und identifiziert verbleibende Korrekturbedarfe. Sunset-Klauseln aus Kapitel 4 zwingen zur regelmäßigen Neubewertung der Versicherungsstruktur.

> **Diskussionspunkt**
> Die zeitliche Streckung der Reform über 10-15 Jahre ist eine bewusste Wahl, die zwei Anforderungen ausbalanciert. Einerseits muss die Reform substanziell schneller wirken als eine reine Generations-Übergangslogik (25-30 Jahre), weil die strukturelle Ungerechtigkeit zwischen Pflichtversicherten und Privatversicherten nicht eine weitere Generation lang fortbestehen darf. Andererseits muss die Übergangszeit lang genug sein, um Versicherungsunternehmen, Mitarbeiter und Verwaltung eine geordnete Anpassung zu ermöglichen. Die 10-15-Jahre-Frist ist der ausbalancierte Kompromiss. Die genaue Länge kann je nach politischer Lage angepasst werden.

### Behandlung der Altersrückstellungen

Die privaten Krankenversicherer haben für ihre Vollversicherten Altersrückstellungen in Höhe von schätzungsweise 270-300 Milliarden Euro aufgebaut. Diese Rückstellungen wurden aus den Beiträgen der Versicherten gebildet, um die im Alter steigenden Gesundheitskosten zu finanzieren. Sie sind individuell zugeordnet und durch die Eigentumsgarantie aus Art. 14 GG geschützt.

Bei der Überführung in die Bürger-Gesundheits-Versicherung haben die Versicherten ein **Wahlrecht** über die Verwendung ihrer Altersrückstellungen:

**Wahlmöglichkeit A: Übertragung als individuelle Gutschrift**

Die Altersrückstellungen werden in die Bürger-Gesundheits-Versicherung übertragen und dort als individuelle Gutschrift dem jeweiligen Versicherten zugeordnet. Sie reduzieren über die Restlebenszeit die Beiträge des Versicherten zur Bürger-Gesundheits-Versicherung. Damit wird das Eigentum gewahrt, und die Versicherten haben keinen Einkommensverlust gegenüber heute.

**Wahlmöglichkeit B: Auszahlung zur freien Verwendung**

Die Altersrückstellungen werden den Versicherten direkt ausgezahlt. Sie können das Geld frei verwenden – für private Zusatzversicherungen, Vermögensaufbau, Vorsorge in anderer Form. Die Auszahlung erfolgt nicht auf einen Schlag, sondern verteilt über die Übergangsfrist, um die Liquidität der Versicherungsunternehmen nicht zu überlasten.

**Steuerrechtliche Behandlung der Auszahlung:** Die eingezahlten Beiträge wurden aus bereits versteuertem Einkommen geleistet und werden bei Auszahlung nicht erneut besteuert. Die in den Rückstellungen erwirtschafteten Erträge (Zinsen, Anlageerträge) wurden während der Laufzeit steuerfrei akkumuliert; sie werden bei Auszahlung als Kapitalertrag versteuert. Diese Differenzierung wahrt das Verbot der Doppelbesteuerung und erfasst gleichzeitig die noch nicht versteuerten Komponenten.

> **Juristische Einordnung**
> Das Wahlrecht über die Verwendung der Altersrückstellungen ist der zentrale verfassungsrechtliche Schutzmechanismus. Es wahrt die Eigentumsgarantie aus Art. 14 GG, weil das Eigentum nicht enteignet, sondern in eine andere Form überführt wird. Die individuelle Wahlfreiheit über die Verwendung des eigenen Geldes ist juristisch tragfähig. Die Liquiditäts-gestreckte Auszahlung schützt die Versicherungsunternehmen vor einer einmaligen Auszahlungswelle, die ihre wirtschaftliche Existenz gefährden könnte. Die steuerliche Differenzierung zwischen Beiträgen (bereits versteuert) und Erträgen (steuerfrei akkumuliert) wahrt das Verbot der Doppelbesteuerung.

### Einbeziehung der Beamten

Die Beamten in Deutschland (etwa 5 Millionen Beamte und Beihilfe-Berechtigte) sind heute durch das Beihilfe-System abgesichert: der Dienstherr (Bund, Land, Kommune) übernimmt 50-70 Prozent der Gesundheitskosten als Beihilfe, die restlichen 30-50 Prozent decken die Beamten über eine private Krankenversicherung ab. Diese Konstruktion ist im Beamtenrecht verankert und Teil der Alimentation des Dienstherrn aus Art. 33 Abs. 5 GG.

Im neuen System werden Beamte vollständig in die Bürger-Gesundheits-Versicherung einbezogen. Aber die Beitragsaufteilung folgt nicht der Standard-Logik (50/50 zwischen Arbeitnehmer und Arbeitgeber), sondern der bisherigen Beihilfe-Logik:

- Der Dienstherr übernimmt 50-70 Prozent des Beitrags, je nach individuellem Beihilfesatz aus dem Beamtenvertrag.
- Der Beamte selbst trägt 30-50 Prozent des Beitrags.

Diese Aufteilung folgt den heute individuell festgelegten Beihilfesätzen, die je nach Familienstand, Dienstort und Statusgruppe variieren. Beispielsweise: Beamte ohne Kinder typisch 50/50, Beamte mit zwei Kindern typisch 70/30, Pensionäre typisch 70/30.

Die strukturelle Asymmetrie zwischen Beamten und Nicht-Beamten in der Krankenversicherung wird damit beseitigt. Beamte sind in der gleichen Solidargemeinschaft wie alle anderen, mit den gleichen Leistungen und der gleichen Versorgungsstruktur. Was erhalten bleibt, ist die Aufteilungslogik des Beihilfe-Systems – nicht als Privileg, sondern als Erfüllung der Alimentation-Pflicht des Dienstherrn aus Art. 33 Abs. 5 GG. Die Einbeziehung folgt der Übergangslogik aus Kapitel 1 und dem Modul Reziproke Solidarität: neue Beamtenverhältnisse werden ab Stichtag erfasst, bestehende Ansprüche geschützt, Sondersysteme laufen über lange Fristen aus.

Die lineare Beitragsstruktur gilt auch für Beamte. Bei Beamten mit höheren Einkommen greift die lineare Absenkung wie bei allen anderen Versicherten.

> **Juristische Einordnung**
> Die Übertragung der Beihilfe-Logik auf die Bürger-Gesundheits-Versicherung schafft innerhalb der Bürgerversicherung eine asymmetrische Beitragsaufteilung: Beamte zahlen 30-50 Prozent des Beitrags selbst, Angestellte 50 Prozent. Diese Asymmetrie könnte als Verstoß gegen Art. 3 GG (Gleichheitsgrundsatz) gelesen werden. Sie ist aber gerechtfertigt durch das Alimentation-Prinzip aus Art. 33 Abs. 5 GG, das den Dienstherrn zur besonderen Fürsorge für seine Beamten verpflichtet. Der höhere Arbeitgeberanteil erfüllt diese verfassungsrechtliche Fürsorgepflicht. Die Konstruktion ist juristisch tragfähig, muss aber im Gesetz klar begründet werden.

### Einbeziehung der Selbstständigen

Selbstständige sind im neuen System pflichtversichert und tragen den vollen Beitrag (Arbeitgeber- und Arbeitnehmeranteil gemeinsam). Die lineare Beitragsstruktur gilt für sie wie für alle anderen.

Diese Lösung folgt dem Solidargedanken: Wer wirtschaftlich leistungsfähig ist, trägt zur Solidargemeinschaft bei, unabhängig von der Art der Beschäftigung. Die heutige Lage – freiwillige Versicherung in der GKV oder private Krankenversicherung – wird durch die Pflichteinbeziehung abgelöst. Selbstständige sind bei Krankheit, Pflegebedürftigkeit und im Alter nicht mehr in einer strukturell schlechteren Position als Angestellte.

Die wirtschaftliche Realität der Selbstständigkeit wird durch die lineare Beitragsstruktur und durch die Bemessung auf das tatsächliche Einkommen abgefedert. Junge Selbstständige mit niedrigem Einkommen zahlen entsprechend niedrige Beiträge in absoluter Höhe. Etablierte Selbstständige mit hohen Einkommen tragen substanziell bei. Selbstständige mit sehr hohen Einkommen fallen in die lineare Absenkung und den Endsockel.

> **Diskussionspunkt**
> Die Pflichteinbeziehung der Selbstständigen wird kontrovers diskutiert. Befürworter argumentieren mit dem Solidargedanken und der strukturellen Gleichbehandlung aller Erwerbstätigen. Kritiker argumentieren, dass Selbstständige aus dem gleichen Einkommen auch Altersvorsorge, Arbeitslosigkeitsrücklage, Krankheit und Urlaub finanzieren müssen, was eine zusätzliche Belastung darstellt. Das Konzept folgt der Solidar-Argumentation und federt die Belastung durch die lineare Beitragsstruktur ab. Die genaue Kalibrierung der Beitragsstruktur muss volkswirtschaftlich modelliert werden, um sicherzustellen, dass die Gründungsphase neuer Selbstständigkeit nicht erstickt wird.

### Behandlung der privaten Krankenversicherungs-Unternehmen

Die heutigen privaten Krankenversicherungs-Unternehmen verlieren nach der Übergangsfrist ihr Kerngeschäftsmodell – die private Vollversicherung. Aber sie werden nicht abgewickelt. Das Konzept folgt einer differenzierten Lösung, die sowohl die wirtschaftliche Substanz als auch die Strukturen und Mitarbeiter sichert.

Die Unternehmen haben Wahlfreiheit zwischen vier Wegen:

**Weg 1: Umstellung auf Zusatzversicherungen.** Die Unternehmen verlagern ihr Geschäftsmodell auf das Zusatzversicherungs-Geschäft: Einbettzimmer, Chefarztbehandlung, Zahnersatz über den Standard hinaus, alternative Heilmethoden (außerhalb des evidenzbasierten Leistungskatalogs der Bürger-Gesundheits-Versicherung), Auslandsversicherung. Dieser Markt bleibt substanziell und wirtschaftlich tragfähig.

**Weg 2: Integration in Bürgerversicherungs-Träger.** Die Unternehmen werden zu Trägern der Bürger-Gesundheits-Versicherung umgewandelt (ähnlich wie heute die verschiedenen gesetzlichen Krankenkassen). Sie folgen dem einheitlichen Leistungs- und Beitragsrecht der Bürger-Gesundheits-Versicherung, behalten aber ihre organisatorische Identität. Der Wettbewerb verlagert sich von der Risikoauslese zur Service- und Effizienzqualität.

**Weg 3: Übernahme durch bestehende gesetzliche Krankenkassen.** Die Unternehmen werden von bestehenden gesetzlichen Trägern übernommen. Mitarbeiter, Systeme und Strukturen werden integriert.

**Weg 4: Geordnete Abwicklung.** Unternehmen, die keinen der drei anderen Wege wählen, werden geordnet abgewickelt. Mitarbeiter haben Anspruch auf Übernahme in andere Bereiche der neuen Struktur.

Wesentlich für die Reform ist die aktive Übernahme von Strukturen und Mitarbeitern. Es wäre volkswirtschaftlich verschwenderisch, etablierte IT-Systeme, Abrechnungsstrukturen, Vertragsmanagement und Risikomodellierung abzuwickeln, während die Bürger-Gesundheits-Versicherung parallel neue Strukturen aufbauen müsste. Versicherungsmathematiker, Sachbearbeiter, IT-Fachkräfte und Verwaltung sind hochqualifizierte Kräfte, deren Expertise die Reform aktiv mitgestalten kann.

Die arbeitsrechtliche Absicherung erfolgt über das Betriebsübergangs-Recht (§ 613a BGB). Mitarbeiter behalten ihre Rechte und Ansprüche beim Übergang. Das ist juristisch erprobt und politisch akzeptiert.

> **Juristische Einordnung**
> Die zwangsweise Beendigung des PKV-Vollversicherungs-Geschäftsmodells nach Ablauf der Übergangsfrist greift in die Berufsfreiheit der Versicherungsunternehmen aus Art. 12 GG ein. Die Wahlfreiheit zwischen den vier Wegen (Umstellung, Integration, Übernahme, Abwicklung) wahrt jedoch substanziell die Berufsfreiheit. Die Unternehmen können selbst entscheiden, wie sie auf die strukturelle Veränderung reagieren. Die lange Übergangsfrist von 10-15 Jahren gibt ausreichend Anpassungszeit. Diese Konstruktion ist verfassungsrechtlich tragfähig.

### Familienmitversicherung mit Erziehungs- und Pflegeleistungsanerkennung

Die Familienmitversicherung wird im neuen System reformiert, um sowohl die Erwerbsorientierung als auch die gesellschaftliche Anerkennung von Erziehungs- und Pflegeleistung zu wahren.

**Grundregel:**

- Kinder bis 25 Jahre sind beitragsfrei mitversichert (Ausbildungs- und Studienphase).
- Ehepartner ohne eigenes Einkommen sind beitragsfrei mitversichert, solange sie anerkannte Erziehungs- oder Pflegeleistung erbringen.

**Definition der anerkannten Leistung:**

- Erziehung: Kinder unter 14 Jahren im Haushalt; alternativ Erziehungsphase nach Geburt eines Kindes für mindestens 1-3 Jahre (analog der Elterngeld-Logik); bei mehreren Kindern Verlängerung der Anerkennung.
- Pflege: Pflege von Angehörigen mit anerkanntem Pflegegrad (mindestens Pflegegrad 2); Mindestumfang an wöchentlicher Pflegezeit (analog der bestehenden Pflegezeit-Anerkennung in der Rente).

Diese Definitionen knüpfen an bestehende sozialgesetzliche Strukturen an (Elternzeit, Pflegezeit). Die Bürger-Gesundheits-Versicherung übernimmt diese etablierten Definitionen, um Verwaltungsaufwand und Rechtsunsicherheit zu vermeiden.

**Bei Wegfall der anerkannten Leistung:**

Wenn die Erziehungs- oder Pflegeleistung wegfällt – beispielsweise das jüngste Kind wird 14 Jahre alt, oder der pflegebedürftige Angehörige verstirbt – endet die beitragsfreie Mitversicherung. Es entsteht kein dauerhafter beitragsfreier Versorgungsstatus. Die Person tritt in die Logik der Reziproken Solidarität ein: entweder durch Aufnahme einer Erwerbstätigkeit oder durch Erbringung sozialer Stunden gemäß Modul Reziproke Solidarität.

Diese Konstruktion ist konsistent mit der gesamten Konzept-Architektur: Niemand wird dauerhaft passiv gehalten. Die Solidargemeinschaft trägt diejenigen, die nicht erwerbstätig sein können und einen anerkannten gesellschaftlichen Beitrag leisten (Erziehung, Pflege). Sie trägt auch diejenigen ohne anerkannten Beitrag im Rahmen der sozialen Mindestteilhabe – die Mitwirkungserwartung greift bei festgestellter Mitwirkungsfähigkeit, mit allen Schutzmechanismen.

Die Schutzmechanismen aus dem Modul Reziproke Solidarität greifen vom ersten Tag: Verhältnismäßigkeit, gerichtliche Überprüfung, Aufsicht durch die Fachkammer Sozialstaat und Reziprozität mit Schwerpunkt Ethik, Schutz des Existenzminimums aus Art. 1 GG, soziale Mindestteilhabe.

> **Diskussionspunkt**
> Die Familienmitversicherung mit Erziehungs- und Pflegeleistungsanerkennung ist die mittlere Lösung zwischen zwei Extremen: einer vollständigen Familienmitversicherung wie heute (die als Fehlanreiz gegen Frauenerwerbstätigkeit kritisiert wird) und einer individuellen Beitragspflicht ohne familiäre Berücksichtigung (die Care-Arbeit nicht anerkennt). Die mittlere Lösung ist geschlechterneutral formuliert – sie knüpft an konkrete Leistungen an, nicht an Geschlecht oder familiären Status. Die Definition der anerkannten Leistung kann politisch umstritten sein und muss klar im Gesetz festgelegt werden.

### Leistungskatalog: Evidenzbasierte Logik

Der Leistungskatalog der Bürger-Gesundheits-Versicherung folgt einer evidenzbasierten Logik mit drei Elementen:

**Erstens, Abschaffung nicht-evidenzbasierter Leistungen.**

Leistungen ohne wissenschaftliche Evidenz für ihre Wirksamkeit werden nicht mehr aus Solidarmitteln finanziert. Dies betrifft beispielsweise viele homöopathische Behandlungen, anthroposophische Medizin, bestimmte alternative Heilverfahren und Wahlleistungen ohne nachgewiesenen Nutzen. Die genaue Liste wird durch den Gemeinsamen Bundesausschuss in transparenten Verfahren festgelegt.

Wichtig: Die Abschaffung betrifft nicht die Behandlungsfreiheit. Wer eine nicht-evidenzbasierte Behandlung wünscht, kann sie weiterhin in Anspruch nehmen – auf eigene Kosten oder über private Zusatzversicherung. Was sich ändert, ist ausschließlich die Solidarfinanzierung: Beiträge aller Versicherten werden nur für nachweislich wirksame Behandlungen verwendet.

**Zweitens, leicht erweiterter evidenzbasierter Leistungskatalog.**

Wo wissenschaftliche Evidenz vorhanden ist, wird der Leistungskatalog gegenüber der heutigen GKV moderat ausgebaut. Beispiele: besserer Zahnersatz im Rahmen evidenzbasierter Versorgung, Brillenkosten in angemessenem Umfang, breitere Vorsorgeleistungen mit nachgewiesenem Nutzen, kürzere Erstattungsverfahren.

**Drittens, substanziell erhöhte Versorgungssicherheit.**

Die formale Aufnahme einer Leistung in den Katalog nützt nichts, wenn die Versorgung praktisch nicht verfügbar ist – wenn Wartezeiten von Monaten herrschen, wenn Fachärzte fehlen, wenn Pflegeheime unterbesetzt sind. Die Bürger-Gesundheits-Versicherung wird deshalb nicht nur durch ihren Leistungskatalog definiert, sondern durch die tatsächliche Versorgungssicherheit.

Die Versorgungssicherheit ist in Kapitel 2 (Öffentliche Grundversorgung) systematisch ausgearbeitet: kommunale Gesundheitszentren als wohnortnahe Anlaufstellen, öffentliche Krankenhäuser als zentrale Versorgungsstruktur, ausreichende Pflegeeinrichtungen und ausreichendes Pflegepersonal. Diese strukturelle Reform aus Kapitel 2 ist die praktische Voraussetzung des Solidarversprechens der Bürger-Gesundheits-Versicherung. Sie wird im Gleichwertigkeitsraster aus Kapitel 5 (Dimensionen Erreichbarkeit Gesundheit und Pflege) regional messbar gemacht.

**Wer entscheidet über die Aufnahme oder den Ausschluss von Leistungen?**

Die Entscheidung erfolgt über transparente Verfahren mit öffentlichen Konsultationen:

- Der **Gemeinsame Bundesausschuss (G-BA)** als bestehende Institution wird gestärkt und führt die operativen Bewertungen durch. Die Methodik wird klarer am wissenschaftlichen Mindeststandard aus Kapitel 4 ausgerichtet.
- Die **Fachkammer Sozialstaat und Reziprozität** des Wissenschafts- und Resilienzrats prüft die Methodik des G-BA und stellt die wissenschaftlichen Mindeststandards sicher.
- **Transparente Verfahren mit öffentlichen Konsultationen** sind das Kernverfahren: bei jeder Bewertung einer Leistung wird offen kommuniziert, was bewertet wird, welche Evidenz vorliegt, welche Argumente für und gegen die Aufnahme oder den Ausschluss sprechen. Die Konsultationen laufen über die gemeinsame Beteiligungsplattform aus Kapitel 4.
- **Bürger, Patientenverbände, Ärzteverbände, Wissenschaft und Industrie** können Stellungnahmen einbringen.
- **Begründete Entscheidung** mit veröffentlichten Argumenten und Minderheitsmeinungen.
- **Regelmäßige Überprüfung** des Leistungskatalogs durch Sunset-Klauseln aus Kapitel 4.

Diese Struktur macht klar: Die Bürger-Gesundheits-Versicherung ist nicht eine technokratische Veranstaltung, in der Experten hinter verschlossenen Türen entscheiden. Sie ist eine transparente, demokratisch nachvollziehbare Struktur, in der wissenschaftliche Evidenz, Patientenerfahrung und politische Verantwortung in einer geordneten Weise zusammenwirken. Die Letztentscheidung bleibt demokratisch, eingebettet in die Sechsstufen-Architektur aus Kapitel 4.

> **Diskussionspunkt**
> Die Abschaffung nicht-evidenzbasierter Leistungen wird politisch hart umkämpft sein. In Deutschland sind Homöopathie und anthroposophische Medizin gesellschaftlich verankert. Viele Bürger nutzen diese Therapien und sind überzeugt von ihrer Wirksamkeit. Die Reform wird als "Eingriff in die Behandlungsfreiheit" wahrgenommen werden. Die Antwort des Konzepts: Die Behandlungsfreiheit wird nicht eingeschränkt, nur die Solidarfinanzierung. Wer alternative Therapien wünscht, kann sie weiterhin in Anspruch nehmen – aber nicht aus den Beiträgen aller Versicherten finanzieren lassen. Diese Trennung ist konsistent mit dem wissenschaftlichen Mindeststandard aus Kapitel 4 und mit der Kennzeichnungspflicht für Hypothese und Fakt aus Kapitel 5.

### Beitragsstruktur: Konzept und Formel mit Variablen

Die Bürger-Gesundheits-Versicherung folgt einer linearen Beitragsstruktur. Diese Struktur ersetzt die heutige harte Beitragsbemessungsgrenze, oberhalb derer keine Beiträge mehr fällig werden. Stattdessen sinkt der Beitragssatz ab einem definierten Schwellenwert linear bis zu einem Endsockel.

**Die Grundlogik:**

Sei *E* das Jahres-Gesamteinkommen einer Person (alle Einkommensarten):

- Wenn *E* ≤ Schwellenwert 1: Beitragssatz = *p* (voller Satz)
- Wenn Schwellenwert 1 < *E* ≤ Schwellenwert 2: Beitragssatz sinkt linear von *p* auf *q*
- Wenn *E* > Schwellenwert 2: Beitragssatz = *q* (Endsockel)

**Die Variablen (konstitutiv für die Struktur):**

- Schwellenwert 1: Punkt, ab dem die lineare Absenkung beginnt – orientiert am heutigen Niveau der Beitragsbemessungsgrenze
- Schwellenwert 2: Punkt, ab dem der Endsockel greift
- *p*: voller Beitragssatz für die breite Mitte
- *q*: Endsockel für Spitzeneinkommen

Die Formel mit ihren vier Variablen ist konstitutiv für die Struktur und bleibt im Modul. Die konkreten illustrativen Größenordnungen (Schwellenwert 1 in der Größenordnung der heutigen Beitragsbemessungsgrenze, Schwellenwert 2 im Bereich sehr hoher Einkommen, voller Satz im Bereich des heutigen GKV-Satzes, Endsockel als niedriger einstelliger Prozentsatz) sowie die drei Rechenbeispiele sind als illustrative Kalibrierungen in der Anlage `anlagen/finanzierungslogik.md` dokumentiert, mit Prüfampel "offen, externe Kalibrierung".

**Wichtiger Hinweis zur Kalibrierung:**

Die endgültige Kalibrierung – also die konkrete Festlegung der Schwellenwerte und der Beitragssätze *p* und *q* – erfolgt durch volkswirtschaftliche Modellierung mit Sensitivitätsanalysen. Diese Modellierung muss die Wechselwirkungen mit dem gesamten Steuer- und Sozialsystem berücksichtigen, die Finanzierung der integrierten Pflegevollversicherung sichern und einen Realitätscheck durch Wirtschaftsexperten durchlaufen. Die Detailausarbeitung erfolgt in der Anlage `anlagen/finanzierungslogik.md`. Das Modul beschränkt sich auf das Konzept und den groben Rahmen mit der Formel und den Variablen.

> **Juristische Einordnung**
> Die Beitragspflicht auf alle Einkommensarten ist verfassungsrechtlich begründungsbedürftig, weil Kapitalerträge und Mieteinnahmen heute zwar besteuert (Abgeltungsteuer, Einkommensteuer), aber nicht mit Sozialversicherungsbeiträgen belastet werden. Die zusätzliche Beitragspflicht ist gerechtfertigt durch das Solidaritätsprinzip aus Art. 20 GG und die Gleichbehandlung verschiedener Einkommensarten: Wenn die Gesundheitsleistung allen zugutekommt, soll auch jeder nach seiner Leistungsfähigkeit beitragen – unabhängig davon, ob seine Leistungsfähigkeit aus Arbeit oder Kapital stammt. Das Bundesverfassungsgericht hat in vergleichbaren Fällen (Pflegeversicherung, Solidaritätszuschlag) ähnliche Argumentationen anerkannt. Die lineare Absenkung bei sehr hohen Einkommen wahrt die Verhältnismäßigkeit und schließt eine konfiskatorische Belastung aus.


<a id="teil-d-arbeitslosenversicherung-mit-gleitender-bruecke"></a>
## Teil D: Arbeitslosenversicherung mit gleitender Brücke

### Die Position des Konzepts

Die Arbeitslosenversicherung wird so reformiert, dass sie alle Erwerbstätigen einbezieht und einen gleitenden, würdewahrenden Übergang zwischen Erwerbstätigkeit, Arbeitslosenversicherung und Grundsicherung schafft. Die zentrale Idee ist die gleitende Brücke: kein harter Absturz vom Arbeitslosengeld in die Grundsicherung, sondern ein abgestufter Übergang, der Sicherheit gibt und gleichzeitig Aktivierungsanreize wahrt.

Die wichtigsten strukturellen Merkmale:

- **Pflichteinbeziehung aller Erwerbstätigen**, einschließlich Selbstständiger.
- **Gleitende Brücke** statt harter Statusübergänge: Das Leistungsniveau sinkt schrittweise und vorhersehbar, nicht abrupt.
- **Verzahnung mit der aktivierenden Sozialhilfe** aus dem Modul Reziproke Solidarität.
- **Würdewahrung** durch soziale Mindestteilhabe und Schutz des Existenzminimums.

### Einbeziehung der Selbstständigen

Selbstständige sind heute weitgehend von der Arbeitslosenversicherung ausgeschlossen. Im neuen System sind sie pflichtversichert. Damit erhalten sie bei Auftragsverlust, Geschäftsaufgabe oder wirtschaftlicher Notlage einen Schutz, der ihnen heute fehlt.

Die Beitragsbemessung folgt dem tatsächlichen Einkommen. Die lineare Beitragslogik gilt entsprechend. Selbstständige mit schwankendem Einkommen zahlen Beiträge auf Basis eines Durchschnitts- oder Vorjahreseinkommens, mit Anpassungsmechanismen für starke Schwankungen.

### Die gleitende Brücke: Drei Stufen

Die gleitende Brücke ersetzt den heutigen harten Übergang vom Arbeitslosengeld I (versicherungsbasiert, einkommensbezogen) zum Bürgergeld (bedarfsbasiert, deutlich niedriger). Dieser harte Übergang ist heute eine zentrale Quelle von Abstiegsangst – gerade in der Mitte der Gesellschaft, wo Menschen mit qualifizierten Berufen und mittleren Einkommen befürchten, bei längerer Arbeitslosigkeit schnell den sozialen Status zu verlieren.

**Stufe 1: Versicherungsleistung (einkommensbezogen).**
In der ersten Phase der Arbeitslosigkeit erhält die Person eine einkommensbezogene Versicherungsleistung, die an das vorherige Einkommen anknüpft. Die Dauer dieser Phase richtet sich nach der Dauer der vorherigen Beitragszahlung. Diese Stufe entspricht im Prinzip dem heutigen Arbeitslosengeld I, ist aber durch die Einbeziehung aller Erwerbstätigen breiter abgesichert.

**Stufe 2: Gleitende Übergangsleistung (abschmelzend).**
Statt eines harten Absturzes folgt eine gleitende Übergangsleistung, die schrittweise und vorhersehbar abschmilzt. Die Person weiß genau, wie sich ihre Leistung über die Zeit entwickelt, und kann sich darauf einstellen. Während dieser Phase greifen die Aktivierungs- und Qualifizierungsangebote aus dem Modul Reziproke Solidarität und aus Kapitel 1 (Bildungs- und Übergangsoffensive, Qualifizierungsgehalt bei automatisierungsbedingtem Arbeitsplatzverlust). Die gleitende Brücke schafft Zeit und Sicherheit für eine qualifizierte Neuorientierung, statt Menschen in Panik in unpassende Beschäftigung zu drängen.

**Stufe 3: Grundsicherung mit aktivierender Sozialhilfe.**
Am Ende der gleitenden Brücke steht die Grundsicherung, die nahtlos in die aktivierende Sozialhilfe aus dem Modul Reziproke Solidarität übergeht. Hier greift die Drei-Gruppen-Logik des Moduls Reziproke Solidarität, mit allen Schutzmechanismen.

### Verzahnung mit der aktivierenden Sozialhilfe aus Reziproke Solidarität

Am Übergang von der Arbeitslosenversicherung in die Grundsicherung greift die Logik des Moduls Reziproke Solidarität. Dabei wird die entschärfte, nicht-stigmatisierende Sprache des Moduls konsequent verwendet:

- **Gruppe 1 – Personen ohne hinreichende Mitwirkungsfähigkeit:** Wer aus gesundheitlichen, altersbedingten oder anderen objektiven Gründen nicht oder nur eingeschränkt leistungsfähig ist, wird bedingungslos getragen. Das Existenzminimum aus Art. 1 GG ist unantastbar.
- **Gruppe 2 – Personen mit Unterstützungsbedarf auf dem Weg zur Mitwirkung:** Wer grundsätzlich leistungsfähig ist, aber Unterstützung braucht, erhält Befähigung: Qualifizierung, Beratung, gesundheitliche und psychosoziale Begleitung, Vermittlung. Die Mitwirkung wird erwartet, aber begleitet und ermöglicht.
- **Gruppe 3 – Personen mit festgestellter Mitwirkungsfähigkeit ohne hinreichenden Mitwirkungsgrund:** Wer nach überprüfter Einzelfallentscheidung tatsächlich leistungsfähig ist und dennoch ohne hinreichenden Grund nicht mitwirkt, unterliegt der Mitwirkungserwartung mit Konsequenzen – nur nach individueller Prüfung und mit allen rechtsstaatlichen Schutzmechanismen.

Die Einordnung erfolgt durch qualifizierte Sozialarbeiter als erste Diagnoseinstanz, nicht automatisiert. Die soziale Mindestteilhabe bleibt in jedem Fall gesichert. Der Aktivitätsbonus erweitert die Teilhabe nach oben, ohne dass das Minimum nach unten entzogen wird. Alle Schutzmechanismen des Moduls Reziproke Solidarität greifen: Verhältnismäßigkeit, gerichtliche Überprüfbarkeit, Aufsicht durch die Fachkammer Sozialstaat und Reziprozität mit Schwerpunkt Ethik, Schutz des Existenzminimums.

> **Diskussionspunkt**
> Die gleitende Brücke ist ein zentrales würdepolitisches Element. Sie nimmt die Abstiegsangst der Mitte ernst, ohne die Aktivierungsanreize aufzugeben. Kritiker von links könnten argumentieren, dass jede Abschmelzung der Leistung Druck erzeugt; Kritiker von rechts könnten argumentieren, dass die gleitende Brücke die Aktivierung verzögert. Das Konzept hält die gleitende Brücke für den ausbalancierten Mittelweg: Sie gibt Sicherheit und Zeit für qualifizierte Neuorientierung, wahrt aber durch die vorhersehbare Abschmelzung und die Verzahnung mit der Aktivierung den Anreiz zur Wiedereingliederung. Die genaue Kalibrierung der Abschmelzung ist eine politische und volkswirtschaftliche Frage, die in der Anlage `anlagen/finanzierungslogik.md` behandelt wird.

> **Juristische Einordnung**
> Die Einbeziehung der Selbstständigen in die Arbeitslosenversicherung ist verfassungsrechtlich unproblematisch, soweit sie an die allgemeine Logik der Pflichtversicherung anknüpft. Die gleitende Brücke bewegt sich im Rahmen des Sozialstaatsprinzips aus Art. 20 GG. Der Übergang in die Grundsicherung muss die Vorgaben des BVerfG-Sanktionsurteils von 2019 wahren: Verhältnismäßigkeit, Schutz des Existenzminimums, keine vollständige Leistungsentziehung. Die soziale Mindestteilhabe aus dem Modul Reziproke Solidarität konkretisiert diese Vorgaben.


<a id="teil-e-gesamtbetrachtung-und-zusammenwirken"></a>
## Teil E: Gesamtbetrachtung und Zusammenwirken

### Das Zusammenwirken der drei Versicherungen

Die drei Versicherungen dieses Moduls – Kranken-, Pflege- und Arbeitslosenversicherung – sind keine isolierten Reformen, sondern eine zusammenhängende Architektur. Sie folgen den gleichen drei Grundsätzen (Pflichteinbeziehung aller Erwerbstätigen, alle Einkommensarten als Bemessungsgrundlage, lineare Beitragsstruktur). Sie verzahnen sich miteinander und mit der Gesamtkonzeption.

Die integrierte Bürger-Gesundheits-Versicherung deckt Krankheit und Pflege über die gesamte Lebensspanne ab. Die Arbeitslosenversicherung mit gleitender Brücke sichert die Erwerbsphase und schafft einen würdewahrenden Übergang in die Grundsicherung. Alle drei Versicherungen beziehen alle Erwerbstätigen ein und beenden die strukturellen Ungleichheiten zwischen Berufsgruppen und Einkommensarten.

### Gemeinsame Phasenarchitektur nach Architektur-Regel 3

Die Phasen dieses Moduls sind mit der gemeinsamen Phasenarchitektur nach Architektur-Regel 3 der `ARCHITEKTUR.md` abgeglichen.

**Gemeinsame Aufbauphase 2026-2028:** Das Modul nutzt die gemeinsame Governance-Startarchitektur aus Kapitel 4. In dieser Phase werden die Fachkammer Sozialstaat und Reziprozität, die Datenarchitektur der erweiterten Bemessungsgrundlage (mit getrennten Datenräumen), die Sechsstufen-Architektur und das Deutschland-Dashboard aufgebaut. Der gesetzliche Rahmen der Versicherungsreform wird vorbereitet und beschlossen. Parallel wird die Versorgungssicherheit aus Kapitel 2 aufgebaut, ohne die das Solidarversprechen praktisch nicht eingelöst werden kann.

**Phase 1 (Vorbereitung):** Beginnt nach der gemeinsamen Aufbauphase. Stichtag für den Stopp neuer PKV-Vollversicherungs-Verträge, Aufbau der erweiterten Bürgerversicherungs-Strukturen, erste Pilot-Übernahmen.

**Phase 2 (Übergang):** Freiwilliger Wechsel der Bestandsversicherten, Umstellung der Versicherungsunternehmen, Ausbau der integrierten Pflegevollversicherung, erste Zwischenevaluation nach fünf Jahren durch den Wissenschafts- und Resilienzrat.

**Phase 3 (Konsolidierung):** Überführung der verbleibenden Bestandsversicherten, Behandlung der Altersrückstellungen gemäß Wahlrecht, formale Beendigung der PKV-Vollversicherung, abschließende Evaluation.

Die kapitelspezifische Phasenlogik (10-15 Jahre für die Versicherungsüberführung) liegt damit innerhalb des Rahmens von Architektur-Regel 3: gemeinsame Aufbauphase 2026-2028, danach kapitelspezifische Umsetzung.

### Nachjustierung über die Sechsstufen-Architektur

Werden zentrale Ziele verfehlt oder zeigen sich unerwartete Wirkungen, greift die Sechsstufen-Architektur aus Kapitel 4 – nicht eine separate Kommission. Die wissenschaftliche Folgenabschätzung erfolgt durch die zuständigen Fachkammern (insbesondere die Fachkammer Sozialstaat und Reziprozität), parlamentarische Beratung mit den Folgenabschätzungs-Daten, suspensives Veto möglich, Überstimmung durch qualifizierte Mehrheit, vier Mechanismen bei Abweichung (Berichtspflicht, Monitoring, Sunset-Klausel, Volksentscheid-Option), Volksentscheid als letzte Instanz bei substantieller Persistenz des Konflikts.

Die Zwischenevaluationen (nach fünf Jahren) und die Sunset-Klauseln zwingen zur regelmäßigen Neubewertung. Damit bleibt die Versicherungsreform lernfähig und korrigierbar, ohne dass parallele Korrekturstrukturen die etablierte Architektur unterlaufen.

### Generationengerechtigkeit und Generationenbilanz

Die Versicherungsreform wird in der Generationenbilanz aus Kapitel 5 bewertet. Die konsolidierten neun Bewertungsdimensionen (langfristige Kosten, langfristiger Nutzen und Teilhabewirkungen, Betriebslasten, soziale Mobilität, Klimawirkung, Infrastrukturzustand, Anbieterabhängigkeiten, Kompetenzaufbau, Datenschutzfolgen) werden auf die Reform angewendet.

Die Reform ist im Kern eine Generationengerechtigkeits-Reform: Sie verteilt die Beitragslast fairer zwischen den Generationen, stabilisiert die Beitragssätze für die heute Jüngeren und verhindert den ungeordneten Kollaps, der die kommenden Generationen am härtesten treffen würde. Die Verzahnung mit der Generationenrücklage und dem Schuldenbremse-Sondermodell aus Kapitel 5 ist substantiell.

### Finanzielle Gesamtbetrachtung

Die finanzielle Gesamtbetrachtung des Moduls erfolgt in der Anlage `anlagen/finanzierungslogik.md`. Dort werden die Beitragsstruktur kalibriert, die Wechselwirkungen mit dem Steuer- und Sozialsystem modelliert, die Finanzierung der integrierten Pflegevollversicherung gesichert und die Übergangskosten (Behandlung der Altersrückstellungen, Strukturumbau) abgeschätzt.

Das Modul selbst beschränkt sich auf das Konzept und den groben Rahmen. Die illustrativen Größenordnungen sind als zu kalibrierender Rahmen mit Prüfampel "offen, externe Kalibrierung" gekennzeichnet. Die endgültige Festlegung erfolgt durch volkswirtschaftliche Modellierung und externe Expertise.


<a id="teil-f-risiken-und-ehrliche-begrenzungen"></a>
## Teil F: Risiken und ehrliche Begrenzungen

Das Modul benennt seine Risiken und Begrenzungen transparent. Sie werden in fünf Kategorien geführt, analog zu den Kapiteln.

### Risiko 1: Politische Risiken

**Widerstand organisierter Interessen.** Die private Versicherungswirtschaft, die Ärzteverbände (soweit sie von der PKV-Vergütung profitieren) und Teile der Beamtenschaft werden Widerstand leisten. Lösungsansatz: Die Mechanismen aus Kapitel 4 (wissenschaftlicher Mindeststandard, Karenzzeiten, transparente Verfahren, messbare Wahlversprechen, Sechsstufen-Architektur) reduzieren den Einfluss organisierter Interessen gegenüber wissenschaftlicher Evidenz und Generationengerechtigkeit.

**Wahrnehmung als Eingriff in die Behandlungsfreiheit.** Die Abschaffung nicht-evidenzbasierter Leistungen wird als Eingriff wahrgenommen werden. Lösungsansatz: Klare Kommunikation der Trennung zwischen Behandlungsfreiheit (bleibt) und Solidarfinanzierung (nur evidenzbasiert).

**Wahrnehmung als Enteignung.** Die Überführung der PKV und die Behandlung der Altersrückstellungen werden als Enteignung wahrgenommen werden. Lösungsansatz: Das Wahlrecht über die Altersrückstellungen, der Bestandsschutz und die lange Übergangsfrist wahren das Eigentum und die Verhältnismäßigkeit.

### Risiko 2: Verwaltungs- und Datenschutzrisiken

**Komplexität der erweiterten Bemessungsgrundlage.** Die Erfassung aller Einkommensarten (Lohn, Kapital, Mieten, selbstständige Tätigkeit) erfordert einen Datenfluss zwischen Finanzbehörden und Versicherungsträgern. Das ist verwaltungstechnisch anspruchsvoll und datenschutzrechtlich sensibel.

**Datenschutz über die Sechs-Schutzräume-Logik aus Kapitel 3.** Der Datenfluss zwischen Finanzbehörden und Versicherungsträgern wird über die Sechs-Schutzräume-Logik aus Kapitel 3 abgesichert. Konkret betrifft das zwei der sechs Schutzräume:

- Der **Gesundheits-Schutzraum** schützt die Gesundheits- und Versicherungsdaten der Bürger. Versicherungsträger erhalten nur die für die Beitragsbemessung notwendigen Einkommensinformationen, nicht die zugrunde liegenden Detaildaten.
- Der **Steuer-Schutzraum** schützt die Steuer- und Einkommensdaten. Die Finanzbehörden übermitteln nur die für die Beitragsbemessung erforderlichen aggregierten Einkommensgrößen an die Versicherungsträger, mit strikter Zweckbindung.

Die beiden Datenräume werden getrennt geführt; es gibt keine ungehinderte Zusammenführung. Die Übermittlung folgt dem Prinzip der Datenminimierung: nur die für die Beitragsbemessung notwendigen Informationen, mit strikter Zweckbindung und ohne Profilbildung. Diese Architektur ist konsistent mit den sechs Schutzräumen aus Kapitel 3 (Gesundheit, Bildung, Sozialleistung, Steuer, Migration, Justiz) und mit den Datenschutzregeln aus Architektur-Regel 6.

**Übergangskomplexität.** Der parallele Betrieb von altem und neuem System während der 10-15-jährigen Übergangsfrist ist komplex. Lösungsansatz: klare Phasenstruktur, Übernahme bestehender Strukturen und Mitarbeiter, wissenschaftliche Begleitung.

> **Juristische Einordnung**
> Der Datenfluss zwischen Finanzbehörden und Versicherungsträgern tangiert das informationelle Selbstbestimmungsrecht und das Steuergeheimnis (§ 30 AO). Die Übermittlung von Einkommensdaten zur Beitragsbemessung ist verfassungsrechtlich machbar, wenn sie klar zweckgebunden ist, dem Prinzip der Datenminimierung folgt und über getrennte Datenräume (Gesundheits- und Steuer-Schutzraum aus Kapitel 3) abgesichert wird. Die Detailausarbeitung erfolgt in der Anlage `anlagen/juristische-fragen.md`.

### Risiko 3: Rechtliche Risiken

**Verfassungsrechtliche Eingriffstiefe.** Die Reform greift in Vertrauensschutz, Eigentumsgarantie (Art. 14 GG), Berufsfreiheit (Art. 12 GG) und das Alimentation-Prinzip (Art. 33 Abs. 5 GG) ein. Lösungsansatz: lange Übergangsfristen, Bestandsschutz, Wahlrecht über die Altersrückstellungen, Wahlfreiheit der Versicherungsunternehmen, Kompensationsmechanismen. Die ausführliche juristische Prüfung erfolgt in der Anlage `anlagen/juristische-fragen.md`.

**EU-rechtliche Fragen.** Die Beendigung des PKV-Vollversicherungs-Geschäftsmodells könnte EU-binnenmarktrechtliche Fragen aufwerfen (Niederlassungsfreiheit, Dienstleistungsfreiheit). Lösungsansatz: Ausgestaltung im EU-rechtskonformen Rahmen, Wahlfreiheit der Unternehmen.

### Risiko 4: Finanzielle Risiken

**Kalibrierungsrisiko der Beitragsstruktur.** Wenn die lineare Beitragsstruktur falsch kalibriert wird, kann sie entweder die Mitte überlasten oder die Finanzierung gefährden. Lösungsansatz: volkswirtschaftliche Modellierung mit Sensitivitätsanalysen, Realitätscheck durch Wirtschaftsexperten, Anpassungsmechanismen über die Sechsstufen-Architektur.

**Liquiditätsrisiko bei den Altersrückstellungen.** Eine zu schnelle Auszahlung der Altersrückstellungen könnte die Liquidität der Versicherungsunternehmen überlasten. Lösungsansatz: gestreckte Auszahlung über die Übergangsfrist.

### Risiko 5: Versorgungsrisiken

**Formales Solidarversprechen ohne reale Versorgung.** Die beste Versicherungsstruktur nützt nichts, wenn die Versorgung praktisch nicht verfügbar ist. Lösungsansatz: Die Versorgungssicherheit aus Kapitel 2 ist die zwingende Voraussetzung. Ohne sie bleibt das Solidarversprechen formal. Das Gleichwertigkeitsraster aus Kapitel 5 macht die Versorgungssicherheit regional messbar.

**Fachkräftemangel im Gesundheits- und Pflegebereich.** Die integrierte Pflegevollversicherung erhöht die Nachfrage nach Pflegeleistungen. Ohne ausreichendes Personal entstehen Wartezeiten. Lösungsansatz: Verzahnung mit Kapitel 2 (Pflegepersonal), Kapitel 1 (Pflegeassistenz-Sonderregel, Bildungs- und Übergangsoffensive) und Kapitel 3 (Ausbildung).

### Ehrliche Begrenzungen

Das Modul benennt seine Grenzen offen:

- Die Beitragskalibrierung ist noch nicht erfolgt und muss volkswirtschaftlich modelliert werden.
- Die genaue Länge der Übergangsfrist ist eine politische Abwägung.
- Die verfassungsrechtliche Tragfähigkeit mehrerer Elemente muss juristisch vertieft geprüft werden.
- Die Reform funktioniert nur in Verzahnung mit Kapitel 2 (Versorgung), Kapitel 4 (politische Durchsetzbarkeit) und Kapitel 5 (generationelle Einbettung). Isoliert ist sie nicht tragfähig.


<a id="verzahnung-mit-der-gesamtkonzeption"></a>
## Verzahnung mit der Gesamtkonzeption

Das Modul Solidarische Versicherungen ist eng mit den Kapiteln und den anderen Modulen verzahnt.

**Verbindung zu Kapitel 1 (Produktivitäts-Dividende):**
Die Pflichtversicherung für alle Erwerbstätigen folgt der Übergangslogik aus Kapitel 1. Die Bildungs- und Übergangsoffensive und das Qualifizierungsgehalt aus Kapitel 1 greifen in der gleitenden Brücke der Arbeitslosenversicherung. Die Pflegeassistenz-Sonderregel aus Kapitel 1 ist für die integrierte Pflegevollversicherung relevant.

**Verbindung zu Kapitel 2 (Öffentliche Grundversorgung):**
Die Versorgungssicherheit ist die zwingende praktische Voraussetzung der Bürger-Gesundheits-Versicherung. Die Bürgerversicherung wird in Kapitel 2 operativ als Teil der Gesundheits-Grundversorgung behandelt. Dieses Modul liefert die Versicherungs-Architektur, Kapitel 2 die Versorgungsstruktur.

**Verbindung zu Kapitel 3 (Bildung, Technologie und Verwaltung):**
Die Sechs-Schutzräume-Logik aus Kapitel 3 (insbesondere Gesundheits- und Steuer-Schutzraum) sichert den Datenfluss zwischen Finanzbehörden und Versicherungsträgern. Die Verwaltungsdigitalisierung mit analoger Alternative gilt auch für die Versicherungsverwaltung. Die Ausbildung von Gesundheits- und Pflegefachkräften ist in Kapitel 3 verankert.

**Verbindung zu Kapitel 4 (Agile wissenschaftsgetriebene Politik):**
Die Sechsstufen-Architektur ist die Hochrisiko-Verzahnung und der Nachjustierungsmechanismus. Die Fachkammer Sozialstaat und Reziprozität ist die fachliche Aufsicht. Der wissenschaftliche Mindeststandard prägt den evidenzbasierten Leistungskatalog. Die Karenzzeiten und transparenten Verfahren sind die politische Voraussetzung der Durchsetzung. Die gemeinsame Beteiligungsplattform trägt die Leistungskatalog-Konsultationen.

**Verbindung zu Kapitel 5 (Gesellschaftlicher Zusammenhalt):**
Die Bürgerversicherung ist in Kapitel 5 (Säule 3) als Teil der Generationengerechtigkeits-Reform verankert. Die Generationenbilanz (neun Dimensionen) bewertet die Versicherungsreform. Das Gleichwertigkeitsraster macht die Versorgungssicherheit regional messbar. Die Verzahnung mit Generationenrücklage und Schuldenbremse-Sondermodell ist substantiell.

**Verbindung zum Modul Reziproke Solidarität:**
Die Pflichtversicherung für alle Erwerbstätigen ist in beiden Modulen als Element des Reziprozitätspakets verankert. Die aktivierende Sozialhilfe mit der Drei-Gruppen-Logik greift am Übergang von der Arbeitslosenversicherung in die Grundsicherung. Die Familienmitversicherung verzahnt sich mit der Mitwirkungslogik des Moduls Reziproke Solidarität. Die Schutzmechanismen (Existenzminimum, soziale Mindestteilhabe, Fachkammer mit Schwerpunkt Ethik, gerichtliche Überprüfbarkeit) gelten durchgängig.

**Verbindung zu den Anlagen:**
Die Beitragskalibrierung, die illustrativen Größenordnungen und die Übergangskosten sind in `anlagen/finanzierungslogik.md` dokumentiert. Die verfassungsrechtlichen Fragen sind in `anlagen/juristische-fragen.md` ausgearbeitet.


<a id="die-leitformel-zum-schluss"></a>
## Die Leitformel zum Schluss

Das Modul Solidarische Versicherungen stellt die Kranken-, Pflege- und Arbeitslosenversicherung auf eine zusammenhängende, zukunftsfeste Architektur. Es beendet die strukturellen Ungleichheiten zwischen Berufsgruppen und Einkommensarten. Es macht die Pflege finanzierbar, ohne Familien zu ruinieren. Es schafft mit der gleitenden Brücke einen würdewahrenden Übergang zwischen Erwerbstätigkeit und Grundsicherung.

Das Modul folgt der grundsätzlichen Linie der Zukunftsdemokratie: lösungsorientiert statt lager-orientiert. Es entscheidet sich für die geordnete Reform statt für den ungeordneten Kollaps. Es nimmt die demografische Realität ernst, ohne zu dramatisieren. Es wahrt die verfassungsrechtlichen Grenzen durch lange Übergangsfristen, Bestandsschutz, Wahlrechte und Kompensationsmechanismen.

Das Modul ist kein fertiges Gesetz, sondern eine Diskussionsgrundlage. Es benennt seine offenen Fragen, seine Kalibrierungsbedarfe und seine verfassungsrechtlichen Grenzen ehrlich. Es funktioniert nur in Verzahnung mit der Gesamtkonzeption – mit der Versorgung aus Kapitel 2, der politischen Architektur aus Kapitel 4, der generationellen Einbettung aus Kapitel 5 und der Mitwirkungslogik des Moduls Reziproke Solidarität.

Die Leitformel bleibt:

> *Alle tragen nach Leistungsfähigkeit. Alle erhalten nach Bedarf. Versorgung wird gesichert.*

Alle tragen nach Leistungsfähigkeit – durch die Pflichteinbeziehung aller Erwerbstätigen, die Bemessung auf alle Einkommensarten und die lineare Beitragsstruktur, die auch sehr hohe Einkommen substanziell einbezieht.

Alle erhalten nach Bedarf – durch den evidenzbasierten Leistungskatalog, die integrierte Pflegevollversicherung ohne ruinöse Eigenanteile und die gleitende Brücke, die Abstiegsangst nimmt.

Versorgung wird gesichert – durch die zwingende Verzahnung mit der Versorgungssicherheit aus Kapitel 2, ohne die das Solidarversprechen formal bliebe.

Solidarität ist kein Selbstzweck und keine Rhetorik. Sie ist das Prinzip, das eine alternde, vielfältige Gesellschaft zusammenhält – wenn alle nach ihrer Leistungsfähigkeit beitragen und alle nach ihrem Bedarf versorgt werden.

---

**Dieses Modul ist Teil des Konzepts Zukunftsdemokratie. Aktuelle Version siehe README.md. Strukturelle Grundregeln siehe `ARCHITEKTUR.md`. Finanzielle Detail-Architektur siehe `anlagen/finanzierungslogik.md`.**
