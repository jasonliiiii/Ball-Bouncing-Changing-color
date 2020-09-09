# Ball-Bouncing-Changing-color
/*
color c1 = color(255,0,255); 
color c2 = color(0,255,255);
void setup(){
  size(600,600);
}
void draw(){
  if(mouseX < width/2){
    background(c1); 
  }
  else if(mouseX >= width/2){
    background(c2);
  }
}
*/

/*
float red = 155;
float blue = 0;

void setup(){
  size(600,600);}
void draw(){
  background(red,0,blue);
} 
void keyPressed(){
  red = red - 10;
  blue = blue +10; 
}
*/

/*
float x = 750;
float y = 1;
float red = 255;
float blue = 0;
void setup(){
  size(800,800);
}
  
void draw(){
  
background(255,255,255);
fill(red,0,blue);
if(x >=750){
  y = -1; 
  red = red + 5;
  blue = blue - 5;
}else if(x<=50){
  y = 1;
}
ellipse(x,450,100,100);
x = x + y;
}
*/
