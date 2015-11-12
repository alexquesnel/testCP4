# testCP4
Testing GitHub for the first time


what is even going on help


FINALBUILD
CODE
-- Items in slots 

-- 1. 64 Blocks of Iron 
-- 2. 64 Blocks of Iron 
-- 3. 32 Blocks of Iron 
-- 4. 32 BLocks of Iron 
-- 5. 32 Blocks of Iron 
-- 6. 32 Blocks of Iron 
-- 7. 10 Blocks of Cobblestone Wall 
-- 8. 32 Blocks of Glass 
-- 9. 64 Iron Bar 
-- 10. 64 Iron Block 
-- 11. 64 Iron BLock 
-- 12. 64 Iron BLock 
-- 13. 64 Iron Block 
-- 14. 64 Iron Bar 
-- 15. 64 Iron Block 
-- 16. 64 Iron Bar

local X 

X = 1 

for n = 1, 4 do -- builds 2x2x1 blocks 6 times in a stairway fashion going upwards 
                -- builds 4 of these stairway structures 
              
for n = 1, 6 do 

turtle.up() 
turtle.select(X) 
turtle.placeDown() 
turtle.forward() 
turtle.placeDown() 
turtle.turnLeft() 
turtle.forward() 
turtle.placeDown() 
turtle.turnLeft() 
turtle.forward() 
turtle.placeDown() 
turtle.forward() 
turtle.turnLeft() 
turtle.forward() 
turtle.forward() 
turtle.turnLeft() 

end


if X < 4 then 

for n = 1, 6 do 

turtle.down() 

end 
end 

for n = 1, 6 do 

turtle.forward() 

end 

turtle.turnRight() 

if X < 4 then 

for n = 1, 8 do 

turtle.forward() 

end 
end 

X = X + 1 

end

turtle.turnRight() -- fills the gap between the top of the stairway structure to complete first level of tower 
                   -- completes a 7x7x1 platform 
                   
for n = 1, 4 do 
                   
turtle.forward() 
                   
end 
      
for n = 1, 7 do 
                   
turtle.select(X) 
turtle.placeDown() 
turtle.forward() 

end 

turtle.turnLeft() 
turtle.forward() 
turtle.turnLeft() 
turtle.forward() 

for n = 1, 7 do 

turtle.select(X) 
turtle.placeDown() 
turtle.forward() 

end

turtle.turnRight() 
turtle.forward() 
turtle.turnRight() 
turtle.forward() 

for n = 1, 7 do 

turtle.select(X) 
turtle.placeDown() 
turtle.forward() 

end 

X = X + 1

turtle.turnLeft() 
turtle.forward() 
turtle.forward() 
turtle.turnLeft() 
turtle.forward() 
turtle.forward() 
turtle.forward() 
turtle.placeDown() 
turtle.forward() 
turtle.placeDown() 
turtle.forward() 
turtle.placeDown() 
turtle.forward() 
turtle.turnLeft() 
turtle.forward() 
turtle.turnLeft() 
turtle.forward() 
turtle.placeDown() 
turtle.forward() 
turtle.placeDown() 
turtle.forward() 
turtle.placeDown() 
turtle.forward() 
turtle.turnRight() 
turtle.forward()
turtle.forward()
turtle.forward()
turtle.forward()
turtle.turnRight()
turtle.forward()
turtle.placeDown()
turtle.forward()
turtle.placeDown()
turtle.forward()
turtle.placeDown()
turtle.forward()
turtle.turnLeft()
turtle.forward()
turtle.turnLeft()
turtle.forward()
turtle.placeDown()
turtle.forward()
turtle.placeDown()
turtle.forward()
turtle.placeDown()
turtle.forward() 
turtle.turnLeft() 
turtle.forward() 

for n = 1, 4 do -- builds 2x2x2 blocks 4 times on top of the platform, each 2x2x2 block is near the edge of the platform 

for n = 1, 2 do -- then adds 1x1x4 tower on top of each of the 2x2x2 block structures 

