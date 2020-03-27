## Cholesterol and ergosterol

Sterols are found in the cell membranes of many living organisms. [Cholesterol](https://en.wikipedia.org/wiki/Cholesterol) is found in cell membranes of animals, [ergosterol](https://en.wikipedia.org/wiki/Ergosterol) in fungi and protozoa, and [phytosterols](https://en.wikipedia.org/wiki/Phytosterol) in plants.

## Relevance of macrolide antibiotics

Because ergosterol is present in cell membranes of fungi, yet absent in those of animals, it is a useful target for antifungal drugs.<sup>[Ref](https://en.wikipedia.org/wiki/Ergosterol#Target_for_antifungal_drugs)</sup> Macrolide antibiotics such as Amphotericin B are target of ergosterol.<sup>[Ref](https://academic.oup.com/jac/article/49/suppl_1/7/2473430)</sup>

## Differences

Cholesterol and ergosterol have similar shapes, but the Hax(7) which is pointing out of the plane of cholesterol is not present in ergosterol because it has a sp<sub>2</sub> hybridisation. This hydrogen atom can be <a href='javascript:jmolScript("select atomno = 41;color [0,255,0]", "A")'>highlighted</a> in green in the structures of Table 1. The <a href='javascript:jmolScript("select atomno = 30, atomno = 48, atomno = 50;color [0,127,127]", "A")'>other three additional</a> H of cholesterol are probably not as important. Note the additional <a href='javascript:jmolScript("select atomno = 65, atomno = 66, atomno = 67;color [127,127,0]", "B")'>methyl</a> of ergosterol at the end of the side chain.

<script type="text/javascript" src="src/JSmol.min.js"></script>
<script type="text/javascript">
Cholest = {
    script: "set antialiasDisplay true;load $cholesterol;cartoon on;color cartoon structure;;rotate z 118.48; rotate y 117.66; rotate z -47.64;",
    width:350,      
    j2sPath: "src/j2s",   
    disableJ2SLoadMonitor: false,
    isableInitialConsole: true
}
Ergost = {
    script: "set antialiasDisplay true;load $ergosterol;cartoon on;color cartoon structure;;rotate z 118.48; rotate y 117.66; rotate z -47.64;",
    width:350,      
    j2sPath: "src/j2s",   
    disableJ2SLoadMonitor: false,
    isableInitialConsole: true
}
document.getElementById("info").reset()
function sync() {
 var syncing = document.getElementById("drive").checked
 var s = (syncing ? "sync * on;sync * \"set syncMouse TRUE\"": "sync * off")
 //jmolScript(s, "A");
 Jmol.script(JmolAppletA,s);
}
</script>

|Cholesterol|Ergosterol|
|----------|-----------|
| <center><img src="data/Cholesterol_2D.svg.png" alt="cholesterol" width="200" /></center> | <center><img src="data/Ergosterol_2D.svg.png" alt="ergosterol" width="200" /></center>  |
| <script>Jmol.getApplet("JmolAppletA",Cholest);</script> | <script>Jmol.getApplet("JmolAppletB",Ergost);</script> |
| View <a href='javascript:Jmol.script("JmolAppletA","reset; rotate z 33.34; rotate y 125.99; rotate z -67.45;select atomno = 41;color [0,255,0]")'>side</a>/<a href='javascript:Jmol.script("JmolAppletA","reset;rotate z 118.48; rotate y 117.66; rotate z -47.64;select atomno = 41;color [0,255,0]")'>top</a> | View <a href='javascript:Jmol.script("JmolAppletB","reset; rotate z -179.67; rotate y 93.62; rotate z -93.8;")'>side</a>/<a href='javascript:Jmol.script("JmolAppletB","reset; rotate z -113.86; rotate y 135.11; rotate z -93.93;")'>top</a> |
View <code><a href='javascript:Jmol.script("JmolAppletA","reset; rotate z 33.34; rotate y 125.99; rotate z -67.45;select atomno = 41;color [0,255,0]");javascript:Jmol.script("JmolAppletB","reset; rotate z -179.67; rotate y 93.62; rotate z -93.8;")'>side</a></code>/<code><a href='javascript:jmolScript("reset;rotate z 118.48; rotate y 117.66; rotate z -47.64;select atomno = 41;color [0,255,0]", "A");javascript:Jmol.script("JmolAppletB","reset; rotate z -113.86; rotate y 135.11; rotate z -93.93;")'>top</a></code>.
Spin
<code><a href='Jmol.script("JmolAppletA","spin on");javascript:Jmol.script("JmolAppletB","spin on")'>on</a></code> /
<code><a href='javascript:script("JmolAppletA","spin off");javascript:script("JmolAppletB","spin off")'>off</a></code>.

Highlight Hax(7) cholesterol <code><a href='javascript:Jmol.script("JmolAppletA","select atomno = 41;color [0,255,0]")'>on</a></code>/
<code><a href='javascript:Jmol.script("JmolAppletA","select atomno = 41;color [255,255,255]")'>off</a></code>.
Set
<code><a href='javascript:Jmol.script("JmolAppletA","script APPLET * \"background white\"")'> white</a></code>/
<code><a href='javascript:Jmol.script("JmolAppletA","script APPLET * \"background black\"")'> black</a></code> background.
<br><br>
<a href='javascript:Jmol.script("JmolAppletA","console")'>Cholesterol</a>/
<a href='javascript:Jmol.script("JmolAppletB","console")'>ergosterol console</a>.
<code>print script("show orientation")</code>
[Version of this page with synchronized rotation](page2.html)
