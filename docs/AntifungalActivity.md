# A new proposition of mecanism of antifungal activity
## Opening of the hemiactal


Hemiacetals are not very stable (see left, below). The C-O bond can easily break to form a ketone and an alcool (see right, below). This is faciliated by the presence of a OH group, or other catalysts exchanging protons.

![333333](images/Fig3.png)

In cyclic coumpounds, hemiacetals are usually at equilibrium with their open form. 

The [mutarotation](https://en.wikipedia.org/wiki/Glucose#Mutarotation) of glucose is very well know. The cyclic &alpha;-glucose (36%) and &beta;-glucose (64%)), two hemiacetals, slowly exchange via the open "keyto" form (< 1%).


<img src="images/open_hemi.png" alt="drawing" width="500"/>

In macrolide antibiotics of the amphotericin family, there is always an OH group making it possible to form the stabilizing 6-membered ring. See carbons 1 in the Figure below. Also on 5...

The active form of the drug may simply be this open form.

It could also be that another hemiacetal is formed, possibly with ergosterol, or with via poly-hemiketalization.

<img src="images/assembling.png" alt="drawing" width="600"/>

A model based on the later hypothesis is shown below. The ergosterol molecules are highlighted in dashed frames.


![7777](images/Fig_7_decamer.png)

This 3D model only shows the top corona (no ergosterol).

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
]