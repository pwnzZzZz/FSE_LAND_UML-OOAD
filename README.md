# UML-OOAD / Objektorientierte Analyse und Design / Übungszettel UML

# Objektorientierte Analyse 

Objektorientierte Analyse und Design (OOAD) sind objektorientierte Varianten der zwei allgemeinen Tätigkeiten Anforderungsanalyse (objektorientierte Analyse) und Systementwurf (Obejktorientiertes Design) im Entwicklungsprozess eines Softwaresystems.

Als Standardnotation für objektorientierte Modelle hat sich die Unified Modeling Language (kurz UML) etabliert. Ein Vorgehensmodell, das speziell für objektorientierte Techniken und die UML entwickelt wurde, ist der sogenannte Rational Unified Process (RUP).

Die Objektorientierte Analyse (OOA) ist der erste Schritt des OOAD-Prozesses. Hierbei wird das zu entwickelnde System analysiert, um ein besseres Verständnis seiner Anforderungen und Funktionalitäten zu erlangen. Der Fokus liegt dabei auf der Identifikation von Objekten im System, die miteinander interagieren, um das Problem zu lösen. In der OOA werden die Anforderungen des Systems identifiziert, relevante Objekte identifiziert und beschrieben, ein Objektmodell erstellt, Beziehungen zwischen Objekten definiert und das Verhalten der Objekte spezifiziert.

Die Objektorientierte Design (OOD) ist der zweite Schritt des OOAD-Prozesses. In diesem Schritt werden die Ergebnisse der OOA genommen und auf der Grundlage der Anforderungen und Funktionalitäten des Systems ein Design erstellt. Das Ziel der OOD ist es, ein Systemdesign zu erstellen, das das System effektiv und effizient lösen kann. Es gibt verschiedene Designprinzipien, wie z.B. das Prinzip der Vererbung, der Polymorphie und der Abstraktion, die während der OOD angewendet werden.

Zusammenfassend ist OOAD ein Prozess, der darauf abzielt, ein System auf der Grundlage der OOP-Prinzipien zu entwickeln. Es umfasst die Objektorientierte Analyse (OOA) und das Objektorientierte Design (OOD) als zwei separate Schritte, die aufeinander aufbauen. Das Ergebnis des OOAD-Prozesses ist ein detailliertes Design, das als Grundlage für die Implementierung des Systems dient.

## Ziele:
Dadurch, dass in den Entwicklungsphasen Analyse und Design bereits objektorientierte Techniken eingesetzt werden, wird der Übergang zur Implementierung in einer objektorientierten Programmiersprache erleichtert.

- Verständnis der Anforderungen: Der erste Schritt bei der OOAD ist das Verständnis der Anforderungen an das System. Dies umfasst die Identifizierung der Bedürfnisse und Anforderungen der Benutzer sowie die Funktionalität, die das System bereitstellen soll.

- Modellierung des Systems: Das nächste Ziel der OOAD ist die Modellierung des Systems mithilfe von Objekten und Klassen. Hierbei werden die Anforderungen des Systems in ein Modell übertragen, das eine detaillierte Darstellung der Systemkomponenten und -funktionen bietet.

- Erstellung von Klassen und Objekten: Auf der Grundlage des erstellten Modells werden Klassen und Objekte erstellt, um das System funktionsfähig zu machen. Dies beinhaltet die Festlegung von Attributen und Methoden sowie die Zuweisung von Funktionen und Eigenschaften an die einzelnen Objekte.

- Implementierung des Systems: Nach der Erstellung der Klassen und Objekte wird das System implementiert, indem der Code geschrieben und getestet wird. Hierbei werden auch geeignete Software-Tools verwendet, um die Programmierung und das Debugging zu erleichtern.

- Wartung und Weiterentwicklung des Systems: Ein weiteres Ziel der OOAD ist die Wartung und Weiterentwicklung des Systems, um sicherzustellen, dass es weiterhin den Anforderungen entspricht und effektiv arbeitet. Hierbei werden auch Änderungen und Erweiterungen an der Software vorgenommen, um die Leistung und Funktionalität des Systems zu verbessern.

Insgesamt zielt die OOAD darauf ab, ein effektives und effizientes System zu schaffen, das den Bedürfnissen der Benutzer entspricht und leicht wartbar und erweiterbar ist.

## Requirements:
Anforderungen für die Objektorientierte Analyse und Design

- Funktionale Anforderungen: Dies sind die spezifischen Anforderungen an die Funktionen, die das System bereitstellen soll. Beispielsweise könnte eine Anforderung sein, dass das System in der Lage sein muss, Daten zu speichern und abzurufen.

- Nicht-funktionale Anforderungen: Diese beziehen sich auf Eigenschaften des Systems, die nicht direkt mit seiner Funktionalität zusammenhängen. Beispiele hierfür sind die Leistung, Skalierbarkeit, Sicherheit, Benutzerfreundlichkeit und Wartbarkeit.

