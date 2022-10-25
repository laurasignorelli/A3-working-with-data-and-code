//variables
int x = 100;
int x2 = 100;
float r = 255;
float g = 192;
float b = 203;
int y = 0;
PImage img;

void setup () {
  size(600, 600);
  img = loadImage("cloud2.png");
  

}

void mousePressed () {
  x = -50; 
  x2 = -50;
  
}

void draw () {
 
  if (mouseY > 550) {
    
     //starry sky
     fill(0, 5);
     rect(0, 0, 600, 300);
     fill(225);
     noStroke();
     ellipse(random(width), random(height), 2,2);
    
     //water (night)
     fill(#013a52);
     rect(0,300,600,300);
     noStroke();  
     
      fill(#506773);
     beginShape();
     curveVertex(264,  293);
     curveVertex(731,  1994);
     curveVertex(577,  586);
     curveVertex(-240,  353);
     curveVertex(903, 1467);
     curveVertex(441, 484);
     endShape();
  
     fill(#205375);
     beginShape();
     curveVertex(645,  631);
     curveVertex(2928,  288);
     curveVertex(23,  436);
     curveVertex(453,  1977);
     curveVertex(441, 605);
     curveVertex(224, 622);
     endShape();
  
     fill(#164280);
     beginShape();
     curveVertex(512,  618);
     curveVertex(3032,  512);
     curveVertex(416,  418);
     curveVertex(-27,  1977);
     curveVertex(450, 605);
     curveVertex(168, 622);
     endShape();
 
     fill(#135e7d);
     beginShape();
     curveVertex(542,  866);
     curveVertex(1367,  730);
     curveVertex(301,  418);
     curveVertex(-77,  513);
     curveVertex(-39, 538);
     curveVertex(201, 607);
     endShape();
  
     fill(#023a52);
     beginShape();
     curveVertex(439,  894);
     curveVertex(727,  662);
     curveVertex(440,  475);
     curveVertex(109,  530);
     curveVertex(-490, 562);
     curveVertex(0, 499);
     endShape();
     
     //jetty (night)
     fill(#78573a);
     triangle(130, 600, 300, 300, 470, 600); 
     noStroke();
     
     //hills (night)
     fill(#144038);
     beginShape();
     curveVertex(1000,289);
     curveVertex(308,300);
     curveVertex(600,300);
     curveVertex(119,257);
     curveVertex(0,300);
     curveVertex(1000,300);
  
     curveVertex(700,338);
     curveVertex(600,287);
     curveVertex(426,269);
     curveVertex(300,300);
     curveVertex(415,300);
     curveVertex(353,553);
     endShape();
  
     //jetty details (night)
     fill(#3b291d, 150);
     rect(165,537,271,1);
     rect(195,483,209,1);
     rect(221,439,161,1);
     rect(243,400,117,1);
     rect(262,366,76,1);
     rect(275,340,48,1);
     rect(287,321,25,1);
     rect(295,308,11,1);
         
      //moon
     fill(#FEFFDE, 1);
     ellipse(500, 100, 140, 140);
     fill(#FEFFDE);
     ellipse(500, 100, 100, 100); 

  }else{
  
  //colour changing sky (day)
  fill(r, g, b);
  rect(0, 0, 600, 300);
  r = map(mouseX, 0, 600, 255, 248);
  g = map (mouseX, 0, 600, 192, 152);
  b = map(mouseX, 0, 600, 203, 128);
 
  //moving sun (day)
  noStroke();
  fill(#FFFFCF, 75);
  ellipse(300, x-100, 250, 250); 
  fill(#FFFF00);
  ellipse(300, x-100, 200, 200); 
  x = x + 1;
  
  //moving clouds (day)
  image(img, x-200, 0, 548, 183);
  
  //water (day
  fill(#006994);
  rect(0,300,600,300);
  noStroke();
  
  fill(#82a6b8);
  beginShape();
  curveVertex(264,  293);
  curveVertex(731,  1994);
  curveVertex(577,  586);
  curveVertex(-240,  353);
  curveVertex(903, 1467);
  curveVertex(441, 484);
  endShape();
  
  fill(#3790cc);
  beginShape();
  curveVertex(645,  631);
  curveVertex(2928,  288);
  curveVertex(23,  436);
  curveVertex(453,  1977);
  curveVertex(441, 605);
  curveVertex(224, 622);
  endShape();
  
  fill(#2881fc);
  beginShape();
  curveVertex(512,  618);
  curveVertex(3032,  512);
  curveVertex(416,  418);
  curveVertex(-27,  1977);
  curveVertex(450, 605);
  curveVertex(168, 622);
  endShape();
 
  fill(#219ed1);
  beginShape();
  curveVertex(542,  866);
  curveVertex(1367,  730);
  curveVertex(301,  418);
  curveVertex(-77,  513);
  curveVertex(-39, 538);
  curveVertex(201, 607);
  endShape();
  
  fill(#0575a3);
  beginShape();
  curveVertex(439,  894);
  curveVertex(727,  662);
  curveVertex(440,  475);
  curveVertex(109,  530);
  curveVertex(-490, 562);
  curveVertex(0, 499);
  endShape();
 
  //jetty (day)
  fill(#DAA06D);
  triangle(130, 600, 300, 300, 470, 600);
  
  //hills (day)
  fill(#1F6357);
  beginShape();
  curveVertex(1000,289);
  curveVertex(308,300);
  curveVertex(600,300);
  curveVertex(119,257);
  curveVertex(0,300);
  curveVertex(1000,300);
  
  curveVertex(700,338);
  curveVertex(600,287);
  curveVertex(426,269);
  curveVertex(300,300);
  curveVertex(415,300);
  curveVertex(353,553);
  endShape();
  
  //jetty details (day)
  fill(#6F4E37, 150);
  rect(165,537,271,1);
  rect(195,483,209,1);
  rect(221,439,158,1);
  rect(243,400,114,1);
  rect(262,366,76,1);
  rect(275,340,48,1);
  rect(287,321,25,1);
  rect(295,308,11,1);
  
 
  }
    
}
