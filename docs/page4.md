test 5

<script type='text/javascript' src='https://chemapps.stolaf.edu/jmol/files/JSmolMin2.js'></script>
<script type='text/javascript' language='javascript'>
  Jmol.Info.j2sPath = 'https://chemapps.stolaf.edu/jmol/jsmol/j2s';
  Jmol.Info.serverURL='https://chemapps.stolaf.edu/jmol/jsmol/php/jsmol.php';
  jmolInitialize('https://chemapps.stolaf.edu/jmol/files', true);
  jmolApplet(['400','200'],"set antialiasdisplay\;load https://gr-jeannerat-unige.github.io/macrolide-antibiotics/data/cholesterol-3D.sdf;",'0');
  Jmol.getApplet("myJmol", myInfo);
  Jmol.jmolButton(myJmol,"spacefill on", "display as vdW spheres");
  Jmol.jmolCheckbox(myJmol, 'display add _H', 'hide add _H', 'hydrogen', true, 'light');
Jmol.jmolHtml('<br>');
Jmol.jmolCheckbox(myJmol, 'display add (not _H)', 'hide add (not _H)', 'heavy atoms', true, 'heavy');
Jmol.jmolHtml('<div style="margin-left:3ex;">');
Jmol.jmolCheckbox(myJmol, 'display add _C', 'hide add _C', 'carbon', true, 'carb');
Jmol.jmolHtml('<br>');
Jmol.jmolCheckbox(myJmol, 'display add _O', 'hide add _O', 'oxygen', true, 'oxy');
Jmol.jmolHtml('<br>');
Jmol.jmolCheckbox(myJmol, 'display add _N', 'hide add _N', 'nitrogen', true, 'nitro');
Jmol.jmolHtml('</div>');
</script>
<div style='width:600px'>cholesterol local model <script>jmolCheckbox('spin on','spin off','spin on/off')</script></div>
<div style='width:600px'>try:  <script>jmolCheckbox("spacefill off","spacefill off","toggle display as spheres")</script></div>
<div style='width:600px'>try2:  <script>jmolButton("spacefill on", "display as vdW spheres");</script></div>
