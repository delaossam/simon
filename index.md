<head>
  <h1>Die beste Seite der Welt</h1>
</head>
<body>
		<h1 align="center">Willkommen</h1>
		<h3 align="center">Hier kannst du so schnell wie nie vorher einen passenden Urlaubsort finden.</h3>
           <img src="bild1.jpg" width="550" height="750">
           <h4>
             Dieser Strand ist etwas ganz besonderes da er so schön und so blau ist.<br>
             Er ist in Sardinien.<br>
             Hinter ihm haust eine sehr hässliche Hotelanlage.
           </h4>
           <p> Würdest du gerne in der Hotelanlage wohnen?<br>
           <input type="radio" name="r1"  onclick="alert('Du Umweltverschmutzer!')" value="Ja">Ja<br>
           <input type="radio" name="r1"  onclick="alert('Gute Entscheidung...')" value="Nein">Nein<br>
           <input type="radio" name="r1"  onclick="alert('Ja oder Nein?')" value="Vielleicht">Vielleicht<br>
           <button onclick="alert('Äähhh... Nö :^)')">Hier gehts zu Bildern vom Hotel</button>
           <form action="select.htm">
             <p>
              Wie wollen Sie anreisen?
             </p>
             <select name="Anreise" size="5" onchange="alert(this.form.Anreise.options[this.form.Anreise.selectedIndex].value)">
               <option value="Gut, sehr Umweltfreundlich.">mit dem Zug</option>
               <option value="Du CO2 Schleuder!">mit dem Schiff</option>
               <option value="Schäm dich!">mit dem Auto</option>
               <option value="Ist das dein Ernst? Dafür wirst du büßen müssen!">mit dem Flugzeug</option>
               <option value="Du bist auf dem richtigen Weg!">mit dem Bus</option>
             </select>
            </form>
            <button onclick="alert('Du hast echt Hoffnungen das es noch ein zweites Hotel zur Auswahl gibt...')">Hier gehts zu weiteren möglichen Hotels
            </button>
