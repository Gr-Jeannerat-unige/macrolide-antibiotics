## Eau en 3D
Patience ! Certains boutons réagissement un peu lentement...
<script type="text/javascript" src="src/JSmol.min.js"></script>
<script type="text/javascript">
Info = {
    script: "set antialiasDisplay true;load molecules/water.xodydata;",
    width:600,      
    height:500,      
    j2sPath: "src/j2s",   
    disableJ2SLoadMonitor: false,
    isableInitialConsole: true
}
</script>

<script>Jmol.getApplet("JmolAppletA",Info);</script>

Spin <a href='javascript:Jmol.script(JmolAppletA,"spin y 5;");'>on</a>/<a href='javascript:Jmol.script(JmolAppletA,"spin off;");'>off</a>.

    <a href='javascript:Jmol.script(JmolAppletA,"select all;isosurface vdw;");'>Surface</a>
   Charges <a href='javascript:Jmol.script(JmolAppletA,"select atomno <60 ;;if ({atomno < 10}.partialcharge == 0){calculate partialcharge};isosurface vdw map mep;");'> 20H2O</a>/ 
        <a href='javascript:Jmol.script(JmolAppletA,"select  all;;if ({atomno < 10}.partialcharge == 0){calculate partialcharge};isosurface vdw map mep;");'>all</a>/ 
        <a href='javascript:Jmol.script(JmolAppletA,"select all;isosurface off;");'>off</a>.

Select <a href='javascript:Jmol.script(JmolAppletA,"select atomno >30 ;;select atomno <=30 ;spacefill")'>on</a>/<a href='javascript:Jmol.script(JmolAppletA,"select all ;spacefill off")'>off</a>. 
