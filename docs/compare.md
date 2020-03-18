test l3


info : http://wiki.jmol.org/index.php/Jmol_Applet_Deployment_Local


<script type='text/javascript' src='https://chemapps.stolaf.edu/jmol/files/JSmolMin2.js'></script>
<script type='text/javascript' language='javascript'>
  Jmol.Info.j2sPath = 'https://chemapps.stolaf.edu/jmol/jsmol/j2s';
  Jmol.Info.serverURL='https://chemapps.stolaf.edu/jmol/jsmol/php/jsmol.php';
  jmolInitialize('https://chemapps.stolaf.edu/jmol/files', true);
  jmolApplet(['400','200'],"set antialiasdisplay\;load https://gr-jeannerat-unige.github.io/macrolide-antibiotics/data/cholesterol-3D.sdf;",'0');
  Jmol.getApplet("myJmol", myInfo);
  Jmol.jmolButton(myJmol,"spacefill on", "display as vdW spheres");
  Jmol.jmolCheckbox(myJmol, 'display add _H', 'hide add _H', 'hydrogen', true, 'light');
</script>
<div style='width:600px'>cholesterol local model <script>jmolCheckbox('spin on','spin off','spin on/off')</script></div>
<div style='width:600px'>try:  <script>jmolCheckbox("spacefill off","spacefill on","toggle display as spheres")</script></div>
<div style='width:600px'>try2:  <script>jmolButton("spacefill on", "display as vdW spheres");</script></div>


<script type='text/javascript' src='https://chemapps.stolaf.edu/jmol/files/JSmolMin2.js'></script>
<script type='text/javascript' language='javascript'>
  Jmol.Info.j2sPath = 'https://chemapps.stolaf.edu/jmol/jsmol/j2s';
  Jmol.Info.serverURL='https://chemapps.stolaf.edu/jmol/jsmol/php/jsmol.php';
  jmolInitialize('https://chemapps.stolaf.edu/jmol/files', true);
  jmolApplet(['400','200'],"set antialiasdisplay\;load https://gr-jeannerat-unige.github.io/macrolide-antibiotics/data/ergosterol-3D.sdf;",'0');
  Jmol.getApplet("myJmol", myInfo);
  Jmol.jmolButton(myJmol,"spacefill on", "display as vdW spheres");
  Jmol.jmolCheckbox(myJmol, 'display add _H', 'hide add _H', 'hydrogen', true, 'light');
</script>
<div style='width:600px'>ergosterol local model <script>jmolCheckbox('spin on','spin off','spin on/off')</script></div>
<div style='width:600px'>try:  <script>jmolCheckbox("spacefill off","spacefill on","toggle display as spheres")</script></div>
<div style='width:600px'>try2:  <script>jmolButton("spacefill on", "display as vdW spheres");</script></div>
