# cMaps
Biotechnology cMaps
<HTML>
<HEAD>
  <TITLE>Bird.html</TITLE>
  <meta NAME = "GENERATOR"          CONTENT = "IHMC CmapTools vr. 4.12 ">
  <meta NAME = "KEYWORDS"           CONTENT = "Vladimir Vincent, Concept Map, cmap, CmapTools, IHMC, Bird,  Constant Body Temperature,  Logan Sumich 1/14/2016 Biotechnology,  Eggs,  Birds,  Fly,  Feathers,  Two Feet,  Endotherms,  Hollow Bones,  Sexually,  Warm-Blooded Animals,  Heat,  Light body weights,  Beaks,  High metabolism,  Rapid Digestive Systems,  Energy,  What are birds?,  Food,  Insulation">
  <meta NAME = "DESCRIPTION"        CONTENT = "This Concept Map, created with IHMC CmapTools, has information related to: Bird, Warm-Blooded Animals produce Heat, Birds lay Eggs, Endotherms means Warm-Blooded Animals, Rapid Digestive Systems is necessary due to High metabolism, Birds have Two Feet, Food for Energy, Light body weights help to Fly, Energy much is required to Fly, Birds have Two Wings, Birds require Food, Birds reproduce Sexually, Birds have Beaks, Hollow Bones provide for Light body weights, Birds have Hollow Bones, Heat from Food, Warm-Blooded Animals maintain Constant Body Temperature, Birds have Feathers, Birds are Endotherms, High metabolism provides Energy, Feathers offer Insulation">
  <meta NAME = "AUTHOR"             CONTENT = "IHMC CmapTools">
  <meta HTTP-EQUIV = "Content-Type" CONTENT = "text/html; charset = UTF-8">
  <script LANGUAGE="JavaScript1.2">
  <!--
    //  PopUp --
    //  Institute for Human and Machine Cognition, http://www.ihmc.us/
    //  CmapTools, Version 4.11, http://cmap.ihmc.us/
    //  Modify by: CmapTools Developers, cmapsupport@ihmc.us
    //  Date: 12/14/2006
    var IE = 0;
    var IE4PC = 0;
    var NS = 0;
    var GECKO = 0;
    var openpopups = new Array();
    if (document.all) {                 // Internet Explorer Detected
	   IE = true;	
    }
    else if (document.layers) {         // Netscape Navigator Detected
	   NS = true;	
    }
    else if (document.getElementById) { // Netscape 6 Detected
       GECKO = true;
    }
    else {
	   alert("Unrecognized Browser Detected::\nSorry, your browser is not compatible.");
    }
    if (IE)
    {
	   OS = navigator.platform;
	   VER = new String(navigator.appVersion);
	   VER = VER.substr (0, VER.indexOf(" "));
	   if ((VER < 4.8) && (OS == "Win32")) 
	   {
	       IE4PC = 1;
	   }
    }
    function handleResize() {
	    location.reload();
	    return false;
    }
    if ((NS) && (navigator.platform == "MacPPC")) {
	   window.captureEvents (Event.RESIZE);
	   window.onresize = handleResize;
    }
    function openResource(event, resourcePath, resourceName, resourceType)
    {
	   var newwindow;
       // Resource MIMETypes are enumerated as follows: 
       // cMap     = Undefined
       // Image    = 0
       // Video    = 1
       // Text     = 2
       // Audio    = 3
       popDown();
	   switch (resourceType) 
	   {
	    case 0:     //Image
                    newwindow = window.open (resourcePath,resourceName);
                    newwindow.onBlur = newwindow.focus()
                    var text ='<center><img src=\"';
                    text += resourcePath;
                    text +='\"> </center>';
             break;
		
	    case 1:  text   // Video
		     newwindow = window.open (resourcePath,resourceName);
                     newwindow.onBlur = newwindow.focus()
                     var text ='<embed src=\"';
                     text += resourcePath;
                     text +='\" autostart=true> </embed> ';
             break;
	    case 2:      // Text or Unknown 
		     newwindow = window.open(resourcePath,resourceName);
                     newwindow.onBlur = newwindow.focus()
              break;
	    case 3:       // Audio
                    newwindow = window.open (resourcePath,resourceName);
                    newwindow.onBlur = newwindow.focus()
                    var text ='<embed src=\"';
                    text += resourcePath;
                    text +='\" autoplay=true> </embed> ';
             break;
	    case 4:
                    newwindow = window.open(resourcePath,resourceName);
                    newwindow.onBlur = newwindow.focus()
	     break;
	    }
        return;
    }
    function popUpEvt(event, popupName)
    {
	popDown();
	if (GECKO)
	{
	    document.getElementById(popupName).style.left = event.layerX;
	    document.getElementById(popupName).style.top = event.layerY;
	    document.getElementById(popupName).style.background = "#B3B3B3";
	    document.getElementById(popupName).style.visibility = "visible";
	    openpopups.push(popupName);
	}
	else if (NS) 
	{
	    document.layers[popupName].moveTo (event.pageX, event.pageY);
	    document.layers[popupName].bgColor = "#B3B3B3";
	    document.layers[popupName].visibility = "show";
	    openpopups.push(popupName);
	}
	else // if (IE)
	{
	    window.event.cancelBubble = true;
	    if (!IE4PC) {
		document.all[popupName].style.backgroundColor = "#B3B3B3";
	    }	
	    document.all[popupName].style.left = window.event.clientX + document.body.scrollLeft;
	    document.all[popupName].style.top = window.event.clientY + document.body.scrollTop;
	    document.all[popupName].style.visibility = "visible";
	    openpopups[openpopups.length] = popupName;
	}
	return false;
    }
    function popDown()
    {
	var popupname;
	
	for (var i = 0; i < openpopups.length; i++) 
	{
	    popupname = new String (openpopups[i]);      
	    if (GECKO) {
		document.getElementById(popupname).style.visibility = "hidden";
	    }
	    else if (NS) {
		document.layers[popupname].visibility = "hide";
	    }
	    else {
		document.all[popupname].style.visibility = "hidden";
	    }
	}
	openpopups = new Array();
	return;
    }
    function popDownNoGecko() 
    {
	var popupname;
	for (var i = 0; i < openpopups.length; i++) 
	{
	    popupname = new String (openpopups[i]);      
	    if (GECKO) {
           //  document.getElementById(popupname).style.visibility = "hidden"; 
	        return;   // erased for test purposes
	    }  
	    else if (NS) {
	        document.layers[popupname].visibility = "hide";
	    }
	    else {
	        document.all[popupname].style.visibility = "hidden";
	    }
	}
	openpopups = new Array();
        return;
    }
  //-->
  </script>
