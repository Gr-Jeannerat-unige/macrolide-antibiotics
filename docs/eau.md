## Eau en 3D
Patience... chargement et boutons (en bas de page) un peu lents...
Rotation et zoom possibles.
<script type="text/javascript" src="src/JSmol.min.js"></script>
<script type="text/javascript">
Info = {
    script: "set antialiasDisplay true;load molecules/water.xodydata;zoom 180;",
    j2sPath: "src/j2s",   
    disableJ2SLoadMonitor: false,
    isableInitialConsole: true
}
</script>
<script>Jmol.getApplet("JmolAppletA",Info);</script>
Spin <a href='javascript:Jmol.script(JmolAppletA,"spin y 5;");'>on</a> / <a href='javascript:Jmol.script(JmolAppletA,"spin off;");'>off</a>. SpaceFill <a href='javascript:Jmol.script(JmolAppletA,"select atomno >30 ;;select atomno <=30 ;spacefill")'>on</a> / <a href='javascript:Jmol.script(JmolAppletA,"select all ;spacefill off")'>off</a>. 

Charges <a href='javascript:Jmol.script(JmolAppletA,"select atomno <60 ;;if ({atomno < 10}.partialcharge == 0){calculate partialcharge};isosurface vdw map mep;");'> 20 H<sub>2</sub>O</a> / <a href='javascript:Jmol.script(JmolAppletA,"select  all;;if ({atomno < 10}.partialcharge == 0){calculate partialcharge};isosurface vdw map mep;");'>all</a> / <a href='javascript:Jmol.script(JmolAppletA,"select all;isosurface off;");'>off</a>.

Observez les charges et l'orientation des molécules d'eau.