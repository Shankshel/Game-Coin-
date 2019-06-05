# Game "Coin"

Write the program "Coin": it generates a random number 0 or 2
And displays "Eagle fell out" for zero, "Tails dropped out" for one or "Coin has risen on an edge!"

coin = rand(2)

if coin == 0
	puts "Выпал орел!"
elsif coin == 1
	puts "Выпала решка!"
else
	puts "Монета встала на ребро!"
end
