# more-css-notes
<--circles with friends-->
<!DOCTYPE html>
<html>
	<head>
		<link type="text/css" rel="stylesheet" href="stylesheet.css"/>
		<title>My Social Network</title>
	</head>
	<body>
		<!--Add your HTML below!-->
		<div class="friend" id="best_friend"><p>Stephanie</p></div>
		<div class="friend"><p>Katie</p></div>
		<div class="friend"><p>Jackie</p></div>
		<div class="oldfriend"><p>Marti</p></div>
        <div class="oldfriend"><p>Tessie</p></div>
        <div class="oldfriend"><p>Tison</p></div>
        <div class="oldfriend"><p>Jen</p></div>
        <div class="workfriend"><p>Teresa</p></div>
        <div class="family"><p>Jason</p></div>
        <div class="family"><p>Lilybeth</p></div>
        <div class="family"><p>Annabelle</p></div>
        <div class="family"><p>Dawn</p></div>
        <div class="enemy" id="archnemesis"><p>Boredom</p></div>
        <div class="enemy"><p>$$$</p></div>
	</body>
</html>
/*Add your CSS below!*/

div {
	display: inline-block;
	margin-left: 5px;
	height: 100px;
	width: 100px;
	border-radius: 100%;
	border-width: 2px;
	border-style: solid;
	border-color: black;
	text-align: center;
	
}
.friend {
    border-width: 2px;
    border-style: dashed;
    border-color: #008000;
}

.family {
    border-width: 2px;
    border-style: dashed;
    border-color: #0000FF;
}
.enemy {
    border-width: 2px;
    border-style: dashed;
    border-color: #FF0000;
}
#best_friend {
    border-width: 4px;
    border-style: solid;
    border-color: #00C957;
}
#archnemesis {
    border-width: 4px;
    border-style: solid;
    border-color: #CC0000;
}


