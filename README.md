from pygame import * 


window = display.set_mode((700, 500)) 
display.set_caption("Пин Понг") 
background = transform.scale(image.load("background.png"), (700, 500)) 
 

   display.update() 
   clock.tick(FPS) 
