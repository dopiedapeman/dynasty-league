<script>
    import { dues } from '$lib/utils/helper';
    let one;
    let two, twoOne, twoTwo, twoThree;
    let three, threeOne, threeTwo, threeThree, threeFour, threeFive;
    let four, fourOne, fourTwo, fourThree;
    let five, fiveOne, fiveTwo, fiveThree;
    let six, sixOne, sixTwo, sixThree;
    let seven, sevenOne, sevenTwo, sevenThree, sevenFour;
    let eight, eightOne, eightTwo, eightThree, eightFour;
    let nine, nineOne, nineTwo, nineThree, nineFour, nineFive;
    let ten;
    let eleven;
    
    const goToSection = (section) => {
        const top = section.getBoundingClientRect().top + window.pageYOffset;
        window.scrollTo({left: 0, top, behavior: 'smooth'});
    }
</script>

<style>
    .constitution {
        position: relative;
        z-index: 1;
        width: 92%;
        max-width: 800px;
        margin: 8em auto 10em;
    }

    h1 {
        font-size: 2em;
        line-height: 1.2em;
        text-align: center;
        margin: 2em 0 1.5em;
    }

    h2 {
        font-size: 1.5em;
        line-height: 1.2em;
    }

    h3 {
        text-decoration: underline;
        font-size: 1.3em;
        line-height: 1.2em;
    }

    h4 {
        text-decoration: underline;
        margin-left: 2em;
        font-size: 1.2em;
        line-height: 1.2em;
    }

    h5 {
        margin-left: 6em;
        font-size: 0.8em;
        line-height: 1.1em;
    }

    .subBlock {
        margin-left: 2.4em;
    }

    .sectionHeading {
        margin: 4em 0 1.5em;
    }

    .subSectionHeading {
        margin: 1.5em 0 1.5em;
    }

    .underscore {
        text-decoration: underline;
    }

    .right {
        text-align: right;
    }

    .positionMaximums td {
        min-width: 3em;
    }

    .noUnderscore {
        text-decoration: none;
    }

    .clickable {
        cursor: pointer;
    }

    .clickable:hover {
        color: #00316b;
    }

    p {
        color: #777;
    }
</style>

