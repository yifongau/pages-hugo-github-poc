---
date: 2025-09-01
draft: no
title: 'test met html'
---

<!DOCTYPE html>
<html lang="en">

<head>

  <!-- CSS -->
  <style type="text/css" id="alt_translations">
    :root {
      --duration: 1s;
      --grey: #606060;
      --black: #0a0a0a;
      --color: var(--black);
    }
	  
	  h3 {
		  margin-top: 2.4rem;
		  margin-bottom: 1rem;
	  }

    .alt_insert::after {
      color: var(--color);
      content: "";
      animation: var(--alt_key) var(--duration) linear infinite;
      animation-play-state: var(--play_state)
    }

    #ongekende_alt {
      --alt_key: ongekende_alt;
      --play_state: paused;
    }

    @keyframes ongekende_alt {
      0% {
        content: "ongekende";
      }

      50% {
        content: "ongeëvenaarde";
      }

      100% {
        content: "ongekende";
      }
    }

    #geslepenheid_alt {
      --alt_key: geslepenheid_alt;
      --play_state: paused;
    }

    @keyframes geslepenheid_alt {
      0% {
        content: "geslepenheid";
      }

      20% {
        content: "doortraptheid";
      }

      40% {
        content: "slinksheid";
        font-style: normal;
      }

      60% {
        content: "gewiekstheid";
        font-style: normal;
      }

      80% {
        content: "brattiness";
        font-style: italic;
      }

      100% {
        content: "geslepenheid";
      }
    }

    #locatie_alt {
      --alt_key: locatie_alt;
      --play_state: paused;
    }

    @keyframes locatie_alt {
      0% {
        content: "locatie";
      }

      50% {
        content: "(geografische) locatie";
      }

      100% {
        content: "locatie";
      }
    }

    #toekomstloze_alt {
      --alt_key: toekomstloze_alt;
      --play_state: paused;
    }

    @keyframes toekomstloze_alt {
      0% {
        content: "toekomstloze";
      }

      50% {
        content: "oeverloze";
      }

      100% {
        content: "toekomstloze";
      }
    }

    #uitspint_alt {
      --alt_key: uitspint_alt;
      --play_state: paused;
    }

    @keyframes uitspint_alt {
      0% {
        content: "uitspint";
      }

      50% {
        content: "uitspeelt";
      }

      100% {
        content: "uitspint";
      }
    }

    #vraagt_alt {
      --alt_key: vraagt_alt;
      --play_state: paused;
    }

    @keyframes vraagt_alt {
      0% {
        content: "vraagt";
      }

      50% {
        content: "eist";
      }

      100% {
        content: "vraagt";
      }
    }

    #standvastigheid_alt {
      --alt_key: standvastigheid_alt;
      --play_state: paused;
    }

    @keyframes standvastigheid_alt {
      0% {
        content: "standvastigheid";
      }

      30% {
        content: "volharding";
      }

      60% {
        content: "vasthoudendheid"
      }

      100% {
        content: "standvastigheid";
      }
    }

    #anders_alt {
      --alt_key: anders_alt;
      --play_state: paused;
    }

    @keyframes anders_alt {
      0% {
        content: "anders";
      }

      50% {
        content: "niet zo";
      }

      100% {
        content: "anders";
      }
    }

    #verreeksing_alt {
      --alt_key: verreeksing_alt;
      --play_state: paused;
    }

    @keyframes verreeksing_alt {
      0% {
        content: "verreeksing";
      }

      50% {
        content: "sequencing";
        font-style: italic;
      }

      100% {
        content: "verreeksing";
      }
    }

    #daadwerkelijk_alt {
      --alt_key: daadwerkelijk_alt;
      --play_state: paused;
    }

    @keyframes daadwerkelijk_alt {
      0% {
        content: "daadwerkelijk";
      }

      50% {
        content: "echt";
      }

      100% {
        content: "daadwerkelijk";
      }
    }

    #koper_alt {
      --alt_key: koper_alt;
      --play_state: paused;
    }

    @keyframes koper_alt {
      0% {
        content: "koper";
      }

      50% {
        content: "consument";
      }

      100% {
        content: "koper";
      }
    }

    #stilstaande_alt {
      --alt_key: stilstaande_alt;
      --play_state: paused;
    }

    @keyframes stilstaande_alt {
      0% {
        content: "stilstaande";
      }

      30% {
        content: "saaie";
      }

      60% {
        content: "banale"
      }

      100% {
        content: "stilstaande";
      }
    }

    #rommel_alt {
      --alt_key: rommel_alt;
      --play_state: paused;
    }

    @keyframes rommel_alt {
      0% {
        content: "rommel";
      }

      50% {
        content: "cruft";
        font-style: italic;
      }

      100% {
        content: "rommel";
      }
    }

    #gebouwd_alt {
      --alt_key: gebouwd_alt;
      --play_state: paused;
    }

    @keyframes gebouwd_alt {
      0% {
        content: "gebouwd";
      }

      50% {
        content: "ontworpen";
      }

      100% {
        content: "gebouwd";
      }
    }

    #verlammende_alt {
      --alt_key: verlammende_alt;
      --play_state: paused;
    }

    @keyframes verlammende_alt {
      0% {
        content: "verlammende";
      }

      30% {
        content: "slopende";
      }

      60% {
        content: "verontmogelijkende"
      }

      100% {
        content: "verlammende";
      }
    }

    #smoren_alt {
      --alt_key: smoren_alt;
      --play_state: paused;
    }

    @keyframes smoren_alt {
      0% {
        content: "smoren";
      }

      30% {
        content: "wurgen";
      }

      60% {
        content: "drosselen"
      }

      100% {
        content: "smoren";
      }
    }

    #miserabele_alt {
      --alt_key: miserabele_alt;
      --play_state: paused;
    }

    @keyframes miserabele_alt {
      0% {
        content: "miserabele";
      }

      25% {
        content: "jammerlijke";
      }

      50% {
        content: "vreselijke";
      }

      75% {
        content: "idiote"
      }

      100% {
        content: "miserabele"
      }
    }

    #vrouwelijke_alt {
      --alt_key: vrouwelijke_alt;
      --play_state: paused;
    }

    @keyframes vrouwelijke_alt {
      0% {
        content: "‘vrouwelijke’";
      }

      50% {
        content: "‘feminiene’";
      }

      100% {
        content: "‘vrouwelijke’";
      }
    }

    #mannelijke_alt {
      --alt_key: mannelijke_alt;
      --play_state: paused;
    }

    @keyframes mannelijke_alt {
      0% {
        content: "‘mannelijke’";
      }

      50% {
        content: "‘masculiene’";
      }

      100% {
        content: "‘mannelijke’";
      }
    }

    #niet_alt {
      --alt_key: niet_alt;
      --play_state: paused;
    }

    @keyframes niet_alt {
      0% {
        content: "niet";
      }

      50% {
        content: "nooit";
      }

      100% {
        content: "niet";
      }
    }

    #snijden_alt {
      --alt_key: snijden_alt;
      --play_state: paused;
    }

    @keyframes snijden_alt {
      0% {
        content: "snijden";
      }

      50% {
        content: "kruisen";
      }

      100% {
        content: "snijden";
      }
    }
  </style>

  <!-- JAVASCRIPT -->
  <script>


    let scrollTimer = null;
    let elements = document.querySelectorAll(".alt_scope");

    function refreshElements() {

      if (elements.length == 0) {
        elements = document.querySelectorAll(".alt_scope");
      }

      if (scrollTimer !== null) {
        clearTimeout(scrollTimer);
      }

      scrollTimer = setTimeout(() => {
        pauseAll(elements);
      }, 250);

      runAll(elements);
    }

    function pauseAll(elements) {
      elements.forEach(element => {
        element.style.setProperty("--play_state", 'paused')
        element.style.setProperty("--color", 'var(--black)');
      });
    }

    function runAll(elements) {
      elements.forEach(element => {
        element.style.setProperty("--play_state", 'running');
        element.style.setProperty("--color", 'var(--grey)');
      });
    }

    document.addEventListener("DOMContentLoaded", refreshElements);
    window.addEventListener("scroll", refreshElements);
    window.addEventListener("resize", refreshElements);
  </script>