</HEAD>
<BODY bgcolor="#FFFFFF" leftmargin="0" topmargin="0">
<noscript>
  <table width=90% cellpadding=10>
    <tr>
      <td bgcolor=ff4447>
        <font color=000000 size=+1 face="helvetica">
        <h1>WARNING:</h1>
        <b>JavaScript is turned OFF.  None of the links on this concept map will <br>
           work until it is reactivated.
          <p>
            <a href="http://cmap.ihmc.us/docs/EnablingJavaScript.html">
                            If you need help turning JavaScript On, click here.
            </a>
          </p>
        </b>
      </td>
    </tr>
  </table>
This Concept Map, created with IHMC CmapTools, has information related to: Bird, Warm-Blooded Animals produce Heat, Birds lay Eggs, Endotherms means Warm-Blooded Animals, Rapid Digestive Systems is necessary due to High metabolism, Birds have Two Feet, Food for Energy, Light body weights help to Fly, Energy much is required to Fly, Birds have Two Wings, Birds require Food, Birds reproduce Sexually, Birds have Beaks, Hollow Bones provide for Light body weights, Birds have Hollow Bones, Heat from Food, Warm-Blooded Animals maintain Constant Body Temperature, Birds have Feathers, Birds are Endotherms, High metabolism provides Energy, Feathers offer Insulation