- Benutzeranforderungen: Diese Anforderungen beschreiben die Bedürfnisse und Erwartungen der Benutzer des Systems. Sie umfassen Aspekte wie Benutzeroberfläche, Datenzugriff und -manipulation, Integration mit anderen Systemen und ähnliches.

- Systemumgebung: Dies bezieht sich auf die Umgebung, in der das System ausgeführt wird, einschließlich Hardware, Betriebssystem, Netzwerk und ähnliches. Es ist wichtig, dass das System in der Umgebung, in der es betrieben wird, ordnungsgemäß funktioniert.

- Gesetzliche und regulatorische Anforderungen: Je nach Art des Systems müssen auch gesetzliche und regulatorische Anforderungen berücksichtigt werden, wie beispielsweise Datenschutz, Barrierefreiheit, Datenschutz und ähnliches.

Insgesamt ist es wichtig, alle relevanten Anforderungen zu identifizieren und zu dokumentieren, um sicherzustellen, dass das System den Bedürfnissen der Benutzer entspricht und effektiv arbeitet.

## Strukturelle Modellierung:
Die strukturelle Modellierung ist ein wichtiger Teil der Objektorientierten Analyse und Design (OOAD). Hierbei werden die statischen Aspekte des Systems modelliert, wie die Klassen und Objekte sowie deren Beziehungen zueinander. Die strukturelle Modellierung besteht aus folgenden Elementen:

- Klassen: Eine Klasse ist eine abstrakte Darstellung eines Konzepts oder einer Entität im System, die Eigenschaften und Verhaltensweisen besitzt. Klassen können Attribute (Eigenschaften) und Methoden (Funktionen) haben, die die Verhaltensweisen der Klasse definieren.

- Objekte: Objekte sind Instanzen von Klassen und repräsentieren spezifische Entitäten oder Konzepte im System. Jedes Objekt hat einen Zustand, der durch seine Attribute beschrieben wird, und kann verschiedene Methoden ausführen, um seine Verhaltensweisen zu definieren.

- Beziehungen: Beziehungen beschreiben, wie Objekte und Klassen im System miteinander verbunden sind. Es gibt verschiedene Arten von Beziehungen, wie beispielsweise die Assoziation, die Vererbung und die Aggregation.

- Assoziation: Eine Assoziation beschreibt eine Beziehung zwischen zwei Klassen, die angibt, dass Objekte der einen Klasse Objekte der anderen Klasse kennen oder darauf zugreifen können.

- Vererbung: Vererbung beschreibt eine Beziehung zwischen Klassen, bei der eine Klasse (die Subklasse) die Eigenschaften und Verhaltensweisen einer anderen Klasse (der Superklasse) erbt. Dies ermöglicht es, Klassen hierarchisch zu organisieren und gemeinsame Eigenschaften und Verhaltensweisen zu definieren.

- Aggregation: Aggregation beschreibt eine Beziehung zwischen Klassen, bei der eine Klasse (der Aggregator) eine oder mehrere Instanzen einer anderen Klasse (der Aggregatklasse) besitzt. Aggregation ermöglicht es, komplexe Systeme durch die Kombination von kleineren Teilen zu modellieren.

Durch die strukturelle Modellierung können die statischen Aspekte des Systems klar und präzise modelliert werden, um ein besseres Verständnis des Systems zu erreichen und eine Grundlage für die Implementierung zu schaffen.

## Dynamische Modellierung:
Die Dynamische Modellierung ist ein wichtiger Teil der Objektorientierten Analyse und Design (OOAD). Hierbei werden die dynamischen Aspekte des Systems modelliert, wie die Abläufe und Prozesse im System, die durch die Interaktionen zwischen den Objekten ausgelöst werden. Die Dynamische Modellierung besteht aus folgenden Elementen:

- Zustandsdiagramme: Ein Zustandsdiagramm beschreibt den Lebenszyklus eines Objekts und zeigt die verschiedenen Zustände, die es durchlaufen kann, sowie die Ereignisse, die diese Zustände auslösen. Zustandsdiagramme sind nützlich, um komplexe Verhaltensweisen zu modellieren und zu verstehen, wie ein Objekt auf Ereignisse reagiert.

- Sequenzdiagramme: Ein Sequenzdiagramm zeigt die Interaktionen zwischen Objekten in einer bestimmten Sequenz, um einen bestimmten Zweck zu erfüllen. Es beschreibt die Reihenfolge der Nachrichten, die zwischen den Objekten ausgetauscht werden, um eine bestimmte Funktion auszuführen. Sequenzdiagramme sind nützlich, um die Interaktionen zwischen Objekten zu verstehen und zu modellieren.