</head>

<!-- HTML -->

<body>
  <h3>0x00: onze toekomsten eisen dat wij ons ontdoen van onze verlamming</h3>
  <p>
    De onze is een wereld in/van vertigo. Het is een wereld zwermend van
    technologische mediaties die onze levens vervlecht met
    abstractie, virtualiteit en complexiteit. XF construeert een feminisme dat
    zich hieraan aanpast: een feminisme van <span class="alt_scope" id="ongekende_alt"><span class="alt_insert"></span>
    </span> <span class="alt_scope" id="geslepenheid_alt"><span class="alt_insert"></span></span> en visie op een nog
    niet eerder
    vertoonde schaal; een toekomst waarin de verwerkelijking van
    genderrechtvaardigheid en feministische emancipatie bijdragen aan een
    universalistische politiek, geassembleerd uit de behoeftes van alle
    mensen – ongeacht ras, fysieke en mentale vermogens, economische positie en
    <span class="alt_scope" id="locatie_alt"><span class="alt_insert"></span></span>. Weg met de
    <span class="alt_scope" id="toekomstloze_alt"><span class="alt_insert"></span></span>
    herhalingen op de tredmolen van het kapitaal. Weg met de onderworpenheid
    aan het geploeter van (re)productieve arbeid. Weg met de reïficatie van
    het gegevene onder het mom van kritiek. Onze visie vereist dat we ons
    ontdoen van onze verlamming. XF beroept zich niet op
    revolutie, maar zet in op het langzame uitspelen van de geschiedenis. XF <span class="alt_scope" id="vraagt_alt"><span
        class="alt_insert"></span></span>
    verbeeldingskracht, behendigheid en <span class="alt_scope" id="standvastigheid_alt"><span
        class="alt_insert"></span></span>.
  </p>

  <h3>0x01: vrijheid is niet een gegeven</h3>

  <p>
    XF grijpt vervreemding aan als aanleiding voor het genereren van nieuwe
    werelden. We zijn allemaal vervreemd – is dat ooit
    <span class="alt_scope" id="anders_alt"><span class="alt_insert"></span></span> geweest? Het
    is juist dankzij, niet ondanks, onze vervreemding dat we ons kunnen
    bevrijden uit de drek der onmiddellijkheid. Vrijheid is geen
    gegeven, en het is al helemaal niet gegeven door iets
    ‘natuurlijks’. De vervaardiging van vrijheid vraagt niet om minder, maar om
    meer vervreemding. Vervreemding is de arbeid waaruit vrijheid ontstaat.
    Niets dient aanvaard te worden als onveranderlijk, permanent of ‘gegeven’ – materiële noch sociale condities. XF muteert, bevraagt en verkent elke
    horizon. Degenen die door de heersende biologische normen worden weggezet
    als ‘onnatuurlijk’, die onrecht hebben ervaren in naam van de natuurlijke
    orde, zij weten dat de verheerlijking van de ‘natuur’ ons niets te bieden
    heeft. Degenen die queer of trans zijn, of fysiek of mentaal beperkt worden,
    degenen die gediscrimineerd worden vanwege zwangerschap of
    ouderschapstaken; zij weten dat. XF is fel anti-naturalistisch. Een
    essentialistisch naturalisme riekt naar theologie – hoe eerder het
    uitgedreven wordt, hoe beter.
  </p>

  <h3>0x02: technologie is niet inherent progressief</h3>

  <p>
    Waarom worden technologieën eigenlijk zo weinig op een
    expliciete en georganiseerde manier ingezet om een progressieve
    genderpolitiek te voeren? XF probeert de wereld te herontwerpen door
    bestaande technologieën op een strategische manier in te zetten. Er zijn
    grote risico’s ingebouwd in deze technologische middelen; ze zijn vatbaar
    voor <i>bias</i>, misbruik en
    exploitatie van de zwakken. XF pleit voor een assemblage van
    technopolitieke interfaces die reageren op deze risico’s, in plaats van te
    doen alsof er geen risico’s zijn. Technologie is niet inherent progressief.
    Het gebruik ervan is versmolten met cultuur in een positieve
    feedbackloop die lineaire <span class="alt_scope" id="verreeksing_alt"><span class="alt_insert"></span></span>,
    voorspelling en daadwerkelijke
    terughoudendheid onmogelijk maken. Daarom moet technowetenschappelijke
    innovatie verbonden
    worden met een collectief theoretisch en politiek denken waarin vrouwen,
    queers en degenen die gendernonconforming zijn een ongeëvenaarde rol
    spelen.
  </p>

  <h3>0x03: genderongelijkheid kenmerkt de velden waarbinnen onze
    technologieën en hun wetgeving bedacht en gemaakt worden</h3>

  <p>
    Het <span class="alt_scope" id="daadwerkelijk_alt"><span class="alt_insert"></span></span>
    emancipatoire potentieel van technologie is nog niet gerealiseerd. Gevoed
    door de markt, neutraliseert uitdijing diens snelle groei, en wordt
    elegante innovatie afgestaan aan de <span class="alt_scope" id="koper_alt"><span
        class="alt_insert"></span></span>, wiens <span class="alt_scope" id="stilstaande_alt"><span
        class="alt_insert"></span></span> wereld het
    versiert. Het is onze taak om, voorbij de lawaaiige wanordelijkheid van
    gecommodificeerde <span class="alt_scope" id="rommel_alt"><span class="alt_insert"></span></span>, technologieën te
    ontwerpen ter bestrijding van de ongelijke toegang tot reproductieve en farmacologische
    hulpmiddelen, ecologische catastrofes, economische onzekerheid, alsook
    schadelijke vormen van onbetaalde of onderbetaalde arbeid.
    Genderongelijkheid kenmerkt nog steeds het veld waarin onze technologieën en hun wetgeving bedacht en gemaakt worden; terwijl vrouwelijke arbeiders in de elektronica-industrie (om maar
    een industrie te noemen) het slechtst betaalde, meest monotone en
    meest <span class="alt_scope" id="verlammende_alt"><span class="alt_insert"></span></span>
    werk verrichten. Zulk onrecht eist structurele, machinale en ideologische
    correctie.
  </p>

  <h3>0x04: rationalisme zelf moet een feminisme zijn</h3>
  <p>
    XF is een rationalisme. Stellen dat rede en rationaliteit ‘van nature’ patriarchale ondernemingen zijn, is het toegeven van verlies.
    Inderdaad wordt/werd de canonieke ‘geschiedenis van het denken’
    gedomineerd door mannen, en zijn het mannelijke handen die we de
    wetenschappelijke en technologische insituties zien <span class="alt_scope" id="smoren_alt"><span
        class="alt_insert"></span></span>. Dat is precies
    de reden waarom feminisme een rationalisme moet zijn: het moet omwille van, en
    niet ondanks, deze <span class="alt_scope" id="miserabele_alt"><span class="alt_insert"></span></span> onbalans. Er
    is noch een <span class="alt_scope" id="vrouwelijke_alt"><span class="alt_insert"></span></span> noch een
    <span class="alt_scope" id="mannelijke_alt"><span class="alt_insert"></span></span>
    rationaliteit. Wetenschap is geen uitdrukking van gender, maar een
    schorsing ervan. Als de wetenschap vandaag de dag door mannelijke ego’s
    wordt gedomineerd, dan is dat in strijd met zichzelf; en die
    tegenstrijdigheid kan benut worden. De rede, net zoals informatie, wil vrij
    zijn – het patriarchaat kan haar die vrijheid <span class="alt_scope" id="niet_alt"><span
        class="alt_insert"></span></span> geven. Rationalisme zelf moet een feminisme zijn. XF markeert het punt waar deze claims elkaar <span class="alt_scope" id="snijden_alt"><span
        class="alt_insert"></span></span> in een dubbele
    afhankelijkheid. Het benoemt de rede tot een aanjager van feministische
    emancipatie, en verkondigt: iedereen heeft het recht om als niemand in het
    bijzonder te spreken.
  </p>
	</body>

</html>
