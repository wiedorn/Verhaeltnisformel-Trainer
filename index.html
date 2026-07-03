<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Ionenformeln-Spiel</title>
    <style>
        body { 
            font: 1em sans-serif; 
            display: flex; 
            flex-direction: column;
            align-items: center; 
            justify-content: center; 
            margin: 5px;
            background-color: #f9f9f9;
        }
        .game-container {
            max-width: 950px;
            width: 100%;
            text-align: center;
            background: white;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            box-sizing: border-box;
        }
        .menu-row {
            margin: 0 0 10px 0;
            display: flex;
            justify-content: center;
            gap: 10px;
            flex-wrap: wrap;
        }
        .header-row {
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-weight: bold;
            margin-bottom: 5px;
            gap: 10px;
            border-bottom: 1px solid #eee;
            padding-bottom: 5px;
        }
        #titelFeld {
            transition: color 0.2s ease;
            outline: none;
            flex: 1;
        }
        
        .welcome-screen {
            max-width: 500px;
            margin: 20px auto;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 8px;
            background-color: #fafafa;
            text-align: center;
        }
        .main-start-btn {
            height: 45px;
            width: 180px;
            font-size: 1.05em;
            font-weight: bold;
            background-color: #28a745;
            color: white;
            border: 1px solid #1e7e34;
            border-radius: 4px;
            cursor: pointer;
            margin-top: 15px;
        }
        .main-start-btn:hover {
            background-color: #218838;
        }
        
        #gameplay-area {
            display: none;
        }

        .block-display-row {
            display: grid;
            grid-template-columns: 60px 1fr 60px;
            align-items: center; 
            gap: 10px;
            margin: 10px 0;
        }
        .ion-count-box {
            font-size: 2.5em;
            font-weight: bold;
            color: #555;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .canvas-container {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            width: 100%;
        }
        
        canvas { 
            width: 100%; 
            max-width: 384px; 
            height: auto; 
            aspect-ratio: 4/2.4;
            border: 2px solid black; 
            background: #fff;
            outline: none;
        }

        .formula-section-row {
            display: grid;
            grid-template-columns: 1fr auto 1fr;
            align-items: center;
            width: 100%;
            margin-top: 10px;
            box-sizing: border-box;
        }
        .formula-wrapper {
            width: 100%;
            max-width: 384px;
            position: relative;
            box-sizing: border-box;
            min-height: 45px;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        #tippFeld { 
            font-size: 1.8em; 
            font-weight: bold;
            text-align: center;
            min-height: 45px;
            width: 100%;
            display: flex;
            align-items: center;
            justify-content: center;
            word-break: break-word;
            padding: 3px; 
            box-sizing: border-box;
            color: #000000 !important;
        }
        #tippFeld sup, #tippFeld sub {
            font-size: 0.6em;
            line-height: 0;
            position: relative;
            display: inline-block;
        }
        #tippFeld sup { bottom: 0.5em; }
        #tippFeld sub { top: 0.45em; }

        #tippFeld sub.kat-idx { color: #FF4444 !important; font-weight: bold; }
        #tippFeld sub.ani-idx { color: #4444FF !important; font-weight: bold; }

        .small-next-btn {
            display: none;
            height: 40px;
            width: 95px;
            background-color: #efefef;
            color: black;
            border: 1px solid #767676;
            border-radius: 2px;
            font-family: sans-serif;
            font-size: 0.9em;
            cursor: pointer;
            box-sizing: border-box;
            justify-self: end;
        }
        .small-next-btn:hover {
            background-color: #e5e5e5;
            border-color: #4f4f4f;
        }

        .main-grid {
            margin-top: 15px;
            width: 100%;
        }
        .buttons-wrapper {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 15px;
            width: 100%;
        }
        
        #kationen {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 4px;
            background: #FFEAEA;
            border: 1px solid #FFCCCC;
            border-radius: 6px;
            padding: 6px;
        }
        #anionen {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 4px;
            background: #EAEAff;
            border: 1px solid #CCCCFF;
            border-radius: 6px;
            padding: 6px;
        }
        
        #kationen button { 
            height: 34px; 
            width: 100%; 
            font-weight: bold;
            cursor: pointer;
            font-size: 0.9em;
            padding: 2px;
            box-sizing: border-box;
            background-color: #FFDDDD;
            border: 1px solid #FF8888;
            color: #A02020;
            border-radius: 4px;
        }
        #kationen button:hover { background-color: #FFAAAA; }
        
        #anionen button { 
            height: 34px; 
            width: 100%; 
            font-weight: bold;
            cursor: pointer;
            font-size: 0.9em;
            padding: 2px;
            box-sizing: border-box;
            background-color: #DDDDFF;
            border: 1px solid #8888FF;
            color: #2020A0;
            border-radius: 4px;
        }
        #anionen button:hover { background-color: #AAAAFF; }
        
        .big-btn {
            height: 40px;
            width: 115px;
            background-color: #efefef;
            color: black;
            border: 1px solid #767676;
            border-radius: 2px;
            cursor: pointer;
            font-size: 0.9em;
        }
        .big-btn:hover {
            background-color: #e5e5e5;
        }

        .testmodus-aktiv {
            border: 2px dashed #767676 !important;
            background-color: #f5f5f5 !important;
            cursor: text;
            border-radius: 6px;
        }
        .testmodus-aktiv:empty::before {
            content: "Verhältnisformel...";
            font-size: 0.6em;
            color: #888;
            font-style: italic;
            font-weight: normal;
        }
        
        #hiddenInput {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            opacity: 0;
            z-index: 5;
            cursor: text;
        }

        @media (max-width: 600px) {
            .block-display-row {
                grid-template-columns: 40px 1fr 40px;
                gap: 5px;
            }
            .formula-section-row {
                grid-template-columns: 1fr auto 1fr;
            }
            .ion-count-box { font-size: 1.8em; }
            .buttons-wrapper { gap: 8px; }
            #kationen, #anionen { padding: 4px; gap: 3px; }
            .big-btn { width: 31%; font-size: 0.8em; padding: 2px; }
            #tippFeld { font-size: 1.4em; min-height: 40px; }
            .formula-wrapper { max-width: 100%; }
            .small-next-btn { width: 70px; font-size: 0.85em; height: 36px; }
        }
    </style>
    <script>
        'use strict';

        var basisAnionen = [
            { name: "Fluorid", formel: "F<sup>-</sup>", ladung: -1, molekuel: false },
            { name: "Chlorid", formel: "Cl<sup>-</sup>", ladung: -1, molekuel: false },
            { name: "Bromid", formel: "Br<sup>-</sup>", ladung: -1, molekuel: false },
            { name: "Iodid", formel: "I<sup>-</sup>", ladung: -1, molekuel: false },
            { name: "Oxid", formel: "O<sup>2-</sup>", ladung: -2, molekuel: false },
            { name: "Sulfid", formel: "S<sup>2-</sup>", ladung: -2, molekuel: false },
            { name: "Nitrid", formel: "N<sup>3-</sup>", ladung: -3, molekuel: false },
            { name: "Phosphid", formel: "P<sup>3-</sup>", ladung: -3, molekuel: false }
        ];

        var basisKationen = [
            { name: "Lithium", formel: "Li<sup>+</sup>", ladung: 1, molekuel: false },
            { name: "Natrium", formel: "Na<sup>+</sup>", ladung: 1, molekuel: false },
            { name: "Kalium", formel: "K<sup>+</sup>", ladung: 1, molekuel: false },
            { name: "Calcium", formel: "Ca<sup>2+</sup>", ladung: 2, molekuel: false },
            { name: "Magnesium", formel: "Mg<sup>2+</sup>", ladung: 2, molekuel: false },
            { name: "Aluminium", formel: "Al<sup>3+</sup>", ladung: 3, molekuel: false },
            { name: "Eisen(II)-", formel: "Fe<sup>2+</sup>", ladung: 2, molekuel: false },
            { name: "Eisen(III)-", formel: "Fe<sup>3+</sup>", ladung: 3, molekuel: false },
            /* KORREKTUR: "Silber" zu "Silber(I)-" geändert */
            { name: "Silber(I)-", formel: "Ag<sup>+</sup>", ladung: 1, molekuel: false }
        ];

        var expertenAnionenVollstaendig = [
            { name: "Carbonat", formel: "CO<sub>3</sub><sup>2-</sup>", ladung: -2, molekuel: true },
            { name: "Hydrogencarbonat", formel: "HCO<sub>3</sub><sup>-</sup>", ladung: -1, molekuel: true },
            { name: "Hydroxid", formel: "OH<sup>-</sup>", ladung: -1, molekuel: true },
            { name: "Nitrat", formel: "NO<sub>3</sub><sup>-</sup>", ladung: -1, molekuel: true },
            { name: "Nitrit", formel: "NO<sub>2</sub><sup>-</sup>", ladung: -1, molekuel: true },
            { name: "Permanganat", formel: "MnO<sub>4</sub><sup>-</sup>", ladung: -1, molekuel: true },
            { name: "Phosphat", formel: "PO<sub>4</sub><sup>3-</sup>", ladung: -3, molekuel: true },
            { name: "Sulfat", formel: "SO<sub>4</sub><sup>2-</sup>", ladung: -2, molekuel: true },
            { name: "Sulfit", formel: "SO<sub>3</sub><sup>2-</sup>", ladung: -2, molekuel: true }
        ];

        var expertenKationenVollstaendig = [
            { name: "Ammonium", formel: "NH<sub>4</sub><sup>+</sup>", ladung: 1, molekuel: true }
        ];

        var aktuelleAnionen = [];
        var aktuelleKationen = [];

        var frageKation = null;
        var frageAnion = null;
        var frageKationenZahl = 0;
        var frageAnionenZahl = 0;
        var antwortAnionenZahl = 0;
        var antwortKationenZahl = 0;
        
        var automatik = true;
        var istExperte = false;
        var pkte = 0;
        var zielPunkte = 1000;
        var nr = 0;
        var gameStarted = false;
        var manuellerText = "";
        var challengeErreicht = false;

        function playSuccessSound() {
            var ctx = new (window.AudioContext || window.webkitAudioContext)();
            var osc1 = ctx.createOscillator(); var osc2 = ctx.createOscillator(); var gain = ctx.createGain();
            osc1.connect(gain); osc2.connect(gain); gain.connect(ctx.destination);
            osc1.type = "sine"; osc2.type = "sine"; osc1.frequency.value = 600; osc2.frequency.value = 800;
            gain.gain.setValueAtTime(0.1, ctx.currentTime); gain.gain.exponentialRampToValueAtTime(0.0001, ctx.currentTime + 0.5);
            osc1.start(); osc2.start(); osc1.stop(ctx.currentTime + 0.5); osc2.stop(ctx.currentTime + 0.5);
        }

        function playErrorSound() {
            var ctx = new (window.AudioContext || window.webkitAudioContext)();
            var osc = ctx.createOscillator(); var gain = ctx.createGain();
            osc.connect(gain); gain.connect(ctx.destination); osc.type = "sawtooth"; osc.frequency.value = 200;
            gain.gain.setValueAtTime(0.1, ctx.currentTime); gain.gain.exponentialRampToValueAtTime(0.0001, ctx.currentTime + 0.3);
            osc.start(); osc.stop(ctx.currentTime + 0.3);
        }

        function playApplauseSound() {
            var ctx = new (window.AudioContext || window.webkitAudioContext)();
            var bufferSize = ctx.sampleRate * 1.5; 
            var buffer = ctx.createBuffer(1, bufferSize, ctx.sampleRate);
            var data = buffer.getChannelData(0);
            
            for (var i = 0; i < bufferSize; i++) {
                data[i] = Math.random() * 2 - 1;
            }

            for (var t = 0; t < 1.4; t += 0.08) {
                var noise = ctx.createBufferSource();
                noise.buffer = buffer;

                var filter = ctx.createBiquadFilter();
                filter.type = "bandpass";
                filter.frequency.value = 1200 + Math.random() * 400;
                filter.Q.value = 3.0;

                var gain = ctx.createGain();
                var startVal = 0.15 + Math.random() * 0.1;
                gain.gain.setValueAtTime(startVal, ctx.currentTime + t);
                gain.gain.exponentialRampToValueAtTime(0.001, ctx.currentTime + t + 0.04);

                noise.connect(filter);
                filter.connect(gain);
                gain.connect(ctx.destination);

                noise.start(ctx.currentTime + t);
                noise.stop(ctx.currentTime + t + 0.05);
            }
        }

        window.addEventListener("load", function() {
            var tf = document.getElementById("tippFeld");
            var hi = document.getElementById("hiddenInput");
            
            tf.addEventListener("click", function() {
                if (!automatik) { 
                    hi.focus(); 
                    setTimeout(function() { tf.scrollIntoView({ behavior: 'smooth', block: 'center' }); }, 200);
                }
            });
            hi.addEventListener("input", mobileInputAuswerten);
            poolsAktualisieren();
        });

        function poolsAktualisieren() {
            if (istExperte) {
                var gefilterteEinfacheAnionen = basisAnionen.filter(function(anion) {
                    return anion.name === "Sulfid" || anion.name === "Nitrid" || anion.name === "Phosphid";
                });
                aktuelleAnionen = gefilterteEinfacheAnionen.concat(expertenAnionenVollstaendig);
                aktuelleKationen = basisKationen.concat(expertenKationenVollstaendig);
            } else {
                aktuelleAnionen = basisAnionen;
                aktuelleKationen = basisKationen;
            }
        }

        function wechselLevel() {
            istExperte = !istExperte;
            var text = "Level:<br><b>" + (istExperte ? "Fortgeschritten" : "Basis") + "</b>";
            document.getElementById("levelBtn").innerHTML = text;
            document.getElementById("levelBtnWelcome").innerHTML = text;
            poolsAktualisieren();
            if (gameStarted) {
                if (confirm("Fortschritt zurücksetzen und Level wechseln?")) {
                    gameStarted = false;
                    document.getElementById("gameplay-area").style.display = "none";
                    document.getElementById("welcome-area").style.display = "block";
                } else {
                    istExperte = !istExperte;
                    poolsAktualisieren();
                }
            }
        }

        function wechselAuto() {
            var tf = document.getElementById("tippFeld");
            if (automatik) {
                automatik = false;
                var btnText = "Modus:<br><b>Test</b>";
                document.getElementById("wechsel").innerHTML = btnText;
                document.getElementById("wechselWelcome").innerHTML = btnText;
                tf.classList.add("testmodus-aktiv");
            } else {
                automatik = true;
                var btnText = "Modus:<br><b>Lernen</b>";
                document.getElementById("wechsel").innerHTML = btnText;
                document.getElementById("wechselWelcome").innerHTML = btnText;
                tf.classList.remove("testmodus-aktiv");
            }
            document.getElementById("punkte-display").style.visibility = automatik ? "hidden" : "visible";
            
            if (gameStarted) {
                nr = 0; neueFrage(); frageSchreiben();
            }
        }

        function mobileInputAuswerten(e) {
            if (automatik) return;
            var val = e.target.value; var formatiert = "";
            for (var i = 0; i < val.length; i++) {
                var char = val.charAt(i);
                if (char >= '0' && char <= '9') { formatiert += "<sub>" + char + "</sub>"; } 
                else { formatiert += char; }
            }
            manuellerText = formatiert;
            document.getElementById("tippFeld").innerHTML = manuellerText;
        }

        function drawFormel(isKation, aktuellesIon) {
            var element = document.getElementById('canvas'); var context = element.getContext('2d');
            context.textBaseline = 'middle';
            var htmlText = aktuellesIon.formel;
            var ladung = aktuellesIon.ladung; var dy = Math.abs(ladung) * 40;
            var x = 0; var y = 0;

            if (!isKation) {
                x = 192; y = antwortAnionenZahl * dy;
                context.fillStyle = "#BBBBFF"; context.strokeStyle = "#4444FF";
            } else {
                x = 0; y = antwortKationenZahl * dy;
                context.fillStyle = "#FFBBBB"; context.strokeStyle = "#FF4444";
            }
            context.fillRect(x + 2, y + 2, 192 - 4, dy - 4); context.strokeRect(x + 2, y + 2, 192 - 4, dy - 4);
            
            context.fillStyle = isKation ? "#600000" : "#000060";
            var centerY = y + dy / 2;
            
            var tempDiv = document.createElement("div");
            tempDiv.innerHTML = htmlText;
            
            var totalWidth = 0;
            for (var i = 0; i < tempDiv.childNodes.length; i++) {
                var node = tempDiv.childNodes[i];
                if (node.nodeType === Node.TEXT_NODE) {
                    context.font = 'bold 20px sans-serif';
                    totalWidth += context.measureText(node.textContent).width;
                } else if (node.nodeType === Node.ELEMENT_NODE) {
                    context.font = 'bold 13px sans-serif';
                    totalWidth += context.measureText(node.textContent).width + 1;
                }
            }
            
            var currentX = x + (96 - totalWidth / 2);
            for (var i = 0; i < tempDiv.childNodes.length; i++) {
                var node = tempDiv.childNodes[i];
                if (node.nodeType === Node.TEXT_NODE) {
                    context.font = 'bold 20px sans-serif';
                    context.fillText(node.textContent, currentX, centerY);
                    currentX += context.measureText(node.textContent).width;
                } else if (node.nodeType === Node.ELEMENT_NODE) {
                    if (node.tagName.toLowerCase() === 'sub') {
                        context.font = 'bold 13px sans-serif';
                        context.fillText(node.textContent, currentX, centerY + 8);
                        currentX += context.measureText(node.textContent).width + 1;
                    } else if (node.tagName.toLowerCase() === 'sup') {
                        context.font = 'bold 13px sans-serif';
                        context.fillText(node.textContent, currentX, centerY - 9);
                        currentX += context.measureText(node.textContent).width + 1;
                    }
                }
            }
        }

        function textAusgabe(s, isSuccess) {
            var tf = document.getElementById("titelFeld"); tf.innerHTML = s;
            tf.style.color = isSuccess === true ? "#00CC00" : (isSuccess === false ? "#FF3333" : "#000000");
            tf.tabIndex = -1; tf.focus();
            tf.scrollIntoView({ behavior: 'smooth', block: 'nearest' });
        }

        function punkte(i) { 
            if (automatik) return; 
            
            pkte = pkte + i; 
            if(pkte < 0) pkte = 0;
            document.getElementById("pkte").innerHTML = pkte.toString(); 
            
            if (pkte >= zielPunkte && !challengeErreicht) {
                challengeErreicht = true;
                playApplauseSound();
                
                setTimeout(function() {
                    if (!istExperte) {
                        alert("Glückwunsch! Du hast das Challenge-Ziel von 1000 Punkten erreicht!\n\nProbier jetzt mal den Fortgeschrittenen-Modus aus!");
                    } else {
                        alert("Großartig! Du hast das Challenge-Ziel von 1000 Punkten im Expertenlevel geknackt!");
                    }
                }, 400);
            }
        }

        function formelPruefen() {
            if (antwortAnionenZahl < frageAnionenZahl || antwortKationenZahl < frageKationenZahl) {
                playErrorSound(); textAusgabe("Du hast noch nicht genug Ionen gewählt.", false); punkte(-50);
            } else if ((antwortKationenZahl == frageKationenZahl) && (antwortAnionenZahl == frageAnionenZahl)) {
                playSuccessSound(); textAusgabe("Super gelöst! Klicke auf 'Weiter'.", true); punkte(100);
            }
        }

        function entferneTags(htmlString) {
            return htmlString.replace(/<sup>.*?<\/sup>/g, '').replace(/<span.*?<\/span>/g, '');
        }

        function baueTeilFormel(ion, zahl, farbKlasse) {
            var basis = entferneTags(ion.formel);
            var klammerKlasse = farbKlasse ? ' class="' + farbKlasse + '"' : '';
            
            if (zahl > 1 && ion.molekuel) {
                return "(" + basis + ")<sub" + klammerKlasse + ">" + zahl + "</sub>";
            } else if (zahl > 1) {
                return basis + "<sub" + klammerKlasse + ">" + zahl + "</sub>";
            }
            return basis;
        }

        function autoFormel() {
            var kat = antwortKationenZahl > 0 ? baueTeilFormel(frageKation, antwortKationenZahl, "kat-idx") : "";
            var ani = antwortAnionenZahl > 0 ? baueTeilFormel(frageAnion, antwortAnionenZahl, "ani-idx") : "";
            
            document.getElementById("tippFeld").innerHTML = kat + ani;
            if (antwortPruefen() === 1) { playSuccessSound(); textAusgabe("Klasse gemacht! Das ist absolut richtig.", true); }
        }

        function formel() {
            return document.getElementById("tippFeld").innerHTML.replace(/ class=".*?"/g, '').trim();
        }

        function antwortPruefen() {
            var eing = formel();
            if (eing != "") {
                var zielKat = baueTeilFormel(frageKation, frageKationenZahl, null);
                var zielAni = baueTeilFormel(frageAnion, frageAnionenZahl, null);
                var zielFormel = (zielKat + zielAni).trim();
                
                var eingBereinigt = eing.replace(/\s+/g, '').replace(/<sub\s*>/g, '<sub>').replace(/<\/sub\s*>/g, '</sub>');
                var zielBereinigt = zielFormel.replace(/\s+/g, '').replace(/<sub\s*>/g, '<sub>').replace(/<\/sub\s*>/g, '</sub>');
                
                if (zielBereinigt == eingBereinigt) return 1;
                if (zielBereinigt.toLowerCase() == eingBereinigt.toLowerCase()) return 2;
                return 0;
            }
            if (antwortKationenZahl == frageKationenZahl && antwortAnionenZahl == frageAnionenZahl) return 3;
            return 0;
        }

        function naechsteFrage() {
            var status = antwortPruefen();
            if (status === 1) {
                playSuccessSound(); textAusgabe("Klasse gemacht! Das ist absolut richtig.", true); punkte(100);
                setTimeout(function() { neueFrage(); frageSchreiben(); }, 1500);
            } else if (status === 2) {
                playErrorSound(); textAusgabe("Schau noch einmal genau hin! Achte auf die korrekte Groß- und Kleinschreibung sowie die Klammern.", false); punkte(-50);
            } else if (status === 3 && !automatik) {
                playErrorSound(); textAusgabe("Die Ionen wurden korrekt gewählt. Bitte tippe nun noch die fertige Verhältnisformel in das Eingabefeld ein.", false);
            } else {
                playErrorSound();
                if (automatik) { formelPruefen(); } 
                else { textAusgabe("Leider nicht richtig! Versuche es noch einmal.", false); punkte(-100); }
            }
        }

        function updateZahlenAnzeige() {
            document.getElementById("kationenZahlLinks").innerHTML = antwortKationenZahl > 0 ? antwortKationenZahl : "";
            document.getElementById("anionenZahlRechts").innerHTML = antwortAnionenZahl > 0 ? antwortAnionenZahl : "";
        }

        function auswertung(isKation, index) {
            var gewaehltesIon = isKation ? aktuelleKationen[index] : aktuelleAnionen[index];
            var korrekteArt = isKation ? (frageKation === gewaehltesIon) : (frageAnion === gewaehltesIon);

            if (!korrekteArt) {
                playErrorSound(); textAusgabe("Das " + gewaehltesIon.name + "-Ion brauchst du für diese Verhältnisformel nicht!", false); punkte(-10);
            } else {
                if (!isKation) {
                    if (frageAnionenZahl > antwortAnionenZahl) { drawFormel(false, gewaehltesIon); antwortAnionenZahl++; } 
                    else { playErrorSound(); textAusgabe("Du hast bereits genug Anionen gewählt!", false); }
                } else {
                    if (frageKationenZahl > antwortKationenZahl) { drawFormel(true, gewaehltesIon); antwortKationenZahl++; } 
                    else { playErrorSound(); textAusgabe("Du hast bereits genug Kationen gewählt!", false); }
                }
            }
            updateZahlenAnzeige();
            if (automatik) { autoFormel(); } 
            else { document.getElementById("tippFeld").innerHTML = manuellerText; }
        }

        function frageSchreiben() {
            var kationName = frageKation.name;
            var anionName = frageAnion.name;
            /* Automatische Anpassung für korrekte Wortbildung (z. B. Silber(I)-chlorid statt Silber(I)-Chlorid) */
            var s = kationName.endsWith("-") ? kationName + anionName.toLowerCase() : kationName + anionName.toLowerCase();
            
            document.getElementById("titel").innerHTML = s;
            textAusgabe("Setze die Verhältnisformel zusammen:", null);
            document.getElementById("tippFeld").innerHTML = ""; manuellerText = ""; document.getElementById("hiddenInput").value = "";
            updateZahlenAnzeige();
        }

        function neueFrage() {
            var aniIndex = Math.floor(Math.random() * aktuelleAnionen.length);
            var katIndex = Math.floor(Math.random() * aktuelleKationen.length);
            frageAnion = aktuelleAnionen[aniIndex];
            frageKation = aktuelleKationen[katIndex];

            frageAnionenZahl = Math.abs(frageKation.ladung);
            frageKationenZahl = Math.abs(frageAnion.ladung);
            
            if (frageAnionenZahl == frageKationenZahl && frageAnionenZahl != 1) {
                frageAnionenZahl = 1; frageKationenZahl = 1;
            }
            
            antwortAnionenZahl = 0; antwortKationenZahl = 0;
            var canvas = document.getElementById("canvas"); canvas.getContext('2d').clearRect(0, 0, canvas.width, canvas.height);
            nr++; document.getElementById("nr").innerHTML = nr.toString();
        }

        function initCanvas() {
            var canvas = document.getElementById('canvas'); var ctx = canvas.getContext('2d');
            var dpr = window.devicePixelRatio || 1;
            canvas.width = 384 * dpr; canvas.height = 240 * dpr; ctx.scale(dpr, dpr);
        }

        function start() {
            document.getElementById("welcome-area").style.display = "none";
            document.getElementById("gameplay-area").style.display = "block";

            initCanvas();

            gameStarted = true; nr = 0; pkte = 0; challengeErreicht = false;
            document.getElementById("pkte").innerHTML = pkte.toString();
            
            document.getElementById("punkte-display").style.visibility = automatik ? "hidden" : "visible";
            
            poolsAktualisieren(); neueFrage(); frageSchreiben();
            document.getElementById("pruefen").style.display = "block";
            
            var kationenDiv = document.getElementById("kationen");
            var anionenDiv = document.getElementById("anionen");
            kationenDiv.innerHTML = ""; anionenDiv.innerHTML = "";

            for (var i = 0; i < aktuelleKationen.length; i++) {
                kationenDiv.innerHTML += '<button onClick="auswertung(true, ' + i + ')">' + aktuelleKationen[i].formel + '</button>';
            }
            for (var i = 0; i < aktuelleAnionen.length; i++) {
                anionenDiv.innerHTML += '<button onClick="auswertung(false, ' + i + ')">' + aktuelleAnionen[i].formel + '</button>';
            }
        }
    </script>
