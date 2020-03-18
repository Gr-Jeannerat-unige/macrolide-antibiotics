

info : [info1](http://wiki.jmol.org/index.php/Jmol_Applet_Deployment_Local)

[info2](https://chemapps.stolaf.edu/jmol/jmol.php)

[info3](https://www.macinchem.org/reviews/jsmol/jsmol.php)


<script type='text/javascript' src='https://chemapps.stolaf.edu/jmol/files/JSmolMin2.js'></script>
<script type='text/javascript' language='javascript'>
  Jmol.Info.j2sPath = 'https://chemapps.stolaf.edu/jmol/jsmol/j2s';
  Jmol.Info.serverURL='https://chemapps.stolaf.edu/jmol/jsmol/php/jsmol.php';
  jmolInitialize('https://chemapps.stolaf.edu/jmol/files', true);
  jmolApplet(['400','200'],"set antialiasdisplay\;load https://gr-jeannerat-unige.github.io/macrolide-antibiotics/data/cholesterol-3D.sdf;",'0');
</script>
<div style='width:600px'>cholesterol local model <script>jmolCheckbox('spin on','spin off','spin on/off')</script></div>
<div style='width:600px'>Option:  <script>jmolCheckbox("spacefill off","spacefill on","toggle display as spheres")</script></div>
<div style='width:600px'>  <script>jmolButton("spacefill on", "display as vdW spheres");</script></div>
<div style='width:600px'><script>jmolButton("select atomno = 41;color [0,128,0]", "Highlight");</script> key difference with ergosterol</div>
