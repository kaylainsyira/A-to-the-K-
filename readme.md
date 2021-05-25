var Juliet;

function preload() {
  Juliet = loadFont('data/Juliet-Serif.otf');
}

function setup() {
  createCanvas(windowWidth, windowHeight);
  background(0);
  fill(255);
  noStroke();
  textFont(Juliet);
  textSize(350);
 

}


function draw() {
  fill(255);
  noStroke();
  textSize(18);
  textAlign(LEFT, TOP);
  text('juliet serif', 25, 18);
  fill(255);
  noStroke();
  textSize(18);
  textAlign(CENTER, TOP);
  text('by', width/2, 18);
  fill(255);
  noStroke();
  textSize(18);
  textAlign(RIGHT, TOP);
  text('kayla insyira', 1250, 18);
  fill(255);
  noStroke();
  textSize(18);
  textAlign(CENTER, BOTTOM);
  text('click anywhere', width/2, 550);
  
}

function mousePressed() {
  fill(255);
  noStroke();
  textSize(350);
  textAlign(CENTER, CENTER);
  text('A', width/2, 250);
  
}
  
