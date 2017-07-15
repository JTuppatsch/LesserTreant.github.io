<html>
	<head>
		<title>This is no test!</title>
		<link rel="icon" href="file:///C:/Users/Johnas/Desktop/Tree.png">
	</head>
	<body>
		<p id="knöpfe">
			<button onclick="Start()"
					id="Startbutton">Start with only Buttons</button>
			or
			<button onclick="KeysForDays()"
					id="key">only Keys</button>
			</p>
		
		<p id="knöpfesec">
			<button onclick="SpeedPlus()"
					style="visibility:hidden"
					id="faster">Faster</button>
			<button onclick="slowdown()"
					style="visibility:hidden"
					id="slow">Slow</button>
			<button onclick="clearAll()"
					style="visibility:hidden"
					id="stop">Stop</button>
			<button onclick="time = 0;y = 0; gd = 0; render(); "
					style="visibility:hidden"
					id="reset">Reset</button>
			</p>
		
		<p id= "pps"> Geschwindigkeit:  <meter 
			id="myMeter" 
			min="0"
			max="20"
			value="0"></meter> 
			</p>
		<p id="Kevin">
			</p>
			
		<canvas width="600" height="600"
			style="border:1px solid #d3d3d3;"
			id="myCanvas">
			</canvas>
			
		<script>
			document.body.style.backgroundColor = "#f3f3f3";
			var canvas = document.getElementById("myCanvas"),
				c = canvas.getContext("2d"),
				K = document.getElementById("Kevin"),
				y = 0,x = 0, v, interval, G, H,
				time = 0, I = 0, P = 0,
				goesdown = true, gd = 0;
			
			function KeysForDays(){
				G = ["reset", "faster", "slow", "stop", "knöpfe", "Startbutton", "pps", "Kevin"];
				hideThem(G);
				G = ["key", "pauseKey", "scriptende"];
				showThem(G);
				document.getElementById("key").innerText = "only Buttons";
				document.getElementById("key").onclick = function onclick(event) {KnopfeForDays()};
				clearAll();
				time = 0; y = 0; gd = 0;
				render();
				KeysFirst();
			}
			
			function KnopfeForDays(){
				clearAll();
				document.getElementById("key").innerText = "only Keys";
				document.getElementById("key").onclick = function onclick(event) {KeysForDays()};
				G = ["scriptende", "pauseKey"]
				hideThem(G);
				G = ["reset", "faster", "slow", "stop", "key", "knöpfesec", "pps", "Kevin"];
				showThem(G);
				y = 0; x = 0;
				render();
				document.getElementById("stop").innerText = "Stop";
				document.getElementById("stop").onclick = function onclick(event) {clearAll()};
				document.getElementById("faster").disabled = false;
			}
			
			function Start(){
				SpeedPlus();
				G = ["Startbutton", "knöpfe", "scriptende", "pauseKey"];
				hideThem(G);
				G = ["reset", "faster", "slow", "stop", "key"];
				showThem(G);
			}
			
			function SpeedPlus(){
				if (P < 20){
					setInterval(render, 50);
					I += 1;
					P += 1;
				}
			}
			
			function slowdown(){
				if (P > 0){
					interval = I - P+1;
					P -= 1;
					clearInterval(interval);
					updateMeter();
				}
			}
			
			function updateMeter(){
				myMeter.value = P;
				document.getElementById("Kevin").innerHTML = "Pps: " + P*20;
			}
			
			function clearAll(){
				for (j = 0; j <= I; j++){
					clearInterval(j);
				}
				document.getElementById("stop").innerText = "Release";
				document.getElementById("stop").onclick = function onclick(event) {release()};
				H = P;
				P = 0;
				updateMeter();
				document.getElementById("faster").disabled = true;
			}
			
			function release(){
				for (j = 0; j < H; j++){
					setInterval(render, 50);
					I += 1;
					P += 1;
				}
				updateMeter();
				document.getElementById("stop").innerText = "Stop";
				document.getElementById("stop").onclick = function onclick(event) {clearAll()};
				document.getElementById("faster").disabled = false;
			}
			
			function render(){
				c.clearRect(0, 0, canvas.width, canvas.height)
				updateMeter();
				x = time;
				var	width = 20, height = 20;
				
				gravity();
				y += gd;
				if(y > 588){
					gd *= -1
				}
				
				if (time == 600){
					time = -10;
					//y = Math.floor(Math.random() * 590);
				};
				
				c.fillRect(x, y, width, height);
				time += 1;
			}
			
			function gravity(){
				if(gd < 12){
					gd += 0.1;
				}
			}
			
			function showThem(a){
				var ToShow = a.length;
				if(document.getElementById("Startbutton").style.visibility === "hidden"){
					for (i = 0; i < ToShow; i++){
						document.getElementById(a[i]).style.visibility = "visible";
					}
				}
			}
			
			function hideThem(a){
				var ToHide = a.length;
				for (i = 0; i < ToHide; i++){
					document.getElementById(a[i]).style.visibility = "hidden";
				}
			}
			
