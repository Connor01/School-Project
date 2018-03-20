# School-Project
drawSpaceship();


GraceLaGrone-patch-1
(Grace)
drawMoon();
//This creates the moon by placing a pale yellow dot in the top left corner then adding darker yellow dots in it
function drawMoon() {
  penUp();
  moveTo(81, 80);
  penDown();
  penRGB(255, 255, 224, 1);
  dot(45);
  moveTo(66, 61);
  penRGB(240, 240, 200, 1);
  dot(20);
  penUp();
  moveTo(99, 101);
  penRGB(240, 240, 200, 1);
  dot(15);

Here is the code for the project, just add what you did to it, MAKE SURE TO LEAVE COMMENTS EXPLAINING WHAT YOUR CODE DID!!!

penUp();
//This creates the Background. 
penRGB(25, 25, 70, 1);
dot(500);
drawStar(500);
// This Function makes the stars by using random numbers to determine the size, color, and where the stars are places on the background.
//There is also a loop with the label amount so you can choose how many stars you want on the background.
function drawStar(amount) {
  for (var i = 0; i < amount; i++) {
    moveTo(randomNumber(1, 350), randomNumber(1, 450));
    penRGB(randomNumber(200, 255), randomNumber(200, 255), randomNumber(200, 255), 1);
    dot(randomNumber(1, 3));
  }master

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