- Aktivitätsdiagramme: Ein Aktivitätsdiagramm beschreibt den Ablauf eines Prozesses oder einer Funktion und zeigt, wie verschiedene Aktionen und Entscheidungen in einer bestimmten Sequenz ausgeführt werden. Es kann auch die Parallelität und die Bedingungen, die den Ablauf beeinflussen, modellieren. Aktivitätsdiagramme sind nützlich, um komplexe Prozesse oder Funktionen zu verstehen und zu modellieren.

- Kollaborationsdiagramme: Ein Kollaborationsdiagramm zeigt die Interaktionen zwischen Objekten, die zusammenarbeiten, um eine bestimmte Funktion auszuführen. Es beschreibt die Nachrichten, die zwischen den Objekten ausgetauscht werden, um Informationen zu teilen und Funktionen auszuführen. Kollaborationsdiagramme sind nützlich, um die Interaktionen zwischen Objekten zu verstehen und zu modellieren.

Durch die Dynamische Modellierung können die dynamischen Abläufe und Prozesse im System klar und präzise modelliert werden, um ein besseres Verständnis des Systems zu erreichen und eine Grundlage für die Implementierung zu schaffen.


# Anforderungsanalyse mit Anwendungsfällen
Arbeite dich in die Grundprinzipien der Anforderungsanalyse mit USE-Cases (Diagramm + textuelle Beschreibung + Mockup) ein.

## Grundlagen
Die Anforderungsanalyse mit Anwendungsfällen (Use Cases) ist eine Methode zur Erfassung, Analyse und Dokumentation von funktionalen Anforderungen für ein Softwaresystem aus der Perspektive der Benutzer. Im Gegensatz zu User Stories, die auf eine bestimmte Benutzeraktion und das gewünschte Ergebnis fokussiert sind, beschreiben Anwendungsfälle detaillierter die Interaktionen zwischen Benutzern (Akteuren) und dem System.

Hier sind einige Grundlagen zur Anforderungsanalyse mit Anwendungsfällen:

- Akteure:
Akteure repräsentieren die Rollen von Personen, anderen Systemen oder Organisationen, die mit dem System interagieren. Sie können primär (direkt) oder sekundär (indirekt) mit dem System interagieren.

- Anwendungsfälle:
Ein Anwendungsfall ist ein Szenario, das eine bestimmte Funktionalität des Systems beschreibt und wie ein Akteur mit dem System interagiert, um ein bestimmtes Ziel zu erreichen. Anwendungsfälle bestehen aus einer Reihe von Schritten oder Abläufen, die die Interaktion zwischen Akteuren und dem System beschreiben.

- Anwendungsfallspezifikation:
Die Anwendungsfallspezifikation ist die detaillierte Beschreibung eines Anwendungsfalls. Sie enthält typischerweise Informationen wie:
-   Name des Anwendungsfalls
-   Beschreibung oder Ziel des Anwendungsfalls
-   Akteure, die am Anwendungsfall beteiligt sind
-   Vorbedingungen (Bedingungen, die vor der Ausführung des Anwendungsfalls erfüllt sein müssen)
-   Nachbedingungen (Zustand des Systems nach der Ausführung des Anwendungsfalls)
-   Normaler Ablauf (Schritte, die im normalen Verlauf der Interaktion stattfinden)
-   Alternative Abläufe (alternative Schritte oder Verzweigungen, die auftreten können)
-   Ausnahmen oder Fehlerbedingungen (Szenarien, in denen der Anwendungsfall fehlschlägt oder abgebrochen wird)

- Anwendungsfalldiagramme:
Anwendungsfalldiagramme sind visuelle Darstellungen von Anwendungsfällen und ihren Beziehungen zu Akteuren. Sie sind Teil der Unified Modeling Language (UML) und helfen dabei, die Anforderungen und Interaktionen eines Systems auf einen Blick zu erfassen.

- Schritte zur Erstellung von Anwendungsfällen:
-   Identifizierung der Akteure: Identifizieren Sie die verschiedenen - -   Rollen, die mit dem System interagieren.
-   Identifizierung der Anwendungsfälle: Ermitteln Sie die verschiedenen Szenarien, in denen Akteure mit dem System interagieren, um ihre Ziele zu erreichen.
-   Erstellung von Anwendungsfallspezifikationen: Beschreiben Sie die Anwendungsfälle detailliert, einschließlich der Vorbedingungen, Nachbedingungen, normalen Abläufe, alternativen Abläufe und Fehlerbedingungen.
-   Erstellung von Anwendungsfalldiagrammen: Visualisieren Sie die Beziehungen zwischen Akteuren und Anwendungsfällen in einem Diagramm.
Die Anforderungsanalyse mit Anwendungsfällen ermöglicht es Ihnen, ein klares Verständnis der funktionalen


