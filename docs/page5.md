[Version of this page with synchronized rotation](page2.html)

<script type="text/javascript" src="src/JSmol.min.js"></script>
<script type="text/javascript" src="src/Jmol2.js"></script>
<script type="text/javascript">
Jmol.Info = {
      jarPath: "src",
      jarFile: "JmolApplet0.jar",
      j2sPath: "src/j2s",
      use: "HTML5", 
			disableJ2SLoadMonitor: false,
			disableInitialConsole: true
}
document.getElementById("info").reset()
function sync() {
 var syncing = document.getElementById("drive").checked
 var s = (syncing ? "sync * on;sync * \"set syncMouse TRUE\"": "sync * off")
 jmolScript(s, "A");
}
</script>

|Cholesterol|Ergosterol|
|-----|-----|
|<script>jmolApplet(400,"load data/cholesterol-3D.sdf;cartoon on;color cartoon structure;;rotate z 118.48; rotate y 117.66; rotate z -47.64;;", "A");</script>|<script>jmolApplet(400,"load data/ergosterol-3D.sdf;calculate structure;cartoon on;color cartoon structure;rotate z -113.86; rotate y 135.11; rotate z -93.93;", "B");</script>|
|View <a href='javascript:jmolScript("reset; rotate z 33.34; rotate y 125.99; rotate z -67.45;select atomno = 41;color [0,255,0]", "A")'>side</a>/<a href='javascript:jmolScript("reset;rotate z 118.48; rotate y 117.66; rotate z -47.64;select atomno = 41;color [0,255,0]", "A")'>top</a>|View <a href='javascript:jmolScript("reset; rotate z -179.67; rotate y 93.62; rotate z -93.8;", "B")'>side</a>/<a href='javascript:jmolScript("reset; rotate z -113.86; rotate y 135.11; rotate z -93.93;", "B")'>top</a>|


View <a href='javascript:jmolScript("reset; rotate z 33.34; rotate y 125.99; rotate z -67.45;select atomno = 41;color [0,255,0]", "A");javascript:jmolScript("reset; rotate z -179.67; rotate y 93.62; rotate z -93.8;", "B")'>side</a>/<a href='javascript:jmolScript("reset;rotate z 118.48; rotate y 117.66; rotate z -47.64;select atomno = 41;color [0,255,0]", "A");javascript:jmolScript("reset; rotate z -113.86; rotate y 135.11; rotate z -93.93;", "B")'>top</a>

Highlight Hax(7) cholesterol <a href='javascript:jmolScript("select atomno = 41;color [0,255,0]", "A")'>on</a>
<a href='javascript:jmolScript("select atomno = 41;color [255,255,255]", "A")'>off</a>

Set 
<a href='javascript:jmolScript("script APPLET * \"background white\"","A")'> white </a>
 or
<a href='javascript:jmolScript("script APPLET * \"background black\"","A")'> black </a>background.
<br><br>
<a href='javascript:jmolScript("console","A")'>Cholesterol </a>/
<a href='javascript:jmolScript("console","B")'>ergosterol console</a>.
print script("show orientation")




