# School-Project
drawSpaceship();

//make space ship 
function drawSpaceship() {
  penUp();
  moveTo(210,160);
  penColor("lightblue");
  dot(23);
  moveTo(210,170);
  turnLeft(90);
  
  penDown();
  penWidth(10);
  penColor("black");
 
  moveForward(50);
  turnLeft(130);
  moveForward(10);
  turnLeft(50);
  moveForward(90);
  turnLeft(50);
  moveForward(10);
  turnLeft(130);
  moveForward(53);
}


