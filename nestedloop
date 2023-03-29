let ypos = 25;
let ystep = 25;
let xpos = 25;
let xstep = 25;
let colorselect = ["red", "whit", "blue"];
let colors = [];
function setup() {
  createCanvas(500, 500);

  colorMode(HSB);
  noStroke();
  for (let i = 0; i < 360; i++) {
    colors[i] = color(i, 100, 100);
  }
}

function draw() {
  background(220);
  for (let i = 0; i < 360; i++) {
        fill(colors[i]);
  }
  function mousepressed(){
fill("colorselect")}
  for (let s = 0; s < 19; s++) {
    for (let q = 0; q < 19; q++){
      ellipse(xpos + xstep * q, ypos + ystep * s, 20, 20);
    }
  }


}