</head>
<body>

<div class="game-container">

    <!-- Startseite -->
    <div id="welcome-area">
        <div class="menu-row">
            <button class="big-btn" id="wechselWelcome" onClick="wechselAuto()">Modus:<br><b>Lernen</b></button>
            <button class="big-btn" id="levelBtnWelcome" onClick="wechselLevel()">Level:<br><b>Basis</b></button>
        </div>

        <div class="welcome-screen">
            <h2>Salze: Verhältnisformel-Trainer</h2>
            <p>Gleiche die Ionenladungen aus und finde die richtige Verhältnisformel.</p>
            <p>Erreiche 1000 Punkte im Testmodus zum Gewinnen!</p>
            <button class="main-start-btn" onClick="start()">Spiel starten →</button>
        </div>
    </div>

    <!-- Spielbereich -->
    <div id="gameplay-area">
        <div class="menu-row">
            <button class="big-btn" id="start" onClick="start()">Neu starten</button>
            <button class="big-btn" id="wechsel" onClick="wechselAuto()">Modus:<br><b>Lernen</b></button>
            <button class="big-btn" id="levelBtn" onClick="wechselLevel()">Level:<br><b>Basis</b></button>
        </div>

        <div class="header-row">
            <div>Salz-Nr. <span id="nr">1</span></div>
            <div id="titelFeld">Setze die Verhältnisformel zusammen:</div>
            <div id="punkte-display">Punkte: <span id="pkte">0</span> / 1000</div>
        </div>

        <div style="margin: 5px 0;">
            <span id="titel" style="font-size: 2em; font-weight: bold; display: block; min-height: 35px; color: #333;"></span>
        </div>

        <div class="block-display-row">
            <div class="ion-count-box" id="kationenZahlLinks" style="color: #FF4444;"></div>
            <div class="canvas-container">
                <canvas id="canvas"></canvas>
            </div>
            <div class="ion-count-box" id="anionenZahlRechts" style="color: #4444FF;"></div>
        </div>

        <div class="formula-section-row">
            <div></div> 
            <div class="canvas-container">
                <div class="formula-wrapper">
                    <div id="tippFeld"></div>
                    <input type="text" id="hiddenInput" autocomplete="off" autocorrect="off" autocapitalize="none" spellcheck="false">
                </div>
            </div>
            <button class="small-next-btn" id="pruefen" onClick="naechsteFrage()">Weiter</button>
        </div>

        <div class="main-grid">
            <div class="buttons-wrapper">
                <div id="kationen"></div>
                <div id="anionen"></div>
            </div>
        </div>
    </div>

</div>

</body>
</html>