//#################################################################################
			//Keypressed
			document.onkeydown = Keycheck;
			
			var foodbits = 80,
				intervalcd = 100;
			
			var F = [4],
				Keyhight = 10, Keywidth = 10,
				doublecount, ac, stopit = 0,
				searchhelp1, searchhelp2, paused,
				position_food, eaten_food = 0,
				XBitArray = [100], YBitArray = [100];
					
			function KeysFirst(){
				I += 1;
				XBitArray.fill(5);
				YBitArray.fill(5);
				Food();
				y = 0;
				setInterval(renderKeys, intervalcd);
			}
			
			function Keycheck(e){
			    e = e || window.event;
				if (document.getElementById("key").innerText === "only Buttons" && F[0] != 5){
					if (e.keyCode == '38') {
						F = [1];
					}
					else if (e.keyCode == '40') {
						F = [2];
					}
					else if (e.keyCode == '37') {
						F = [3];
					}
					else if (e.keyCode == '39') {
						F = [4];
					} 
				} else {
					if (e.keyCode == '38') {
						pauseKeygame(); F = [1]; 
					}
					else if (e.keyCode == '40') {
						pauseKeygame(); F = [2]; 
					}
					else if (e.keyCode == '37') {
						pauseKeygame(); F = [3]; 
					}
					else if (e.keyCode == '39') {
						pauseKeygame(); F = [4]; 
					}
					
				}
			}
			
			
			
			function renderKeys(){
				c.clearRect(0, 0, canvas.width, canvas.height)
				var	width = Keywidth, height = Keyhight;
						if (F[0] == 1 && y > 1){				//up
					y -= 10;
				}else 	if (F[0] == 2 && y < 600-height){		//down
					y += 10;
				}else	if (F[0] == 3 && x > 1){				//links
					x -= 10;
				}else 	if (F[0] == 4 && x < 600-width ){		//rechts
					x += 10;
				}else 	if (F[0] == 1 && y < 1){				//seitenwechsel
					y = 600-height;
				}else 	if (F[0] == 2 && y >= 600-height){		//down
					y = 10;
				}else 	if (F[0] == 3 && x < 1){				//seitenwechsel
					x = 600-height;
				}else 	if (F[0] == 4 && x >= 600-height){		//down
					x = 10;
				}
				checkCollision();
				c.fillRect(x, y, width, height);
				c.fillStyle = "blue";
				for(i = 0; i < XBitArray.length; i++){
					c.fillRect(XBitArray[i], YBitArray[i], 10, 10);
				}
				c.fillStyle = "black";
			}
			
			function checkCollision(){
				searchhelp1 = 0;
				searchhelp2 = foodbits;
				//sorting();
				for(i = searchhelp1; i < foodbits; i++){
					if(XBitArray[i] == x && YBitArray[i] == y){
						//console.log("Eat up!");
						position_food = i;
						food_eaten();
						eaten_food += 1;
						document.getElementById("scriptende").innerHTML = "Dots eaten: " + eaten_food;
						
						break;
					}
					/*
					if(XBitArray[i] > x){
						//break;
					}*/
				}
			}
			
			function sorting(){
				if (searchhelp2 - searchhelp1 > 10){
					var half = searchhelp1 + (searchhelp2 - searchhelp1)/2;
					if (XBitArray[half] >= x){
						searchhelp2 = half
					} else {
						searchhelp1 = half
					}
					sorting();
				}
			}

			function food_eaten(){
				var round = 0;
				while(round == 0){
					var Xbits, Ybits;
					Xbits = Math.floor(Math.random() * 60)*10;
					Ybits = Math.floor(Math.random() * 60)*10;	
					doublecount = 0;
					ac = Xbits;
					//console.log(Xbits + "/" + Ybits);
					if (XBitArray.find(checkmatches) === Xbits){
						doublecount = 1;
					}
					
					ac = Ybits;
					if (YBitArray.find(checkmatches) === Ybits){
						doublecount += 1;
					}
					
					if (doublecount != 2){
						YBitArray[position_food] = Ybits;
						XBitArray[position_food] = Xbits;
						round = 1;
						//XBitArray
					}
				}
			}
			
			function Food(){
				var Xbits, Ybits;
				stopit = 0;
				for (i = foodbits - 1; i >= 0; i--){
					Xbits = Math.floor(Math.random() * 60)*10;
					Ybits = Math.floor(Math.random() * 60)*10;
					if (i != foodbits-1){
						doublecount = 0;
						ac = Xbits;
						//console.log(Xbits + "/" + Ybits);
						if (XBitArray.find(checkmatches) === Xbits){
							doublecount = 1;
						}
						
						ac = Ybits;
						if (YBitArray.find(checkmatches) === Ybits){
							doublecount += 1;
						}
						
						if (doublecount != 2){
							YBitArray[i] = Ybits;
							XBitArray[i] = Xbits;
						}
						
						if(doublecount == 2){
							i += 1;
							//console.log(stopit + "/" + i);
						}
						
					} else {
						XBitArray[i] = Xbits;
						YBitArray[i] = Ybits;
					}
					stopit += 1;
					if (stopit == 500){
						console.log("break");
						break;
					}
					
				}
				XBitArray.sort(function(a, b){return a-b});
			}
			
			function checkmatches(Array) {
				return Array == ac;
			}
			
			function tell(){
				for(i = 0; i < XBitArray.length; i++){
					console.log(XBitArray[i] + "/" + YBitArray[i]);
				}
			}
			
			function pauseKeygame(){
				if (F[0] != 5){
					paused = F[0]
					F[0] = 5;
					document.getElementById("pauseKey").innerText = "Unpause"
					
					c.clearRect(0, 0, canvas.width, canvas.height)
					c.font = "100px Verdana";
					c.fillStyle = "red";
					c.fillText("Paused", 120, 300);
					c.fillStyle = "black";
					c.font = "30px Verdana";
					c.fillText("Press any key to continue!", 105, 350);
					clearInterval(I);
				} else {
					if (F[0] == 5){
						F[0] = paused;
					}
					document.getElementById("pauseKey").innerText = "Pause"
					setInterval(renderKeys, intervalcd);
					I += 1;
				}
			}
			
		</script>
		<p>		<button onclick="pauseKeygame()"
					style="visibility:hidden"
					id="pauseKey">Pause</button>
			</p>
		<p id="scriptende"> </p>
	</body>
</html>