</noscript>

<map name="Bird.html">
  <area shape="rect"
        href="1QNHQC127I2BZ53CFIS4ItextIhtml"
        onClick="popUpEvt(event,'1QNHQC127I2BZ53CFIS4ItextIhtml'); return false;"
        coords="1103,252,1121,270">
  <area shape="rect"
        href="1QNHR6HYHIW3Q55YI1MGItextIhtml"
        onClick="popUpEvt(event,'1QNHR6HYHIW3Q55YI1MGItextIhtml'); return false;"
        coords="684,497,702,515">
  <area shape="rect"
        href="1QNHR06PBI3FLQ81I1G8ItextIhtml"
        onClick="popUpEvt(event,'1QNHR06PBI3FLQ81I1G8ItextIhtml'); return false;"
        coords="736,329,754,347">
</map>

<center>
  <table width=* height=* cellpadding=0 cellspacing=0 border=0>
    <tr>
      <td valign=center align=center>
        <img USEMAP="#Bird.html"
             SRC="Bird.jpg"
             ALIGN=middle
             BORDER=0
             onClick=popDown();>
      </td>
    </tr>
    <tr>
      <td VALIGN=top ALIGN=right>
        <table>
          <tr>
            <td ALIGN=right VALIGN=middle>
              <map NAME="CmapToolsTrademark">
                <area SHAPE="rect"
                      href="http://cmap.ihmc.us/"
                      onClick="openResource(event,'http://cmap.ihmc.us/', 0, 2); return false;"
                      coords="1,1,210,50">
              </map>
            </td>
          </tr>
          <tr>
            <td  ALIGN=right VALIGN=middle>
              <img USEMAP="#CmapToolsTrademark"
                   SRC="CmapToolsTrademark.gif" 
                   ALT="IHMC Cmap Tools Trademark" width="210" height="50"
                   ALIGN=middle
                   BORDER=0>
            </td>
            <td VALIGN=middle>
            </td>
          </tr>
        </table>
      </td>
    </tr>
  </table>
</center>
</BODY>
</HTML>
<div id="1QNHQC127I2BZ53CFIS4ItextIhtml" style="POSITION: absolute; Z-INDEX: 20; VISIBILITY: hidden; left: 0; top: 0;">
  <table border=1 cellpadding=1 cellspacing=0 bgcolor="#dddddd">
    <tr>
      <td nowrap><font face="Geneva, Arial" size=2>
      <a href="http://users.rcn.com/jkimball.ma.ultranet/BiologyPages/H/HeatTransport.html "TITLE="This website explains what endotherms are and how they maintain homeostasis.">
      The Transport of Heat
      </a>
      </td>
    </tr>
  </table>
</div>
<div id="1QNHR6HYHIW3Q55YI1MGItextIhtml" style="POSITION: absolute; Z-INDEX: 20; VISIBILITY: hidden; left: 0; top: 0;">
  <table border=1 cellpadding=1 cellspacing=0 bgcolor="#dddddd">
    <tr>
      <td nowrap><font face="Geneva, Arial" size=2>
      <a href="http://ornithology.com/ornithology-lectures/7898-2/ "TITLE="This article informs the reader on the properties and scientific figures that result from the analysis of bird metabolism.">
      Bird Metabolism
      </a>
      </td>
    </tr>
  </table>
</div>
<div id="1QNHR06PBI3FLQ81I1G8ItextIhtml" style="POSITION: absolute; Z-INDEX: 20; VISIBILITY: hidden; left: 0; top: 0;">
  <table border=1 cellpadding=1 cellspacing=0 bgcolor="#dddddd">
    <tr>
      <td nowrap><font face="Geneva, Arial" size=2>
      <a href="http://www.brendanbody.co.uk/flight_tutorial/bounding.html "TITLE="This website analyzes the aerodynamics and flight mechanics that let small birds fly faster.">
      Affects of air resistance on small birds
      </a>
      </td>
    </tr>
  </table>
</div>