## Vorgehensweisen
Die Anforderungsanalyse mit Anwendungsfällen folgt einer strukturierten Vorgehensweise, um die funktionalen Anforderungen eines Systems zu erfassen und zu dokumentieren. Hier sind die üblichen Schritte, die bei der Anforderungsanalyse mit Anwendungsfällen verwendet werden:

1. Sammeln von Informationen:
Zu Beginn sollten Sie alle relevanten Informationen über das System und dessen Anforderungen sammeln. Dies kann durch Interviews, Workshops, Brainstorming-Sitzungen oder das Studium von Dokumenten und vorhandenen Systemen geschehen.

2. Identifizierung der Akteure:
Akteure sind die Personen, Systeme oder Organisationen, die mit dem zu entwickelnden System interagieren. Identifizieren Sie die verschiedenen Akteure und ihre Rollen, um ein klareres Bild der Interaktionen zu erhalten.

3. Identifizierung der Anwendungsfälle:
Ermitteln Sie die verschiedenen Szenarien, in denen Akteure mit dem System interagieren, um ihre Ziele zu erreichen. Anwendungsfälle repräsentieren typischerweise die Hauptfunktionen des Systems.

4. Dokumentation der Anwendungsfälle:
Für jeden identifizierten Anwendungsfall erstellen Sie eine detaillierte Anwendungsfallspezifikation. Diese sollte Informationen wie Name, Beschreibung, beteiligte Akteure, Vorbedingungen, Nachbedingungen, normaler Ablauf, alternative Abläufe und Ausnahmen enthalten.

5. Validierung der Anwendungsfälle:
Stellen Sie sicher, dass die Anwendungsfälle die Anforderungen der Stakeholder und Benutzer korrekt widerspiegeln. Überprüfen Sie die Anwendungsfälle mit den Stakeholdern und Benutzern, um Feedback zu erhalten und eventuelle Unklarheiten oder Lücken zu klären.

6. Anwendungsfalldiagramme erstellen:
Erstellen Sie Anwendungsfalldiagramme, um die Beziehungen zwischen den Akteuren und Anwendungsfällen visuell darzustellen. Diese Diagramme helfen, das Verständnis der Anforderungen und Interaktionen zu fördern und sind Teil der Unified Modeling Language (UML).

7. Priorisierung der Anwendungsfälle:
Priorisieren Sie die Anwendungsfälle, um festzulegen, welche Funktionen zuerst entwickelt oder implementiert werden sollen. Dies kann auf der Grundlage von Faktoren wie Geschäftswert, technischer Komplexität oder Abhängigkeiten zwischen den Anwendungsfällen erfolgen.

8. Anforderungsverfolgung und -management:
Verwenden Sie geeignete Werkzeuge und Prozesse, um die Anwendungsfälle und ihre Umsetzung im Laufe des Projekts zu verfolgen und zu verwalten. Dies stellt sicher, dass alle Anforderungen erfüllt werden und Änderungen angemessen verwaltet werden.


### Generelle Vorgehensmodelle
### Wasserfallmodell
![Wasserfallmodell](images/wasserfallmodell.png)


### V-Modell
![V-Modell](images/v-modell.jpg)


### Prototyp-Modell
![Prototyp-Modell](images/prototyp-modell.jpg)


## Werkzeuge
Es gibt verschiedene Werkzeuge, die bei der Anforderungsanalyse mit Anwendungsfällen eingesetzt werden können, um den Prozess der Erstellung, Verwaltung und Kommunikation von Anwendungsfällen zu erleichtern. Hier sind einige gängige Werkzeuge:

- UML-Modellierungswerkzeuge:
Unified Modeling Language (UML) ist eine Standardnotation zur Modellierung von Softwaresystemen. UML-Modellierungswerkzeuge wie Enterprise Architect, Visual Paradigm, Lucidchart oder StarUML ermöglichen es Ihnen, Anwendungsfalldiagramme und andere UML-Diagramme zu erstellen und zu verwalten, um die Anforderungen und Interaktionen eines Systems besser zu visualisieren.

- Anforderungsmanagement-Software:
Werkzeuge wie IBM Rational DOORS, Jama Connect oder Helix ALM können zur Verwaltung und Dokumentation von Anwendungsfällen verwendet werden. Diese Werkzeuge unterstützen die Verwaltung von Anforderungen, Priorisierung, Zusammenarbeit, Verfolgung von Änderungen und Berichterstattung.

- Projektmanagement- und Kollaborationswerkzeuge:
Projektmanagement- und Kollaborationswerkzeuge wie Jira, Trello oder Azure DevOps können verwendet werden, um Anwendungsfälle und deren Umsetzung im Laufe des Projekts zu verfolgen. Sie unterstützen die Zusammenarbeit im Team, indem sie die Kommunikation, das Zuweisen von Aufgaben und das Verfolgen des Projektfortschritts erleichtern.

