<!DOCTYPE html>
<html>

<head>
  <title>
    Parse poems
  </title>
</head>

<body>
  <div style="height:60px" aria-hidden="true" class="wp-block-spacer"></div>
  <hr class="wp-block-separator has-alpha-channel-opacity is-style-dots">
  <div style="height:60px" aria-hidden="true" class="wp-block-spacer"></div>
  <div id="presentation"></div>
  <div style="height:60px" aria-hidden="true" class="wp-block-spacer"></div>
  <div style="height:60px" aria-hidden="true" class="wp-block-spacer"></div>
</body>
<script>


  const poems = [

    "De schreeuw van morgen breekt de schemer,\nwaar klokken kaakslag na kaakslag tasten.\nGolvend hoofd van gister's halve stemmer,\ntocht door mist, nog vochtig van het rasten.\n\nWanneer woorden weerklinken in de lucht,\ndansen kleuren ongeremd door straten.\nRottende zon rijkt naar de hemelzucht,\ndiep in de reliëfs van de verlaten.\n\nLelijk is de vreugd van het voorbije lied,\nziet de wereld zijn ware spiegel niet.",

    "In de schaduw der daden vind ik licht,\nzwart en wit geslacht op spiegelglas,\nogen die branden met de mond van de nacht,\nik spreek in de taal van de blinde wind.\n\nDe regen is een gevleugelde schim,\nlachend met een mond vol hagelstenen,\nwaar het zweet van onze dromen druipt,\nbevlekt de schreeuw van de ochtend.\n\nEen schaduw legt zich neer als een sjaal,\nom de hals van wie niet kent, maar loopt.",

    "De nacht likt het licht van muren wit\nen alles schreeuwt in stilte gedachten zwart.\nHier zweven woorden, krom en spits,\nals dauwdruppels in verkreukeld hart.\n\nHet oog van gisteren knipoogt schril,\nde tijd trekt haastig golven in de zee.\nIn de schaduw van een roos, zo stil,\nverspringt het heden naar een verre eeuw.\n\nWant wie gelooft in een cirkel omarmd,\nvindt in chaos een glimlach bewaard.",

    "In het galgenlied van mijn dromen zing ik\nschor en schimmig in het verwarde licht –\nde dichtersraven krassen schemering\nen woorden slaan als houten hamers\nop de kreukels van het platte vlees.\n\nAch, de meester van het wilde waas\nverstomt het zonkâltige geluid\nvan grijze engelen in hun trommels.\nDiep het schilderachtige bittere zout\nkringelt om de krans van muzelige muten.",

    "Krekelzang breekt de stilte, \nwaar de mens in scherven spreekt,\neen kermis van klanken\nbuiten de wetten der wijsbegeerte.\nSchreeuw om het onuitsprekelijke,\nsporen van een onbreekbare taal.\nVermenigvuldig de zon,\nomarm de illusies van het vlees,\nwant in de bedwelming van de nacht\nverliefd op het leven als een bevel.",

    "In de rinkelende zinnen zing ik zacht,\nde maan een hongerige harlekijn,\nmother's milk word konfituur in de nacht,\nen ik ben de koning van het stof, een zuivere schijn.\n\nWankelende woorden weten weinig,\nwoorden worstelen om wind,\nde wereld is een wonderlijk weefsel,\nik ben een kind van koninklijk kind.\n\nMorgen de meester over elke muse,\nmaar vandaag ben ik niets dan bruisend blus.",

    "In de rauwe schoot der stadskreten,\nwaar beton en harten breken\nfluistert de nacht als een blinde muze\n\nschaduwen dansen, schurend langs de ziel,\nogen staren, eeuwig hongerig,\nachter ramen, ondoorgrondelijk als mythes\n\nwoorden vallen, koude vuurstenen breken,\ndichter zwijgt, zijn schreeuw begraven\nomdat zelfs de vogels\nin hun herfstvrees\nniet kunnen zingen.",

    "In de schaduw van het neon, dansen woorden\nzonder gezichten, blote grenzen aan het raam\nwaar de regen als gedachten stroomt, chaotisch.\n\nMijn ziel is een wirwar van goddelijke krabbel,\nheilige inspiratie en aardse twijfel samen verweven.\nEen krijtstreep treurende tederheid zoekt een vergezicht\n\ndat zichzelf schildert in zekere lijnen van verlangen.\nDe wereld ademt, stopt, en begint weer, eindeloos\nin die koortsige jungle waar tijden niet bestaan, \n\nen Lucebert’s stem fluistert tussen beton en dromen.",

    "In de glanzende chaos zonder kruin\nwaar dromen als zeepbellen barsten,\ndool ik als een kind van zwart karton,\nzoekt mijn schreeuw naar vormen.\n\nGod staart door het kille venster,\nletters sidderen als vissen op het droge.\nIk ben de koning van niets,\nen mijn troon is gemaakt van lucht en schaduwen.\n\nDe eeuwige leegte huilt, \nom een wereld die nooit slapen kan.",

    "O vreemdeling van het neonlicht, de stad zingt\nschaduwliedjes in de poriën van een visioen.\nGlazen ogen schreeuwen naar de tijd die vlucht,\neen mierenhoop van staal en vlees ontwaakt.\n\nJe knieën buigen voor zilveren niemandswezens,\nin de vlam van de eeuwige ochtend,\nwaar woorden stukslaan op de muren van stilte,\nzo zingt de chaos zijn bittere hymne.\n\nDe kosmos graaft in jouw naakte ziel,\nwaar herfst en vriendschap als messen zwijgen.",

    "In de schaduw van de morgensterren\nhuilt de zon om haar verloren licht,\ngebroken zinnen wapperen als gembergras,\ngeurend naar liefde die nooit vervaagt.\n\nDe wereld slaat met al zijn kleuren\neen gat in de stilte van het bestaan,\nwaar goden wandelen op glazen velden,\nversplintert de hoop in duizenden druppels.\n\nDe dichter zingt, verwond door schoonheid,\nzijn woorden bloeden rood op wit papier.",

    "In de diepte schreeuwt een eeuwig krassend kind,\nwaar de bloemen van steen bloeien in stilte,\nroestige woorden baren het brood van de nacht,\nals neergedaalde engelen zonder vleugels.\n\nGebroken spiegels dromen van een hevig licht,\nschilders en dichters met blinde ogen\nbotvieren hun scherpe tongen op papier,\nhun namen geschreven in vervlogen zand.\n\nAlles van waarde is weerloos en bloedrood,\nwaar het gras van de tijd fluistert: blijf staan.",

    "In de schimmel van de nacht, hoestend\nplakken woorden hard, weerbarstig aan de lucht\nkleuren verdwijnen als het kind dat droomt\nen ik, een schimmelende schildwacht, besta slechts in twijfel.\n\nTussen de scheuren van mijn taal, gloeit soms een god\neen gesternte van radeloozen, lichtend noch verblekend\nluiden wij naar de transpiraties van de dageraad, de rillingen \nvan een helende heiland, die slechts bestaat\nals een echo van leegte, een fluistering van het niets\no, geliefde ellende, van je glans leef ik."

  ];

  // RANDOMN FUNCTIONS
  //
  function randomInteger(min, max) {
    return Math.floor(Math.random() * (max - min) + min);
  }

  function pickRandom() {
    return arguments[randomInteger(0, arguments.length)]
  }

  function shuffle(array) {
    let currentIndex = array.length;

    while (currentIndex != 0) {
      let randomIndex = Math.floor(Math.random() * currentIndex);
      currentIndex--;
      [array[currentIndex], array[randomIndex]] = [
        array[randomIndex], array[currentIndex]];
    }
  }

  // STRING FUNCTIONS
  //
  function filterEmptyStrings(array) {
    let filteredArray = []

    for (let i = 0; i < array.length; i++) {
      string = array[i]
      if (string !== '') {
        filteredArray.push(string);
      }
    }
    return filteredArray
  }

  function stanzaSplit(poem) {
    console.log("stanzaSplit")
    splitPoem = poem.split(/(\n\n)/) // breek per strofe
    let splitPoemHTML = []

    for (let i = 0; i < splitPoem.length; i++) {
      let unit = splitPoem[i]
      unit = unit.replace(/\n\n/g, '<br/>')
      unit = unit.replace(/\n/g, '<br/>')
      splitPoemHTML.push(unit);
    }
    return splitPoemHTML
  }

  function lineSplit(poem) {
    console.log("lineSplit")
    splitPoem = poem.split(/(\n+)/) // breek per regel
    let splitPoemHTML = []

    for (let i = 0; i < splitPoem.length; i++) {
      let unit = splitPoem[i]
      unit = unit.replace(/\n\n/, '<br/>')
      unit = unit.replace(/\n/, '')
      splitPoemHTML.push(unit);
    }
    return splitPoemHTML
  }

  // RENDER FUNCTIONS
  //

  function timePoem(poem) {
    let timedPoem = []

    // determine timings for each unit
    for (let i = 0; i < poem.length; i++) {
      let unit = poem[i]
      let delay = randomInteger(100, 15000)
      let interval = randomInteger(100, 300)
      //let timing = [ ]
      let timedUnit = {}
      timedUnit["string"] = unit
      timedUnit["delay"] = delay
      timedUnit["interval"] = interval
      timedUnit["length"] = unit.length
      timedUnit["duration"] = delay + interval * unit.length
      timedPoem.push(timedUnit)
    }

    // determine first and last units to finish
    let durations = []
    for (let i = 0; i < timedPoem.length; i++) {
      duration = timedPoem[i].duration
      durations.push(duration)
    }
    let firstUnit = durations.indexOf(Math.min(...durations))
    let lastUnit = durations.indexOf(Math.max(...durations))
    timedPoem[firstUnit]["placement"] = "first"
    timedPoem[lastUnit]["placement"] = "last"

    return timedPoem
  }

  function renderPoem(timedPoem) {

    for (let i = 0; i < timedPoem.length; i++) {
      let unit = timedPoem[i]
      console.log(unit)

      // Create divs outside of setTimeout, so units will print in correct order
      let newDiv = document.createElement("div")
      newDiv.id = `div${i}`
      document.getElementById("presentation").appendChild(newDiv);

      // Retrieve values for each unit
      let string = unit["string"]
      let delay = unit["delay"]
      let interval = unit["interval"]
      let placement = unit["placement"]

      // The render function
      function printUnit(onComplete) {
        let char = 0
        let timer = setInterval(function () {
          console.log
          document.getElementById(`div${i}`).innerHTML = string.slice(0, char);
          if (char > (string.length - 1)) {
            clearInterval(timer);
            console.log(`Unit ${i} completed.`)
            if (onComplete) {
              onComplete()
            }
          } else {
            char++;
          }
        }, interval)
      }

      // Launch units
      if (placement != "last") {
        setTimeout(printUnit, delay)
      } else {
        setTimeout(printUnit, delay, onLastLine)
      }


    }
  }

  function onLastLine() {
    let delay = randomInteger(1000, 10000)
    console.log("Poem completed.")
    setTimeout(function () {
      document.getElementById("presentation").innerHTML = ""
      loopPoems()
    }, delay)
  }
  ///////////////
  // MAIN LOOP //
  ///////////////

  let poemIndex = Math.floor(Math.random() * poems.length);
  function loopPoems() {
    let newPoemIndex = Math.floor(Math.random() * poems.length);
    while (newPoemIndex == poemIndex) {
      newPoemIndex = Math.floor(Math.random() * poems.length);
    } 
    poemIndex = newPoemIndex
    poem = poems[poemIndex]
    renderPoem(timePoem(filterEmptyStrings(pickRandom(stanzaSplit(poem), lineSplit(poem)))))
  
  }

  loopPoems()

</script>

</html>
