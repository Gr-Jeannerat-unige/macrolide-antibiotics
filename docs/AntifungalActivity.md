# A new proposition of mecanism of antifungal activity
Since the X-ray structure (of ...) was published as hemiacetal in 1973?, the fact they may be open was never mentionned again.
We believe that opening the hemiacetal was neglected and explains the abscence of good model of the selectivity and structure of the complexes.
TO BE WORKED ON....

## Opening of the hemiactal

Hemiacetals (left in B) are not very stable. The C-O bond can easily break to form a ketone and an alcool (right in B). This is faciliated by the presence of a OH group, or other catalysts exchanging protons. The two have almost the same energy (1.2 kcal difference), and the barrier is less than 20 kcal. (Calculated using B3LYP...)

![333333](images/Fig3.png)

In cyclic coumpounds, hemiacetals are usually at equilibrium with their open form. For example, glucose undergoes [mutarotation](https://en.wikipedia.org/wiki/Glucose#Mutarotation), a process during which the cyclic &alpha;-glucose (36%) and &beta;-glucose (64%) - two hemiacetals) slowly exchange via the open "*keto*" form (< 1%).

## Opening macrolides antibiotics

In macrolide antibiotics of the amphotericin family, there is always an OH group making it possible to form the stabilizing 6-membered ring. See carbons 1 in the Figure below. Also on 5...

<img src="images/open_hemi.png" alt="drawing" width="500"/>

The active form of the drug may simply be this open form.

It could also be that another hemiacetal is formed, possibly with ergosterol, or through hemiketalization.

<img src="images/assembling.png" alt="drawing" width="600"/>

A model based on the later hypothesis is shown below. The ergosterol molecules are highlighted in dashed frames. Their edge shape makes the intercalation possible (which contrasts with [cholesterol](CholesterolErgosterol)).


![7777](images/Fig_7_decamer.png)

This 3D model only shows the top corona (no ergosterol). Observe the salt bridges and the favorable position of the (5)OH between these bridges.

<script type="text/javascript" src="src/JSmol.min.js"></script>
<script type="text/javascript">
Info = {
    script: "set antialiasDisplay true;load molecules/sym8.mol;cartoon on;color cartoon structure;rotate x 130.0;spin MOLECULAR Z 10",
    width:600,      
    height:500,      
    j2sPath: "src/j2s",   
    disableJ2SLoadMonitor: false,
    isableInitialConsole: true
}
</script>

<script>Jmol.getApplet("JmolAppletA",Info);</script>

View <a href='javascript:Jmol.script(JmolAppletA,"reset;");'>top</a>/<a href='javascript:Jmol.script(JmolAppletA,"reset;rotate x -90");'>side</a>. Spin <a href='javascript:Jmol.script(JmolAppletA,"; spin MOLECULAR Z 10");'>on</a>/<a href='javascript:Jmol.script(JmolAppletA,"spin off");'>off</a>. 

Select one unit <a href='javascript:Jmol.script(JmolAppletA,"select atomno >60 ;color atoms TRANSLUCENT 0.8")'>on</a>/<a href='javascript:Jmol.script(JmolAppletA,"select atomno >60 ;color atoms TRANSLUCENT 0.0")'>off</a>. Highlight one carboxylate/amonium pair <a href='javascript:Jmol.script(JmolAppletA,"select atomno = 429 , atomno = 427 , atomno = 428 ,  atomno = 475 ;spacefill 200;select   atomno = 476 ,  atomno = 477 ,  atomno = 480;spacefill 150")'>on</a>/<a href='javascript:Jmol.script(JmolAppletA,"select atomno = 429 , atomno = 427 , atomno = 428 ,  atomno = 475 ;spacefill 100;select   atomno = 476 ,  atomno = 477 ,  atomno = 480;spacefill 60")'>off</a>/

Set<a href='javascript:Jmol.script(JmolAppletA,"script APPLET * \"background white\"")'> white</a>/<a href='javascript:Jmol.script(JmolAppletA,"script APPLET * \"background black\"")'>black</a> background.

<a href='javascript:Jmol.script(JmolAppletA,"console")'>Console</a>.
<code>print script("show orientation");label</code>
