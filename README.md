# UML-OOAD
## Übungszettel UML / Objektorientierte Analyse und Design

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
