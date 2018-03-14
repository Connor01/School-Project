# School-Project
This is the place for a school project for team constellations.

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
}