- Textverarbeitungs- und Tabellenkalkulationsprogramme:
Microsoft Word, Google Docs oder Excel können verwendet werden, um Anwendungsfälle und ihre Spezifikationen zu dokumentieren. Sie sind zwar nicht so leistungsfähig wie spezialisierte Anforderungsmanagement-Software, bieten jedoch einfache Möglichkeiten zur Erstellung, Formatierung und Speicherung von Dokumenten.

- Diagramm- und Grafikwerkzeuge:
Diagramm- und Grafikwerkzeuge wie Microsoft Visio, draw.io oder Creately können verwendet werden, um Anwendungsfalldiagramme und andere visuelle Darstellungen von Anwendungsfällen und ihren Beziehungen zu erstellen.

- Prototyping-Tools:
Werkzeuge wie Balsamiq, Sketch, Figma oder InVision können verwendet werden, um einfache Prototypen oder Wireframes des Systems zu erstellen. Diese können hilfreich sein, um das Verständnis der Anwendungsfälle zu vertiefen und Feedback von Benutzern und Stakeholdern zu erhalten.

## UI Mockups
UI (User Interface) Mockups spielen eine unterstützende Rolle bei der Anforderungsanalyse mit Anwendungsfällen. Sie sind visuelle Darstellungen des User Interfaces eines Systems und helfen, die Anforderungen und Benutzerinteraktionen besser zu veranschaulichen. Hier sind einige Gründe, warum UI Mockups im Zusammenhang mit der Anforderungsanalyse mit Anwendungsfällen nützlich sein können:

- Verständnis vertiefen:
UI Mockups helfen, die Anwendungsfälle und ihre Interaktionen mit dem System zu verdeutlichen. Sie bieten ein konkretes Bild davon, wie die Benutzer das System verwenden und wie die Anwendungsfälle in der Benutzeroberfläche repräsentiert werden.

- Kommunikation verbessern:
Mockups dienen als gemeinsame Referenz für Teammitglieder, Stakeholder und Kunden. Sie helfen, die Kommunikation und das gemeinsame Verständnis der Anforderungen zu fördern, indem sie ein visuelles Hilfsmittel bieten, das leichter zu verstehen ist als reiner Text.

- Benutzerfeedback einholen:
UI Mockups können verwendet werden, um frühzeitig Feedback von Benutzern und Stakeholdern zu erhalten. Dadurch können mögliche Probleme oder Verbesserungsmöglichkeiten in Bezug auf Benutzerfreundlichkeit, Design und Funktionalität identifiziert werden, bevor die Entwicklung beginnt.

- Anforderungen validieren:
Durch die Visualisierung der Anwendungsfälle in UI Mockups kann das Team überprüfen, ob die Anforderungen korrekt verstanden und umgesetzt wurden. Dies hilft, Unklarheiten und Lücken in der Anforderungsanalyse zu identifizieren und zu beheben.

- Zusammenarbeit fördern:
UI Mockups können zur Diskussion und Zusammenarbeit innerhalb des Teams beitragen, indem sie eine gemeinsame Grundlage für Ideen und Entscheidungen bieten.

Obwohl UI Mockups keine direkte Rolle in der Anforderungsanalyse mit Anwendungsfällen spielen, tragen sie dazu bei, die Anwendungsfälle und Anforderungen besser zu vermitteln und das Verständnis der Benutzerinteraktionen zu verbessern. Sie sind eine wertvolle Ergänzung, die den Analyseprozess unterstützt und die Qualität des entwickelten Systems verbessern kann.

## Dokumentation
Dokumentiere die wesentlichen Aspekte sowie deine persönlichen Lernergebnisse.

Bei der Anforderungsanalyse mit Anwendungsfällen ist es wichtig, die Anwendungsfälle und ihre zugehörigen Informationen klar und strukturiert zu dokumentieren. Die Dokumentation sollte alle relevanten Informationen enthalten, um ein gemeinsames Verständnis der funktionalen Anforderungen zu gewährleisten. Hier sind einige Schritte zur Dokumentation von Anwendungsfällen:

- Anwendungsfallspezifikation erstellen:
Für jeden identifizierten Anwendungsfall sollte eine Anwendungsfallspezifikation erstellt werden.
-   Name des Anwendungsfalls
-   Kurze Beschreibung oder Ziel des Anwendungsfalls
-   Beteiligte Akteure (Benutzer, Systeme oder Organisationen, die mit dem System interagieren)
-   Vorbedingungen (Bedingungen, die vor der Ausführung des Anwendungsfalls erfüllt sein müssen)
-   Nachbedingungen (Zustand des Systems nach der Ausführung des Anwendungsfalls)
-   Normaler Ablauf (Schritte, die im normalen Verlauf der Interaktion stattfinden)
-   Alternative Abläufe (alternative Schritte oder Verzweigungen, die auftreten können)
-   Ausnahmen oder Fehlerbedingungen (Szenarien, in denen der Anwendungsfall fehlschlägt oder abgebrochen wird)

