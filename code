let radius = 100;
let x, y;
let score = 0;
let r, g, b;

function setup() {
  createCanvas(windowWidth, windowHeight);
  x = random(windowWidth);
  y = random(windowHeight);
  r = random(255);
  g = random(255);
  b = random(255);
}

function draw() {
  background(220);
  fill(r, g, b);
  noStroke();
  ellipse(x, y, radius * 2, radius * 2);
  fill(0)
  textSize(50)
  text("Score: " + score, 10, 50);
}

function mousePressed() {
  let d = dist(mouseX, mouseY, x, y);
  if (d < radius) {
    newCircle();
    score++;
    radius = random(50)
  }
}

function newCircle() {
  x = random(windowWidth);
  y = random(windowHeight);
  r = random(255);
  g = random(255);
  b = random(255);
}