<div class="constitution">
   <h1 class="noUnderscore">JEDEN VERDAMMTEN SONNTAG LEAGUE CONSTITUTION</h1>
    
    <h2 class="noUnderscore">INHALTSVERZEICHNIS</h2>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(one)}>Artikel I: EINLEITUNG</h3>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(two)}>Artikel II: LEAGUE COMMISSIONER</h3>
	
		<h4 class="noUnderscore clickable" on:click={() => goToSection(twoOne)}>Das Amt des Commissioners</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(twoTwo)}>Einschränkungen</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(twoThree)}>Vorgeschriebene Strafen</h4>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(three)}>Artikel III: CLUBS UND MANAGER</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(threeOne)}>Aktuelle Manager</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(threeTwo)}>Abstimmungen in der Offseason</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(threeThree)}>Abstimmung in der Regular Saison</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(threeFour)}>Regularien der Abstimmungen</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(threeFive)}>Austritt von Managern</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(four)}>Artikel IV: LEAGUE SETTINGS</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fourOne)}>Allgemeine Einstellungen der Liga</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fourTwo)}>Siege und Tiebreaker</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fourThree)}>Trades und Waiver-Picks</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(five)}>Artikel V: MAINZER DYNASTY LEAGUE ROOKIE DRAFT</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fiveOne)}>Ankündigung</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fiveTwo)}>Draft Order Determination</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fiveThree)}>Regeln des Drafts</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(six)}>Artikel VI: WAIVER UND ROSTER MANAGEMENT</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixOne)}>Waiver Wire</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixTwo)}>Verantwortlichkeiten der Manager</h4>
    
     <h3 class="noUnderscore clickable" on:click={() => goToSection(seven)}>Artikel VII: TRADES</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sevenOne)}>Regeln</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sevenTwo)}>Besondere und Verbotene Trades</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sevenThree)}>Trade Deadline</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sevenFour)}>FAAB-Einsatz</h4>
    
     <h3 class="noUnderscore clickable" on:click={() => goToSection(eight)}>Artikel VIII: PLAYOFFS</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(eightOne)}>Zeit</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(eightTwo)}>Teilnahme</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(eightThree)}>Tiebreaker</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(eightFour)}>Bestimmungen</h4>
    
     <h3 class="noUnderscore clickable" on:click={() => goToSection(nine)}>Artikel IX: REGELVERSTÖßE</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(nineOne)}>Art der Straftaten</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(nineTwo)}>Einleitung eines Ordnungswidrigkeitenverfahrens</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(nineThree)}>Regelverstöße</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(nineFour)}>Strafen</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(nineFive)}>Schiedsrichter</h4>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(ten)}>Anhang "A": FINANZEN</h3>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(eleven)}>Anhang "B": VERSIONSHISTORIE</h3>
    
    <hr />
    
     <h2 class="sectionHeading" bind:this={one}>Artikel 1: EINLEITUNG</h2>
     <p>Diese Constitution ist eine Vereinbarung zwischen den Managern der Dynasty-Liga. Von diesen Managern akzeptiert jeder die Regeln und Pflichten, die in dieser Vereinbarung festgesetzt wurden und verpflichtet sich, diese zu befolgen. Die Constitution bleibt auf unbestimmte Zeit in Kraft.</p>
    

     <h2 class="sectionHeading" bind:this={two}>Artikel II: LEAGUE COMMISSIONER</h2>
     
	 <h3 bind:this={twoOne}>Das Amt des Commissioners</h3>
		<ol>
			<li>Das Amt des Commissioners ist hiermit eingerichtet.</li>
			<li>Zu den Aufgaben des Commissioners gehören:</li>
				<ol type="a" id="2.2">
					<li>als Verwaltungschef und Streitschlichter der Liga zu fungieren.</li>
					<li>Fragen der Mitglieder zu beantworten und auftretende Probleme zu lösen.</li>
					<li>auf Beschwerde oder auf eigene Initiative jede Handlung oder Transaktion zu untersuchen, die eventuell nicht mit den Regeln dieser Constitution vereinbar ist. Dafür darf er Manager dazu bewegen, zu einem Problem Stellung zu nehmen und anschließend eventuelle vorgesehenen Sanktionen zu verhängen.</li>
					<li>welche Präventiv- oder Strafmaßnahmen unter den jeweiligen Umständen für die Handlung oder Transaktion angemessen sind und gegebenenfalls Maßnahmen gegen Manager oder andere Personen zu ergreifen.</li>
					<li>eine Person zu ernennen, die dem Amt des Commissioners offiziell beigeordnet ist, soweit dies erforderlich ist.</li>
					<li id="2.2f">Entscheidungen in Bezug auf Regelauslegungen, Verwaltung, Trades oder Disziplinarmaßnahmen treffen, soweit dies erforderlich sein kann.</li>
					<li>alle Änderungen dieser Verfassung in <a href="#anhangb">Anhang B "Änderungshistorie"</a> festzuhalten.</li>
				</ol>
			<li>Amtszeitbeschränkungen und Wahlen</li>			
				<ol type="a">
					<li>Der Commissioner übt sein Amt ohne Mindestdauer aus. Die Manager der Liga haben in jeder Offseason die Möglichkeit, über einen neuen Commissioner abzustimmen.</li>
					<li>Die Wahl eines Commissioners erfolgt mit einfacher Mehrheit. Jeder Manager hat eine (1) Stimme. Bei Stimmengleichheit findet mindestens einmal wöchentlich eine weitere Wahl statt, bis ein Commissioner gewählt ist.</li>
					<li>Der Commissioner kann jederzeit (auch in der Season) mit einer Zweidrittel-Mehrheit abgewählt werden. Gleichzeitig muss ein neuer Commissioner mit absoluter Mehrheit gewählt werden. Kommt diese Mehrheit nicht zustande, bleibt der Commissioner bis auf Weiteres im Amt.</li>
					<li>Der Commissioner ist zu jeder Zeit gleichgestellt mit jedem anderen Manager der Liga. Er hat sich an alle Regeln zu halten, unabhängig der in <a href="#2.2">Artikel II, Abschnitt 2</a> beschriebenen Sonderrechte.</li>
				</ol>
			<li>Commissioner und weitere Offizielle</li>
				<p>Folgende Aufgaben sind unter den Managern verteilt. Alle Positionen können über einen League-Vote verändert werden, wie in <a href="#2.2">Artikel II, Abschnitt 3</a> festgelegt. </p>
					<ol type="a">
						<li>Marcus Kizina (Commissioner)</li>
						<li>Christian Wiedenhöft (Commissioner)</li>
						<li>Sebastian Böckel (League-Treasurer)</li>
					</ol>
				
		</ol>

	<h3 bind:this={twoTwo}>Einschränkungen</h3>
		<ol start="4">
			<li>Ungeachtet der Bestimmungen dieses Abschnitts darf der Commissioner keine Maßnahmen ergreifen und keine Änderung dieser Constitution vornehmen, die eine Abstimmung der Manager erfordern, wie in <a href="#3.2">Artikel III, Abschnitt 2</a> dargelegt.</li>
			<li>Jede ergriffene Maßnahme des Commissioners kann nach folgendem Verfahren wieder aufgehoben werden:</li>			
				<ol type="a">
					<li>Manager, die von der Entscheidung betroffen sind, sind nicht berechtigt, an einem Vote zur Aufhebung der Commissioner-Entscheidung teilzunehmen.</li>
					<li id="2.5b">Die Entscheidung kann neu überprüft werden, wenn mindestens die Hälfte der Manager (ausgenommen die beteiligten Manager) gegen die Entscheidung des Commissioners stimmt. Damit kann der Fall neu überprüft oder neu abgestimmt werden. <u>Dieser Antrag auf Abstimmung muss innerhalb einer Woche nach der Entscheidung in den Message Boards gestellt werden.</u></li>
					<li>Der Commissioner und alle betroffenen Parteien können bei den Managern der Liga nach Belieben zur Unterstützung einer Abstimmung werben.</li>
					<li>Die Entscheidung des Commissioners kann bei der Abstimmung nur mit einer Zweidrittel-Mehrheit der wahlberechtigten Manager aufgehoben werden.</li>
					<li>Wenn eine solche Mehrheit nicht erreicht wird, bleibt die Entscheidung des Commissioners bestehen. <u>Zur Klarstellung: Dies schließt weitere Aktionen des Commissioners gegen denselben Manager oder zum selben Thema nicht aus.</u></li>
				</ol>
		</ol>
		<p><u>Auslegungsbemerkung:</u> <i>Zum Beispiel kann der Commissioner gemäß <a href="#2.6c">Artikel II, Abschnitt 6, Absatz c)</a> entscheiden, dass Manager X aufgrund von illegalem Verhalten (z.B. illegal Lineup) einen Punktabzug für den Spieltag erhält. Diese Entscheidung wird an einem Dienstag um 12:35 Uhr in den Message Boards veröffentlicht. Sechs Manager der Liga (ohne die beteiligten Manager) (mehr als 50%) beantragt beim Commissioner eine erneute Überprüfung oder eine erneute Abstimmung gemäß <a href="#2.5b">Artikel II, Abschnitt 5, Absatz b)</a>, und zwar vor Ablauf der Frist um 12:35 Uhr am folgenden Dienstag.</i></p>
		<p><i>Der Commissioner weigert sich, dies noch einmal zu überdenken, und daher findet eine Abstimmung statt. Mehr als zwei Drittel der Manager stimmen dafür, dass die Entscheidung aufgehoben werden soll. Die Entscheidung des Commissioners ist damit offiziell aufgehoben. Der Commissioner entscheidet dann gemäß <a href="#2.6e">Artikel II, Abschnitt 6, Absatz e)</a>, dass der angeklagte Manager stattdessen mit einer Reduzierung der Waiver-Priority bestraft wird. Nur zwei Manager beantragen dazu eine Überprüfung dieser Entscheidung. Da dies weniger als 50% sind, um einen gültigen Antrag zu stellen, hat diese Entscheidung bestand und der angeklagte Manager wird darauf hin mit einer Reduzierung der Waiver-Priority bestraft.</i></p>

	<h3 bind:this={twoThree}>Vorgeschriebene Strafen</h3>
		<ol start="6">
			<li>Im Falle einer illegalen Aktion, können folgende Straf- oder Disziplinarmaßnahmen gegen die Manager erlassen werden:</li>
				<ol type="a">
					<li>Eine formelle Warnung;</li>
					<li>Eine Rückgängigmachung, Änderung oder Ablehnung eines Trades oder Waiver-Picks;</li>
					<li id="2.6c">Punktabzug für den Spieltag;</li>
					<li>Ein Verfall eines zuvor festgelegten Draft-Picks;</li>
					<li id="2.6e">Eine Reduzierung der Waiver Priority;</li>
					<li>Suspendierung oder Rauswurf eines Managers aus der Liga;</li>
					//<li>Abzug oder Verfall des FAAB-Budgets;</li>
					<li>Andere Maßnahmen, die der Commissioner für angemessen hält.</li>
				</ol>
			<li>Entscheidungen des Commissioners über Strafen für die Manager müssen formell in den Boards veröffentlicht werden.</li>
		</ol>
    
    
    <h2 class="sectionHeading" bind:this={three}>Artikel III: CLUBS UND MANAGER</h2>
    
    <h3 bind:this={threeOne}>Aktuelle Manager</h3>
    <ol>
         <li>Die Manager jedes Clubs werden wie folgt festgelegt:</li>
            <ol type="a">
                <li>Marcus – Allen's Amazing Airshow</li>
                <li>Chris – Fly me to the Mond</li>
                <li>Markus Hembes – TeamBayPackers</li>
                <li>Markus Flohr –  The Fail Mary</li>
                <li>Bö – boesen</li>
                <li>Ecki – Eckis Eleven</li>
                <li>David Mehrfeld – David247</li>
                <li>Teemu – ChopBlockPukki</li>
                <li>Nico – WTF Team</li>
                <li>Paul – Cheesehead32</li>
            </ol>
    </ol>
    
    <h3 id="3.2" bind:this={threeTwo}>Abstimmungen in der Offseason</h3>
    <ol start="2">
         <li>In jeder Offseason sind die Manager verpflichtet, an Abstimmungen teil zu nehmen, die Folgendes umfassen können:</li>
            <ol type="a">
                <li>die Wahl eines Commissioners;</li>
                //<li>Der Betrag des jährlichen FAABs eines Clubs;</li>
                <li id="3.2c">Änderung an dieser Constitution. Dies kann Folgendes umfassen:</li>
                    <ol type="i">
                        <li>Die Erweiterung der Liga;</li>
                        <li>Aktualisierung der Ligaeinstellungen und Regeln, wie in Artikel IV definiert; und</li>
                        <li>Aktualisierung der Draft-Regularien.</li>
                    </ol> 
            </ol>
    </ol>
    <p><a href="#3.2">Absatz a) bis c)</a> bedarf einer einfachen Mehrheit durch eine Abstimmung; <a href="#3.2c">Absatz c)</a> kann bei Bedarf und Bedeutung der Änderung mit einer Zwei-Drittel-Mehrheit festgesetzt werden. Nach Ablauf des Abstimmungsfensters werden alle Stimmen gezählt und eine Entscheidung vom Commissioner gemäß der ihm in <a href="#2.2f">Artikel II, Abschnitt 2, Absatz f)</a> erteilten Befugnis getroffen.</p>

    <h3 bind:this={threeThree}>Abstimmungen in der Regular Season</h3>
    <ol start="3">
         <li>Während der Regular Saison sind die Manager verpflichtet, an Abstimmungen teil zu nehmen, die Folgendes umfassen können:</li>
            <ol type="a">
                <li>Umfragen, die vom Commissioner zur Orientierung verlangt werden; und</li>
                <li>Überprüfung der Entscheidungen des Commissioners innerhalb der Regular Saison, wie in Artikel II, Abschnitt 5 dargelegt.</li>
            </ol>
		 <li>Diese Constitution kann, während der Regular Saison, nur durch einstimmigen Beschluss durch eine Abstimmung der Manager geändert werden. Die Abstimmungen bleibt für 3 Tage nach der Erstellung geöffnet. Nach Ablauf des Abstimmungsfensters werden alle Stimmen gezählt und eine Entscheidung vom Commissioner gemäß der ihm in Artikel II, Abschnitt 2 Absatz f) erteilten Befugnis getroffen.</li>
    </ol>
    
    <h3 bind:this={threeFour}>Regularien der Abstimmungen</h3>
    <ol start="5">
         <li>Es besteht eine Abstimmungspflicht in der Regular Season- und Offseason. Falls ein Manager nicht abstimmt, verfällt dessen Stimme unwiderruflich.</li>
         <li>Ausnahmen, bei der eine 100% Abstimmungsquote erreicht werden muss, sind: Abwahl-/ Wahl des Commissioners, Abstimmung in Bezug auf die Constitution, Ernennung/Ersetzen neuer Mitglieder, Ort und Uhrzeit des Drafts.</li>
    </ol>
    
    <h3 bind:this={threeFive}>Austritt von Managern</h3>
    <ol start="7">
         <li>Manager können sich jederzeit zwischen Beginn der Offseason und dem 15. August innerhalb dieser Offseason ohne Strafe aus der Liga zurückziehen. Ihre Clubs bleiben bestehen und ein neuer Manager kann durch die anderen Manager gefunden und ernannt werden.</li>
         <li>Jeder Manager, der zwischen dem 15. August und dem Beginn der folgenden Offseason in einem bestimmten Jahr aussteigt, verliert sein Buy-In-Guthaben.</li>
         <li>Neue Manager haben die Möglichkeit, den Club eines zurückgetretenen Managers umzubenennen.</li>
    </ol>
    
    
    <h2 class="sectionHeading" bind:this={four}>Artikel IV: LEAGUE SETTINGS</h2>
    
    <h3 bind:this={fourOne}>Allgemeine Einstellungen der Liga</h3>
    <ol>
         <li>Die Liga ist eine wöchentliche Full-PPR Head-to-Head-Liga, die auf Sleeper gehosted wird.</li>
		 <li>Es ist eine Dynasty-Liga. Der erste Draft fand zur Saison 2021 statt, jedes Jahr gibt es einen Rookie-Draft.</li>
		 <li>Es existieren zwei Divisions, die in der Saison 2021 festgelegt wurden und durch einen League-Vote veränderbar sind.</li>
         <li>Das Scheduling der Liga wird von den internen Systemen von Sleeper festgelegt und vom Commissioner überprüft.</li>
            <ol type="a">
                <li>Jeder spielt einmal gegen jeden anderen.</li>
                <li>Die weiteren Spiele werden mit Spielen in der eigenen Division ausgetragen.</li>
            </ol>
         <li>Die Scoring-Kategorien und zugehörigen Punkte für die Liga lauten wie folgt:</li>
             <ol type="a">
                 <li>Passing: Passing Yards (0,04) / TD Pass (4) / Interceptions Throw (-2) / 2pt Passing Conversions (2)</li>
                 <li>Rushing: Rushing Yards (0.1) / TD Rush (6) / 2pt Rushing Conversion (2)</li>
                 <li>Receiving: Receiving Yards (0.1) / Reception (1) / TD Reception (6) / 2pt Receiving Conversion (2) / Reception-Bonus - TE (0.25)</li>
                 <li>Sonstiges: Fumble (-0.5) / Fumble Lost (-1.5) / Fumble Recovery TD (6)</li>
                 <li>Kicking: PAT Made (1) / PAT Missed (-2) / Points per FG Yard (0.1) / FG Missed (0-29 yds) (-2) / FG Missed (30-39 yds) (-1.5) / FG Missed (40-49 yds) (-1)</li>
                 <li>Special Teams Player: Special Teams Player TD (6) / Special Teams Player Forced Fumble (1) / Special Teams Player Fumble Recovery (1)</li>
				 <li>IDP: IDP TD (6) / Sack (4) / Hit on QB (1) / Tackle For Loss (3) / Blocked Punt, PAT or FG (6) / Interception (6) / Int Return Yards (0.05) / Fumble Recovery (2) / Forced Fumble (4) / Safety (10) / Assisted Tackle (0.5) / Solo Tackle (1) / Pass Defended (3)</li>
             </ol> 
        <li>Der Roster setzt sich wie folgt zusammen:</li>
             <ol type="a">
                <li>2 Starting Quarterbacks (QB); Kein Maximum</li>
                <li>3 Starting Running Backs (RB); Kein Maximum</li>
                <li>4 Starting Wide Receivers (WR); Kein Maximum</li>
                <li>2 Starting Tight End (TE); Kein Maximum</li>
                <li>2 Starting Flex (RB/WR/TE);</li>
                <li>1 Starting Kicker (K); Kein Maximum</li>
				<li>1 Starting Defensive Line Man (DL); Kein Maximum</li>
				<li>1 Starting Linebacker (LB); Kein Maximum</li>
				<li>1 Starting Defensive Backs (DB); Kein Maximum</li>
                <li>23 Bench (BN);</li>
             </ol>
        <li>Während der Regular Saison besteht dieser Kader maximal aus 40 Spielern (zuzüglich fünf IR-Spots und sechs Taxi-Spots).</li>
		<li>Die Taxi-Spots sind nur für Spieler geöffnet, die maximal ihre zweite Saison spielen. Kommen diese Spieler in ihre dritte NFL-Saison, so müssen sie vom Taxi-Spot entfernt werden.</li>
    </ol>

    <h3 bind:this={fourTwo}>Siege und Tiebreaker</h3>
    <ol start="6">
         <li>Wöchentliche Head-to-Head-Matchups werden von dem Team mit der höheren Punktzahl für diese bestimmte Woche nach Abzug aller etwaigen Strafen gemäß Artikel IX, Abschnitt 8 gewonnen.</li>
         <li>Matchups, die mit einem Unentschieden enden, werden als Unentschieden mit Ausnahme von Spielen in den Playoffs und des Championship-Games wie in Artikel VIII, Abschnitt 6 gewertet.</li>
    </ol>
    
    <h3 bind:this={fourThree}>Trades und Waiver-Picks</h3>
    <ol start="8">
         <li>Jeder Club ist berechtigt, jede Saison eine unbegrenzte Anzahl von Trades und/oder Add/Drops auf der Waiver zu tätigen.</li>
	 <li>Zusätzlich zu Spielern können zukünftige Draft-Picks getraded werden. Dies ist auch während eines Live-Drafts möglich.</li>
     <li>Jeder Trade unterliegt keinem Überprüfungszeitraum. Manager haben jedoch die Möglichkeit durch eine Abstimmung den Trade als illegal oder unfair zu melden.</li>
    </ol>
    
     
    <h2 class="sectionHeading" bind:this={five}>Artikel V: MAINZER DYNASTY LEAGUE ROOKIE DRAFT</h2>
    
    <h3 bind:this={fiveOne}>Ankündigung</h3>
    <ol>
         <li>Das Datum und die Uhrzeit werden auf Sleeper, auf der Website und in WhatsApp veröffentlicht und jedem Eigentümer per E-Mail mitgeteilt.</li>
         <li>Das Startdatum jedes nachfolgenden Rookie Drafts wird vom Commissioner in Absprache mit den Managern spätestens zwei (2) Wochen vor Beginn der regulären NFL-Saison festgelegt, und soll spätestens einen (1) Tag vor dem Opening Kickoff und mit einer Frist zur Kenntnisnahme von mindestens sieben (7) Tagen für die Clubs durchgeführt werden.</li>
    </ol>
    
    <h3 bind:this={fiveTwo}>Draft Order Determination</h3>
    <ol start="3">
         <li>Die Draft Order wird durch die Vorjahresplatzierung festgelegt. Dabei erhält der Vorjahresletze den First Pick, der 9. den Second Pick und so weiter.</li>
    </ol>
    
    <h3 bind:this={fiveThree}>Regeln des Drafts</h3>
    <ol start="4">
         <li>Der Draft unterliegt dem automatisierten Prozess von Sleeper und ist ein Snake Draft aus dem Rookie Player Pool.</li>
		 <li>Jedoch kann der Draft auf anderen Plattformen oder im Offline-Format stadtfinden. Die Ergebnisse werden anschließend vom Commissioner in Sleeper eingetragen.</li>
		 <li>Es ist möglich, Draft Picks vor und während des Drafts zu traden.</li>
    </ol>

    <h2 class="sectionHeading" bind:this={six}>Artikel VI: WAIVER UND ROSTER MANAGEMENT</h2>
    
    <h3 bind:this={sixOne}>Waiver Wire</h3>
    <ol>
         <li>Spieler werden über die wöchentliche Waiver Wire erworben. Die Waiver-Wire-Reihenfolge wurde zu Beginn der 2021 Season ausgelost. Von da an wird ein Manager, der eine Spieler darüber erworben hat, an das Ende der Waiver-Wire verschoben.</li>
         <li>Es gibt kein Saison-Limit an Waiver-Picks.</li>
         <li>Jeder neue Free Agent bleibt 24 Stunden lang auf der Waiver Wire, um allen Teams die Möglichkeit zu geben, auf diesen zu bieten.</li>
    </ol>
    
    <h3 bind:this={sixTwo}>Verantwortlichkeiten der Manager</h3>
    <ol start="4">
         <li>Manager müssen ein komplettes (legal) Team aufstellen.</li>
         <li>>Manager dürfen verletzte Spieler oder IR-Spieler nicht zum Kick-Off in ihrer aktiven Aufstellung belassen. Kick-Off bedeutet, dass der verletzte oder IR-Spieler zum individuellen Spielbeginn nicht im aktiven Roster sein darf. Das gleiche gilt für das Verbleiben eines Spielers auf dem IR-Spot. <i>(Beispiel: Der Status eines Spielers wechselt auf Out. Das Team des Spielers spielt er am Sonntag um 22:30 Uhr. Zu Beginn des Spieles um 19:00 Uhr befindet sich dieser Spieler noch in der aktiven Aufstellung. Dies stellt so lange kein Problem dar, bis das Spiel um 22:30 angepfiffen wird. Erst bis dahin muss er aus der Aufstellung heraus genommen werden.)</i></li>
         <li>Verletzt sich ein Spieler vor einem Spätspiel, oder ist bis dahin der Status noch nicht geklärt, wird die Frist für die Manager zum wechseln des Spielers auf 23 Uhr des Spieltages festgelegt. Ändert sich nach dieser Uhrzeit der Status eines Spieler, so wird der Manager nicht für ein illegal Line-Up verantwortlich gemacht.</li>
         <li>Die Nichteinhaltung der in den Abschnitten 4,5 und 6 festgelegten Verantwortlichkeiten führt dazu, dass der Manager nach Ermessen des Commissioners gemäß Artikel II, Abschnitt 6 bestraft wird und gemäß Artikel II, Abschnitt 5 überprüfbar ist.</li>
         <li>Darüber hinaus, wenn ein Manager für einen Zeitraum von mehr als zwei Wochen inaktiv ist, stellt dies einen Regelbruch im Sinne von Artikel IX dar.</li>
    </ol>
    
    <h2 class="sectionHeading" bind:this={seven}>Artikel VII: TRADES</h2>
    
    <h3 bind:this={sevenOne}>Regeln</h3>
    <ol>
         <li>Jeder Manager kann jederzeit eine beliebige Anzahl von Trades mit einer beliebigen Anzahl anderer Manager durchführen, vorausgesetzt, dass die Trades nicht unfair oder illegal sind. Vorgeschlagene Trades werden keiner Überprüfung durch die Manager unterzogen und werden nach der Annahme direkt durchgeführt.</li>
         <li>Der Commissioner ist befugt, alle Transaktionen gemäß Artikel II Abschnitt 2 Absatz e) unter den folgenden Bedingungen zu bewerten:</li>
            <ol type="a">
                <li>der Commissioner kann ein Veto gegen Transaktionen einlegen oder sie für nichtig erklären, die gegen diese Constitution verstoßen oder die nach seinem Ermessen unfair oder illegal wären;</li>
				<li>Ebenso können alle Manager ein Veto gegen den Trade einlegen;</li>
                <li>alle derartigen Vetos müssen innerhalb von 24 Stunden nach dem Trade angekündigt werden;</li>
                <li>alle diese Vetos sind überprüfbare Entscheidungen gemäß Artikel II, Abschnitt 5; und</li>
                <li>der Commissioner muss diese Handlung mit allen Betroffenen abstimmen;</li>
            </ol>
    </ol>
    
    <h3 bind:this={sevenTwo}>Besondere und Verbotene Trades</h3>
    <ol start="3">
         <li>Draft-Picks sind übertragbar und dürfen Teil eines Trades sein.</li>
         <li>Mit Ausnahme der Roster-Anforderungen gibt es keine Einschränkungen in Bezug auf die Anzahl der Spieler, die Teil eines Trades sein können.</li>
    </ol>
    
    <h3 bind:this={sevenThree}>Trade Deadline</h3>
    <ol start="5">
         <li>Es wurde keine Trade-Deadline eingeführt.</li>
    </ol>

    <h3 bind:this={sevenFour}>FAAB-Einsatz</h3>
    <ol start="6">
         <li>Entfällt!</li>
    </ol>

    
    <h2 class="sectionHeading" bind:this={eight}>Artikel VIII: PLAYOFFS</h2> 
    
    <h3 bind:this={eightOne}>Zeit</h3>
    <ol>
         <li>Die Playoffs beginnen in Week 16 der Regular Season der NFL.</li>
         <li>Es gibt zwei (2) Playoff-Runden</li>
         <li>Jede Playoff-Runde dauert eine (1) Woche.</li>
    </ol>
    
    <h3 bind:this={eightTwo}>Teilnahme</h3>
    <ol start="4">
         <li>Die beiden Gewinner der jeweiligen Division erhalten automatisch einen Platz in jeweils einem Halbfinale.</li>
         <li>Die zwei weiteren bestbewerteten Manager erhalten die weiteren zwei Plätze. Dabei ist die Divisionzugehörigkeit nicht von Bedeutung.</li>
    </ol>
    
    <h3 bind:this={eightThree}>Tiebreaker</h3>
    <ol start="6">
         <li>Für den Fall, dass ein Club in Bezug auf die Win Percentage gleichauf liegen sollte, ist der Tiebreaker die Gesamtpunktzahl der erzielten Punkte (PF) während der regulären Saison.</li>
    </ol>    
    
    <h3 bind:this={eightFour}>Bestimmungen</h3>
    <ol start="7">
         <li>Der Sieger der Playoffs und damit der Liga erhält den Pokal mit eingraviertem Namen.</li>
         <li>Der Verlierer der Liga in der Regular Season erhält den First Pick der nächsten Saison.</li>
    </ol>    
    
    
    <h2 class="sectionHeading" bind:this={nine}>Artikel IX: REGELVERSTÖßE</h2> 
    
    <h3 bind:this={nineOne}>Art der Straftaten</h3>
    <ol>
         <li>Dieser Artikel befasst sich mit Regelverstößen, die über geringfügige Verstöße gegen diese Constitution hinausgehen und einer strengeren Bestrafung bedürfen.</li>
    </ol>
    
    <h3 bind:this={nineTwo}>Einleitung eines Ordnungswidrigkeitenverfahrens</h3>
    <ol start="2">
         <li>Der Commissioner kann von sich aus oder nach Eingang einer anonymen oder öffentlichen, begründeten Beschwerde verkünden, dass ein Manager eine Regelwidrigkeit begangen hat und die Strafe benennen.</li>
         <li>Der Commissioner ist befugt, mutmaßliche Regelwidrigkeiten zu untersuchen, wenn er dies für notwendig hält, und die Manager sind verpflichtet, bei solchen Untersuchungen zu helfen, indem sie dem Commissioner wahrheitsgemäße Aussagen machen, wenn sie dazu aufgefordert werden.</li>
    </ol>
    
    <h3 bind:this={nineThree}>Regelverstöße</h3>
    <ol start="4">
         <li>Jeder begeht einen Regelverstoß, der ...:</li>
            <ol type="a">
                <li>><u>Bestechung:</u> ... einer anderen Partei einen anderen Wert als den In-Game Wert im Austausch für Leistungen oder Trades im Spiel bietet.</li>
                <li>><u>Collusion:</u> ... mit einer anderen Partei vereinbart, den offenen Wettbewerb im Spiel einzuschränken, indem andere getäuscht, irregeführt oder betrogen werden, damit eine Partei, die an der Absprache beteiligt sein kann oder nicht, einen unfairen Marktvorteil erlangt.</li>
                    <ol type="i">
                        <li>Eine Collusion wird in jedem Fall angenommen, wenn ein Manager gleichzeitig für mehr als einen Club tätig ist.</li>
                    </ol>
                <li>><u>Respektlosigkeit:</u> ... beleidigende, aggressive, unangenehme oder abfällige Kommentare zu einer anderen Partei macht, die von anderen Menschen als mehr als freundlichem "Trash Talk" betrachtet werden würde.</li>
                <li>><u>Belästigung:</u> ... wiederholt eine andere Partei kontaktiert, obwohl diese Partei darum gebeten hat, dies zu unterlassen.</li>
                <li>><u>Wettbewerbswidriges Verhalten:</u> ... die Absicht zeigt, nicht mehr am Spiel teilzunehmen.</li>
                    <ol type="i">
                        <li>Unter extremen Umständen kann eine wiederholte Weigerung, sich an angemessenen Trades zu beteiligen, als wettbewerbswidriges Verhalten angesehen werden.</li>
                    </ol>
                <li>><u>Belästigung:</u> ... sich wiederholt über den Betrieb in der Liga in dem Maße beschwert, dass es auf eine Belästigung des Commissioners hinausläuft oder den Spaß anderer deutlich verringert.</li>
                <li>><u>Allgemein:</u> ... ein Verhalten zeigt, das nicht anderweitig durch diese Verfassung verboten ist, aber allgemein als beschissen anerkannt wird.</li>
            </ol>
    </ol>    
    
    <h3 bind:this={nineFour}>Strafen</h3>
    <ol start="5">
         <li>Jeder Manager, der einer Regelwidrigkeit für schuldig befunden wird, kann eine Strafe gemäß Artikel II, Abschnitt 6, einschließlich einer dauerhaften Suspendierung ohne Rücknahme erhalten.</li>
         <li>Der Commissioner kann nach eigenem Ermessen einen Club für die Handlungen eines Managers bestrafen.</li>
         <li>Entscheidungen über eine Straftat und ihre Strafe können gemäß Artikel II, Abschnitt 5 überprüft werden.</li>
         <li>Folgende Strafen werden ausgesprochen:</li>
             <ol type="a">
                 <li><b>Illegal Lineup</b> – Abzug von 10 Punkten pro illegalem Spieler bei Kick-Off des individuellen Teams. Dazu zählen aufgestellte Spieler mit folgendem Status:</li>
                        <ol type="i">
                            <li>OUT, IR, SUP, PUP;</li>
                            <li>Bye-Week; </li>
                            <li>NFL-Free Agents</li>
                        </ol>
                 <li><b>Ungültiger Spieler auf IR</b> – Abzug von 10 Punkten.</li>
                 <li>Weitere Strafen können vom Commissioner im League Chat kommuniziert werden. Insbesondere bei Wiederholten Strafen können diese vom Commissioner angepasst und verschärft werden.</li>
        </ol>
    </ol>
    
    <h3 bind:this={nineFive}>Schiedsrichter</h3>
    <ol start="9">
         <li>Der Commissioner ist nach Artikel II, Abschnitt 2, Absatz d) ausdrücklich befugt, einen neutralen Schiedsrichter zu ernennen, wenn er dies für erforderlich hält; und muss dies tun, wenn er an einem mutmaßlichen Regelverstoß selbst beteiligt ist. Trotz Artikel II, Abschnitt 5 ist die Entscheidung, einen Schiedsrichter zu ernennen, nicht diskutierbar.</li>
         <li>Ein Schiedsrichterbeschluss ist nicht bindend, sondern nur beratend.</li>
         <li>Schiedsrichterbeschlüsse dürfen nicht geheim sein.</li>
         <li>Es gibt kein Mindestquorum- oder Abstimmpflicht für eine unverbindliche Schiedsrichterabstimmung mit den Managern.</li>
    </ol>             
                 
               
 
 <p>VEREINBART mit diesem Tag, dem 01. Februar 2024.</p>               

    
  <h2 class="sectionHeading" bind:this={ten}>Anhang "A": FINANZEN</h2>  
   <p>Der Schatzmeister wird von der Mitgliedern der League auf unbestimmte Zeit gewählt. Es ist möglich ein Misstrauensvotum zu jeder Zeit durchzuführen und gleichzeitig einen neuen Schatzmeister zu wählen. Dazu bedarf es einen formlosen Antrag an den Commissioner. Bö wurde zum Schatzmesiter ernannt. 
   Die Aufgaben sind das Eintreiben eines unbestimmten Beitragd, die Verwaltung und Buchführung der Finanzen, die Genehmigung von Ausgaben und das Auszahlen des benötigten Betrags. Jedes Jahr wird von jedem Manager ein Buy-In Beitrag von 5€ erhoben. Dieses Budget soll für die Gravierung der beiden Trophäen, für eine eventuelle Neuanschaffung dieser und für den Versand an Manager dienen. Schatzmeister sammelt das Geld in der Offseason ein und verwalten es über die gesamte Zeit. Zusätzlich wird jährlch ein schriftlicher Bericht angefertigt.</p>

  <h2 id="anhangb" class="sectionHeading" bind:this={eleven}>Anhang "B": VERSIONSHISTORIE</h2>  
  
  <table border="1">
  <tr>
    <th>Anhang</th>
    <th>Anhang Beschreibung</th>
    <th>Verantwortlicher</th>
    <th>Datum</th>
  </tr>
  <tr>
    <td>01</td>
    <td>Erstmalige Erstellung</td>
    <td>Marcus</td>
    <td>14.01.2024</td>
  </tr>
</table>
    
</div>
