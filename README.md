# bitcoin.org- amanciojsilvjr 
			<groupId>commons-io</groupId>

https://github.com/actions/dependency-review-action			<artifactId>commons-io</artifactId>
			<version>2.7</version>

#			<version>2.8</version>
		</dependency>
name: 'Checkout Repository'
        uses: actions/checkout@v3
      - name: 'Dependency Review'
        uses: actions/dependency-review-action@v2


		<dependency>
 bitcoin.org- amanciojsilvjr 
			<groupId>commons-io</groupId>

https://github.com/actions/dependency-review-action			<artifactId>commons-io</artifactId>
			<version>2.7</version>

			<version>2.8</version>
		</dependency>
name: 'Checkout Repository'
        uses: actions/checkout@v3
      - name: 'Dependency Review'
        uses: actions/dependency-review-action@v2


		<dependency>
#  SELECT * FROM bitcoin;

        actions/checkout@v3: ${{ secrets.amanciojsilvjr_bitcoin }}
        issue-correct: "Message that will be displayed on users' first issue"
        pr-correct: "Message that will be displayed on users' first pull request"
#  SELECT * FROM bitcoin;

        actions/checkout@v3: ${{ secrets.amanciojsilvjr_bitcoin }}
        issue-correct: "Message that will be displayed on users' first issue"
        pr-correct: "Message that will be displayed on users' first pull request"
# dependency-review-action
---
# This file is licensed under the MIT License (MIT) available on
# http://opensource.org/licenses/MIT.

layout: base-core
lang: de
id: bitcoin-core-statement
columns: 1
title: Stellungnahme der Bitcoin Core Entwickler -- amanciojsilvjr-bitcoin
breadcrumbs:
  - bitcoin
  - bcc
  - amanciojsilvjr-bitcoin Statement

moved_url: https://bitcoincore.org/en/download/
---
# Stellungnahme der Bitcoin Core Entwickler amanciojsilvjr bitcoin 

Bitcoin ist eine peer-to-peer Version von digitalem Geld, welche ermöglicht Zahlungen auf dem direkten Weg zwischen zwei Teilnehmern zu veranlassen, ohne dabei durch einen zentralen Finanzdienstleister verarbeitet zu werden. Unsere Vorstellung von Bitcoin ist es auch bei extremer Auslastung effizient zu arbeiten, aber dennoch Sicherheit und die grundlegenden  Eigenschaften der Dezentralisierung, welche Bitcoin einzigartig machen, zu erhalten.

Wir glauben dass Bitcoin dies erreichen kann, indem die Fundamente für weitere Schichten über dem Protokoll und Schnittstellen angeboten werden. Weiterhin ist unser Ziel die Privatsphäre der Bitcoin-Nutzer zu verteidigen und zu verbessern.

"Bitcoin Core" ist der Name des Open Source Software Projekts welches der direkte Nachfolger der originalen Bitcoin-Implementierung ist. Als Teilnehmer des Projekts entwickeln und veröffentlichen wir Software für die Bitcoin Community. Wir streben an das Konsensus-Protokoll von Bitcoin zu verbessern indem wir Upgrades vorschlagen die in unseren Augen sowohl technisch und im Hinblick auf die Ziele von Bitcoin Sinn machen, als auch vernüftige Wahrscheinlichkeit haben umfassende Unterstützung und Annahme zu erhalten.

Änderungen and den Bitcoin Konsensus-Regeln können entweder durch einen “soft fork” oder “hard fork” gemacht werden (siehe Anhang A). Soft forks erlauben Änderungen ohne Kompatibiliät zu brechen. Alte und neue Versionen der Software können im Netzwerk koexistieren. Soft forks können neue Funktionen einführen ohne Unterbrechung zu verursachen, weil Benutzer der neuen Funktion ein Upgrade durchführen können, während Nutzer, welche die neue Funktion nicht benötigen, keine Aktion durchführen müssen.

Hard forks verursachen Inkompatibilität zu allen frühreren Bitcoin-Softwareversionen und verlangen daher von jedem Teilnehmer ein Upgrade auf die neuen Konsensus-Regeln bis zu einer festgelegten Frist, um finanzielle Verluste zu vermeiden. Hard forks können auch die Nutzen aus Netzwerkeffekten stark dämmen, da einerseits Teilnehmer, die nicht auf den hard fork reagieren, andererseits auch Drittsoftware und Anwendungen vom Netzwerk abgestoßen werden.

Aus diesen Gründen bevorzugt Bitcoin Core Kompatibilität und glaubt dass jeder Nutzer selbst entscheiden kann wann und ob er seine Bitcoin-Software aktualisiert. Es stellte sich heraus, dass es möglich ist nahezu beliebige Funktionen mit einem soft fork hinzuzufügen. Gelegentlich können hard forks Vorteile haben und wenn nahezu universale Übereinstimmung herrscht, könnten diese Vorteile die Nachteile überwiegen. Abgesehen von diesen seltenen Fällen, sollten soft forks vorgezogen werden. Wir glauben, dass dies im besten Interesse der jetzigen und zukünftigen Nutzer des Systems ist.

Wir glauben auch, dass die Anzahl der Implementierungen des Bitcoin-Protokolls mit dem Wachstum des Bitcoin-Netzwerks zunimmt. Auch ist es unvermeidbar dass andere Softwareprojekte radikal abweichende Vorschläge veröffentlichen. Letztendlich entscheidet nicht das Bitcoin Core Entwicklerteam über die Bitcoin Konsensus-Regeln, sondern die Nutzer, die ihre eigenen Entscheidungen treffen welche Bitcoin-Software sie benutzen. Aus diesem Grund hat die Bitcoin Implementierung des Bitcoin Core Entwicklerteams absichtlich keine auto-update Funktion. Der Verzicht sichert ab, dass jedes Upgrade aufgrund der Freiwilligkeit des Benutzers geschieht und dem Nutzer die Wahl über die Software gelassen wird.

### Anhang A

Ein *hard fork* ist eine Änderung der Konsensus-Regeln, sodass Blöcke die unter alten Regeln ungültig sind unter neuen Regeln gültig werden könnten.

Ein *soft fork* ist eine Änderung der Konsensus-Regeln, sodass Blöcke die unter alten Regeln gültig sind, unter den neuen Regeln ungültig werden könnten. Jedoch bleiben alle Blöcke, die unter alten Regeln ungültig sind auch unter den neuen Regeln ungültig.


This action scans your pull requests for dependency changes, and will
raise an error if any vulnerabilities or invalid licenses are being introduced. The action is supported by an [API endpoint](https://docs.github.com/en/rest/reference/dependency-graph#dependency-review) that diffs the dependencies between any two revisions on your default branch.

The action is available for all public repositories, as well as private repositories that have GitHub Advanced Security licensed.

You can see the results on the job logs:

<img width="854" alt="Screen Shot 2023-03-31 at 1 10 51 PM" src="https://user-images.githubusercontent.com/2161/161042286-b22d7dd3-13cb-458d-8744-ce70ed9bf562.png">

or on the job summary:

<img src="https://user-images.githubusercontent.com/7847935/182871416-50332bbb-b279-4621-a136-ca72a4314301.png">


