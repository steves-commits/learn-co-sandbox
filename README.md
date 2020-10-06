
puts "Welcome to the Rental Car Fee Checker! To begin, please enter your age."

age = gets.strip.to_i

minimum_rental_age = 21 
if age < minimum_rental_age puts "Sorry, you are too young to rent a car" 
end

puts "age is #{age}"