var btn_red;
var btn_green;
var btn_blue


var r = 0;
var g = 0;
var b = 0;

function setup() {
  createCanvas(400, 400);  

  btn_red = createButton ("RED");
  btn_red.position(50,190);
  btn_red.mousePressed(red_bg)
  
  btn_green = createButton ("GREEN");
  btn_green.position(150,190);
  btn_green.mousePressed(green_bg)

  btn_blue = createButton ("BLUE");
  btn_blue.position(250,190);
  btn_blue.mousePressed(blue_bg)

  btn_anyColor = createButton("Click to change color"); 
  btn_anyColor.position(110,150); 
  btn_anyColor.mousePressed(colorChange)

}

function draw() {
  background(r,g,b);
}


function colorChange(){
  var randR = Math.round(random(0,255)); 
  var randG = Math.round(random(0,255));
  var randB = Math.round(random(0,255));
  r = randR; 
  g = randG; 
  b = randB;
}






function red_bg(){
  r = 243;
  g = 12;
  b = 83;
}
function green_bg(){
  r = 7;
  g = 248;
  b = 183;
}
function blue_bg(){
  r = 0;
  g = 145;
  b = 255;
}

