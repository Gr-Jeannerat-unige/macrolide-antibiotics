Macrolide antibiotics with antifungal activity:

![Common structure element](images/commonMotif.png)

Diversity 

table:

![all](images/all_anti_images.png)

<script type="text/javascript" language="javascript" src="jsme/jsme.nocache.js"></script>
<script>
        function getFile(fileName) {
            oxmlhttp = null;
            try {
                oxmlhttp = new XMLHttpRequest();
                oxmlhttp.overrideMimeType("text/xml");
            }
            catch (e) {
                try {
                    oxmlhttp = new ActiveXObject("Msxml2.XMLHTTP");
                }
                catch (e) {
                    //return null;
                    return "failed MS<BR>";
                }
            }
            if (!oxmlhttp) return "failed to create object<BR>";
            try {
                oxmlhttp.open("GET", fileName, false);
                oxmlhttp.send(null);
            }
            catch (e) {
                return "failed to get webpage<BR>";
            }
            return oxmlhttp.responseText;
        }


        //this function will be called after the JavaScriptApplet code has been loaded.
        function jsmeOnLoad() {
            jsmeApplet = new JSApplet.JSME("jsme_container", "580px", "340px", {
                "options": "depict multipart reaction border"
            });
// other options : https://www.molinspiration.com/jme/doc/jme_functions.html number
            var fileData = getFile('menthol-2d.mol')
            jsmeApplet.readMolFile(fileData);

            var actionMarked = 105;
            jsmeApplet.setAction(actionMarked);


        }
</script>
<div id="jsme_container"></div>