- Anwendungsfalldiagramme erstellen:
Anwendungsfalldiagramme sind visuelle Darstellungen der Anwendungsfälle und ihrer Beziehungen zu den beteiligten Akteuren. Erstellen Sie Anwendungsfalldiagramme, um die Interaktionen und Beziehungen zwischen den Anwendungsfällen und den Akteuren zu verdeutlichen. Verwenden Sie UML-Modellierungswerkzeuge wie Enterprise Architect, Visual Paradigm, Lucidchart oder StarUML, um die Diagramme zu erstellen und zu verwalten.

- Dokumentation organisieren:
Organisieren Sie die Anwendungsfallspezifikationen und Diagramme in einer strukturierten und leicht zugänglichen Weise. Dies kann in Form von Dokumenten, Wikis oder durch den Einsatz von Anforderungsmanagement-Software erfolgen. Stellen Sie sicher, dass alle Teammitglieder Zugang zu den Dokumenten haben und Änderungen verfolgt werden können.

- Prototypen oder Wireframes erstellen (optional):
Erstellen Sie Prototypen oder Wireframes des Systems, um ein besseres Verständnis der Anwendungsfälle zu erhalten und das Design und die Benutzererfahrung zu veranschaulichen. Dies kann mit Hilfe von Prototyping-Tools wie Balsamiq, Sketch, Figma oder InVision erfolgen. Fügen Sie diese Visualisierungen in Ihre Dokumentation ein, um sie für die Teammitglieder und Stakeholder verfügbar zu machen.

- Überprüfung und Validierung:
Laden Sie die Stakeholder und Teammitglieder ein, die Anwendungsfalldokumentation zu überprüfen und Feedback zu geben. Dies stellt sicher, dass alle Anforderungen korrekt erfasst wurden und mögliche Unklarheiten oder Lücken geklärt werden.


# Anforderungsanalyse mit User Stories und Epics
Arbeite dich in die Grundprinzipien der Anforderungsanalyse mit User-Stories und Epics ein.

## Grundlagen
Anforderungsanalyse ist ein wichtiger Prozess in der Softwareentwicklung, bei dem die Bedürfnisse und Erwartungen der Benutzer ermittelt und dokumentiert werden. User Stories und Epics sind zwei gängige Werkzeuge, die in agilen Entwicklungsframeworks wie Scrum verwendet werden, um Anforderungen zu erfassen und zu organisieren.

User Stories:
User Stories sind kurze, einfache Beschreibungen einer Funktion aus der Perspektive eines Endbenutzers. Sie bestehen aus drei Hauptelementen:

1. Rolle (Wer): Beschreibt die Art des Benutzers oder die Rolle, die die Funktion nutzen wird.
2. Funktion (Was): Beschreibt die gewünschte Aktion oder das gewünschte Ergebnis.
3. Nutzen (Warum): Beschreibt den erwarteten Wert oder Vorteil, den der Benutzer durch die Funktion erhält.
User Stories folgen oft dieser Struktur: "Als [Rolle] möchte ich [Funktion], um [Nutzen] zu erzielen."

Ein Beispiel: "Als Online-Shop-Kunde möchte ich die Möglichkeit haben, meine Lieferadresse zu ändern, damit meine Bestellung an die richtige Adresse geliefert wird."

Epics:
Epics sind größere, komplexere Anforderungen, die in mehrere kleinere User Stories aufgeteilt werden können. Sie sind oft schwer zu schätzen und erfordern mehrere Iterationen, um vollständig umgesetzt zu werden. Epics helfen, das Projekt in überschaubare Teile zu zerlegen, die leichter zu verwalten und umzusetzen sind.

Ein Beispiel für ein Epic: "Implementierung eines Kundenbindungsprogramms für den Online-Shop."

In diesem Fall könnte das Epic in mehrere User Stories aufgeteilt werden, wie zum Beispiel:

"Als Kunde möchte ich Treuepunkte für jeden Einkauf sammeln, um später Rabatte zu erhalten."
"Als Kunde möchte ich meine gesammelten Treuepunkte einsehen können, um meinen Fortschritt zu verfolgen."
"Als Shop-Administrator möchte ich Kundenbindungsprogramm-Regeln erstellen und ändern können, um das Programm anpassen zu können."
Zusammengefasst helfen User Stories und Epics dabei, Anforderungen in leicht verständliche und umsetzbare Teile zu zerlegen. Sie ermöglichen es Entwicklern und Stakeholdern, den Fortschritt zu verfolgen und den Fokus auf die Bedürfnisse der Benutzer zu richten.


