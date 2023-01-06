Add onload on body attribute<br>
 body onload="Load()"

Add div with id (e.g. Load)
 div id="Load"
    h1 Loading... /h1
/div

Add z-index at style
#Load {
    z-index:1000;
    background:rgba(255,255,255,0.9);
}

Add script at the end of body
...
    script

    /script
/body

Or
...
    script src="load.js"  /script
/body

Fill the script with script that I've put on "load.js"

Done
