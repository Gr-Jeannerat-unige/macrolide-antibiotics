de2
<script type="text/javascript" src="src/JSmol.min.js"></script>
<script type="text/javascript" src="src/Jmol2.js"></script>
<script type="text/javascript">
Jmol.Info = {
      
      jarPath: "src",
      jarFile: "JmolApplet0.jar",
      j2sPath: "src/j2s",
      use: "HTML5", // could be JAVA or HTML5
			disableJ2SLoadMonitor: false,
			disableInitialConsole: true
}

document.getElementById("info").reset();

function sync() {
 var syncing = document.getElementById("drive").checked
 var s = (syncing ? "sync * on;sync * \"set syncMouse TRUE\"": "sync * off")
 jmolScript(s, "A");
}
</script>
<script>
jmolApplet(400,"load data/cholesterol-3D.sdf;cartoon on;color cartoon structure;;rotate z 118.48; rotate y 117.66; rotate z -47.64;;", "A");
</script>
<script>
jmolApplet(400,"load data/ergosterol-3D.sdf;calculate structure;cartoon on;color cartoon structure;rotate z -113.86; rotate y 135.11; rotate z -93.93;", "B");
</script>

<a href='javascript:jmolScript("reset; rotate z 33.34; rotate y 125.99; rotate z -67.45;select atomno = 41;color [0,128,0]", "A")'>Side view cholesterol</a>
<a href='javascript:jmolScript("reset; rotate z -179.67; rotate y 93.62; rotate z -93.8;", "B")'>Side view ergosterol</a>

<a href='javascript:jmolScript("reset;rotate z 118.48; rotate y 117.66; rotate z -47.64;select atomno = 41;color [0,128,0]", "A")'>Reset cholesterol</a>


<a href='javascript:jmolScript("reset; rotate z -113.86; rotate y 135.11; rotate z -93.93;", "B")'>Reset ergosterol</a>
<a href='javascript:jmolScript("select atomno = 41;color [0,128,0]", "A")'>Highlight Hax(7)</a>

Set 
<a href='javascript:jmolScript("script APPLET * \"background white\"","A")'> white </a>
 or
<a href='javascript:jmolScript("script APPLET * \"background black\"","A")'> black </a>background.
<br><br>
<a href='javascript:jmolScript("console","A")'>Cholesterol console</a>
<br><br>
<a href='javascript:jmolScript("console","B")'>Ergosterol console</a>
<pre>
<code>
print script("show orientation")
</code>
</pre>