## Vorgehensweisen
Bei der Anforderungsanalyse mit User Stories und Epics gibt es mehrere Vorgehensweisen, um effektiv und effizient zu arbeiten.

1. Identifizierung der Stakeholder:
Identifizieren Sie zunächst alle relevanten Stakeholder, die an dem Projekt beteiligt sind oder von ihm betroffen sein könnten, wie z. B. Endbenutzer, Projektmanager, Entwickler und Kunden.

2. Sammeln von Anforderungen:
Arbeiten Sie eng mit den Stakeholdern zusammen, um Anforderungen zu ermitteln und zu dokumentieren. Verwenden Sie Techniken wie Interviews, Workshops, Fragebögen und Beobachtungen, um ein klares Verständnis der Bedürfnisse und Ziele der Benutzer zu gewinnen.

3. Erstellung von User Stories:
Schreiben Sie User Stories, die die Anforderungen aus der Perspektive des Benutzers beschreiben. Achten Sie darauf, dass die User Stories die Rolle, die Funktion und den Nutzen enthalten, und dass sie klar und prägnant formuliert sind.

4. Identifizierung von Epics:
Suchen Sie nach größeren, komplexeren Anforderungen, die in mehrere User Stories aufgeteilt werden können, und erstellen Sie entsprechende Epics. Ein Epic sollte einen übergeordneten Zweck oder ein Ziel repräsentieren, das durch die zugehörigen User Stories erreicht werden soll.

