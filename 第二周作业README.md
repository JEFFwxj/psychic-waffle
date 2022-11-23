# psychic-waffle
void setup() {
  size(1000, 1200);
  background(58);
}
int x;
int Y,R,W,B;
void draw() {
    fill(58,20);
    rect(0,0,width,height);
    x=int(random(100)+1);
    if(x<=15){ 

    fill(#F6FA21);
  Y=Y+1;}
 else if ( x>=15 & x<=40){
 fill(#3667F5);
 B=B+1;
 }
  else if ( x>=40 & x<=90){
 fill(255);
 W=W+1;
 }
 else if (x>=90){
   fill(#FF1C2B);
   R=R+1;
}
strokeWeight(random(20));
rect(random(1000),random(1000),random(1000),random(1000));
 print(frameRate,W,Y,R,B);
