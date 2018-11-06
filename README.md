void setup() {

  size(600, 600);
}

void draw() {

  fill(255, 214, 248);
  textSize(100);
  text("i", 150, 200);

  background(193, 239, 255);

  strokeWeight(10);
  stroke(255, 214, 248);
  ellipse(mouseX, mouseY, 5, 5);

  line(150, 90, 150, 150);


  strokeWeight(5);
  arc(mouseX+250, mouseY+350,50,50, radians(0), radians(300));

  fill(255, 202, 202);
  textSize(100);
  text("am", 200, 300);



  fill(255, 181, 154);
  textSize(100);
  text("kaithleen", 110, 440);
}