5. Priorisierung:
Arbeiten Sie mit den Stakeholdern zusammen, um die User Stories und Epics nach ihrer Dringlichkeit und Wichtigkeit zu priorisieren. Sie können Techniken wie die MoSCoW-Methode (Must-have, Should-have, Could-have, Won't-have) oder den Business-Value-Ansatz verwenden, um eine Rangfolge festzulegen.

6. Planung und Schätzung:
Planen Sie die Umsetzung der User Stories und Epics in den entsprechenden Entwicklungszyklen (Sprints) und schätzen Sie die benötigte Zeit und Ressourcen. Sie können Schätztechniken wie Planning Poker oder T-Shirt-Größen verwenden, um die relativen Aufwände zu bestimmen.

7. Überprüfung und Anpassung:
Überprüfen Sie regelmäßig den Fortschritt und passen Sie Ihre Prioritäten und Pläne entsprechend an. Agile Methoden legen Wert auf kontinuierliche Verbesserung und Flexibilität, um auf Veränderungen in den Anforderungen oder dem Projektumfeld reagieren zu können.

8. Validierung und Abnahme:
Stellen Sie sicher, dass die umgesetzten User Stories und Epics die ursprünglichen Anforderungen erfüllen und von den Stakeholdern abgenommen werden. Dies gewährleistet, dass das Produkt die Bedürfnisse der Benutzer erfüllt und den gewünschten Wert liefert.

## Werkzeuge
Es gibt verschiedene Werkzeuge, die Ihnen bei der Arbeit mit User Stories und Epics helfen können. Einige dieser Werkzeuge sind speziell für die agile Softwareentwicklung konzipiert, während andere allgemeiner einsetzbar sind. Hier sind einige der gängigsten Werkzeuge:

- Jira:
Jira ist ein beliebtes Projektmanagement- und Bug-Tracking-Tool von Atlassian. Es unterstützt agile Methoden wie Scrum und Kanban und bietet Funktionen zum Erstellen, Organisieren und Priorisieren von User Stories und Epics. Jira ermöglicht auch die Planung von Sprints, die Schätzung von Aufwänden und die Überwachung des Fortschritts.

- Trello:
Trello ist ein visuelles Kollaborations- und Projektmanagement-Tool, das auf dem Kanban-Prinzip basiert. Sie können Trello-Boards, Listen und Karten verwenden, um User Stories und Epics zu erstellen, zu organisieren und zu verwalten. Trello eignet sich besonders für kleinere Teams und weniger komplexe Projekte.

- Azure DevOps (früher VSTS):
Azure DevOps ist eine Suite von DevOps-Tools von Microsoft, die eine Vielzahl von Funktionen wie Quellcodeverwaltung, Build-Automatisierung, Deployment und Projektmanagement bietet. Es unterstützt agile Methoden und ermöglicht die Verwaltung von User Stories, Epics, Sprints und Backlogs.

- GitLab:
GitLab ist eine webbasierte DevOps-Plattform, die Funktionen wie Versionskontrolle, Continuous Integration und Deployment, sowie Projektmanagement bietet. GitLab bietet ein Issue-Tracking-System, mit dem Sie User Stories und Epics erstellen, organisieren und verwalten können.

- Pivotal Tracker:
Pivotal Tracker ist ein agiles Projektmanagement-Tool, das speziell für Softwareentwicklungsteams entwickelt wurde. Es bietet Funktionen zum Erstellen und Verwalten von User Stories, Epics und Iterationen. Pivotal Tracker ermöglicht die Schätzung von Aufwänden, die Planung von Releases und die Visualisierung des Projektfortschritts.

- Taiga:
Taiga ist ein Open-Source-Projektmanagement-Tool für agile Teams. Es unterstützt Scrum und Kanban und

## Dokumentation
Bei der Anforderungsanalyse mit User Stories und Epics ist es wichtig, die Informationen klar und übersichtlich zu dokumentieren, um die Zusammenarbeit im Team zu erleichtern und Missverständnisse zu vermeiden. Hier sind einige Tipps zur Dokumentation von User Stories und Epics:

- User Stories:
User Stories sind kurze, einfache Beschreibungen einer Funktion oder eines Features aus der Perspektive des Benutzers.
- Epics:
Ein Epic ist eine größere, abstraktere Anforderung, die aus mehreren User Stories besteht. Epics sollten auch klar und verständlich dokumentiert werden, um das Gesamtziel und den Zusammenhang zwischen den zugehörigen User Stories zu verdeutlichen.
- Akzeptanzkriterien:
Akzeptanzkriterien sind spezifische Bedingungen, die erfüllt sein müssen, damit eine User Story als abgeschlossen betrachtet wird. Akzeptanzkriterien sollten klar und präzise formuliert werden, um sicherzustellen, dass alle Teammitglieder wissen, wann eine User Story abgeschlossen ist.

- Dokumentationstools:
Nutzen Sie Projektmanagement- und Kollaborationswerkzeuge wie Jira, Trello oder Azure DevOps, um User Stories und Epics zu dokumentieren und zu verwalten. Diese Werkzeuge ermöglichen es Ihnen, Anforderungen zu organisieren, Prioritäten festzulegen und den Fortschritt des Projekts zu verfolgen.

- Visuelle Darstellungen:
Verwenden Sie visuelle Darstellungen wie Story Maps, um den Zusammenhang zwischen User Stories und Epics zu verdeutlichen und die Reihenfolge der Umsetzung zu planen.

- Kommunikation und Zusammenarbeit:
Fördern Sie offene Kommunikation und Zusammenarbeit im Team, um sicherzustellen, dass alle Mitglieder über die Anforderungen und deren Bedeutung im Klaren sind. Halten Sie regelmäßige Meetings und Diskussionen ab, um gemeinsam an User Stories und Epics zu arbeiten und Probleme oder Unklarheiten zu klären.

# Wichtige UML-Diagrammarten

## Klassendiagramm

### Einsatzzweck

### Wesentliche Notationsformen

### Exemplarische Anwendung Beispiel



## Sequenzdiagramm

### Einsatzzweck

### Wesentliche Notationsformen

### Exemplarische Anwendung Beispiel



## Zustandsdiagramm

### Einsatzzweck

### Wesentliche Notationsformen

### Exemplarische Anwendung Beispiel



# Textuelles Diagramm Design-Tool

## PlantUML

## Mermaid



# USE-CASE-DIAGRAMM 1
Interpretieren Sie schriftlich das folgende Use-Case-Diagramm:


# USE-CASE-DIAGRAMM 2
Interpretieren Sie schriftlich das folgende Use-Case-Diagramm:


# USE-CASE-DIAGRAMM 3
Entwerfen Sie ein Anwendungsfalldiagramm zu der folgenden Beschreibung:
Es soll ein Anwendungssystem zur Unterstützung der Geschäftsprozesse in einem Krankenhaus
entwickelt werden. Das System soll folgende Aufgaben erledigen:
- Herr Müller und Herr Maier seien in der Verwaltung angestellt.
- Herr Müller soll Mitarbeiter einstellen und entlassen können. Sowohl Herr Müller als auch Herr Maier
kann Patienten aufnehmen und entlassen.
- Sowohl bei der Einstellung von Mitarbeitern, als auch bei der Aufnahme von Patienten müssen Name
und Adresse erfasst werden. Um redundante Anwendungsfall-Beschreibungen zu verhindern wird
diese Tätigkeit in einen gesonderten Anwendungsfall ausgelagert.
- Falls der einzustellende Mitarbeiter bzw. der aufzunehmende Patient seinen Wohnsitz am Ort des
Krankenhauses hat, wird geprüft, ob die angegebene Adresse am Wohnort existiert. Lagern Sie auch
diesen Anwendungsfall aus.

# USE-CASE-DETAILBESCHREIBUNGEN
Definieren Sie die Use-Case-Details (level, complexity, status, pre-conditions, post-conditions and assumptions,
event flow etc.) für einige Use-Cases der vorhergehenden Use-Case-Übungen. Verwenden Sie dazu eine der
bereitgestellten Schablonen bzw. ein entsprechendes Software-Tool.
Schablone A