turtle.up() 
turtle.select(6) 
turtle.placeDown() 
turtle.forward() 
turtle.placeDown() 
turtle.turnLeft() 
turtle.forward() 
turtle.placeDown() 
turtle.turnLeft() 
turtle.forward() 
turtle.placeDown() 
turtle.turnLeft() 

end

turtle.up()
turtle.placeDown()
turtle.up()
turtle.placeDown()
turtle.back()
turtle.down()
turtle.down()
turtle.down()
turtle.down()
turtle.back()
turtle.turnLeft()
turtle.forward()
turtle.turnLeft()
turtle.forward()
turtle.turnLeft()

end

turtle.forward()
turtle.up()
turtle.up()
turtle.up()
turtle.up()
turtle.select(1)
turtle.placeDown()
turtle.forward()
turtle.placeDown()
turtle.forward()
turtle.placeDown()
turtle.forward()
turtle.back()
turtle.back()
turtle.turnLeft()
turtle.back()
turtle.placeDown()
turtle.forward()
turtle.forward()
turtle.placeDown()
turtle.turnLeft()
turtle.forward() 

for n = 1, 4 do 

turtle.up() 
turtle.select(2) 
turtle.placeDown() 
turtle.up() 
turtle.placeDown() 
turtle.turnLeft() 
turtle.forward() 
turtle.down() 
turtle.down() 
turtle.forward()

end -- builds the 3x3x14 tall tower section of the structure on top of the 1x1x4 pillars 

turtle.up()
turtle.up()
turtle.forward()
turtle.turnRight()
turtle.turnRight()

for n = 1, 14 do 

turtle.up() 
turtle.select(9) 
turtle.placeDown() 
turtle.forward() 
turtle.select(10) 
turtle.placeDown() 
turtle.forward() 
turtle.select(9) 
turtle.placeDown() 
turtle.turnLeft() 
turtle.turnLeft() 

end

turtle.back() 
turtle.turnRight() 

for n = 1, 14 do 

turtle.down() 

end 

turtle.forward() 
turtle.turnLeft() 
turtle.forward() 

for n = 1, 14 do 

turtle.up() 
turtle.select(11) 
turtle.placeDown() 
turtle.forward() 
turtle.select(12) 
turtle.placeDown() 
turtle.forward() 
turtle.select(13) 
turtle.placeDown() 
turtle.turnLeft() 
turtle.turnLeft() 

end

turtle.back() 
turtle.turnRight() 

for n = 1, 14 do 

turtle.down() 

end 

turtle.forward() 
turtle.turnLeft() 
turtle.forward() 

for n = 1, 14 do 

turtle.up() 
turtle.select(14) 
turtle.placeDown() 
turtle.forward() 
turtle.select(15) 
turtle.placeDown() 
turtle.forward() 
turtle.select(16) 
turtle.placeDown() 
turtle.turnLeft() 
turtle.turnLeft() 

end

for n = 1, 2 do -- builds a 3x3x2 glass structure at the top of the tower section 

turtle.up() 
turtle.select(8) 
turtle.placeDown() 
turtle.forward() 
turtle.placeDown() 
turtle.forward() 
turtle.placeDown() 
turtle.forward() 
turtle.turnLeft() 
turtle.forward() 
turtle.turnLeft() 
turtle.forward() 
turtle.placeDown() 
turtle.forward() 
turtle.placeDown() 
turtle.forward() 
turtle.placeDown() 
turtle.forward()
turtle.turnRight() 
turtle.forward() 
turtle.turnRight() 
turtle.forward() 
turtle.placeDown() 
turtle.forward() 
turtle.placeDown() 
turtle.forward() 
turtle.placeDown() 
turtle.turnRight() 
turtle.turnRight() 

end 

turtle.forward() -- builds a 1x1x3 block tall antenna at the very top of the glass structure 
turtle.turnLeft() 
turtle.forward() 
turtle.select(7) 
turtle.up() 
turtle.placeDown() 
turtle.up() 
turtle.placeDown() 
turtle.up() 
turtle.placeDown()
















