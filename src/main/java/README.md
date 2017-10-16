To do:

Check Formatting!

Stretch tasks for myself:
- add option for when there are no more pets to adopt
- add option when shelter is full
- add option when name is entered that isn't an option
- add starting health stats for newly admitted pups (make sure table formatting is set
- do not allow for negative numbers
- set caps and cause/effect

Virtual Pet Stretch Tasks:

- Give the pet the ability to take care of some of its own needs.

- Pets are not robots - they usually have some sort of self-determination! When tick() is called, 
you might want to have your pet take a look at its needs and address one, prioritizing whichever need is highest. 
You could also make your pet uncooperative - when the user tries to feed the pet, for example, you might make the pet refuse to eat if it is bored. 
Remember how we created an instance of the Random class to create a random number generator? You might want to incorporate that.

- Create a visual representation of your pet.

Rather than using numbers to convey your pet's status, you could have some sort of visual representation of the pet. 
I.e., instead of printing hunger: 50, you could use smileys or ASCII art to show hunger when hunger >= 50.

		     >=<        
		,.--'  ''-.
		(  )  ',_.'
		Xx'xX      
		
		Horace looks like this: :0
		
		1. Feed Horace
		2. Water Horace
		3. Play with Horace
		4. Put Horace to sleep
		5. Do nothing

- Assign favorite foods to your pet, and add a parameter specifying the type of food to the method you use to feed your pet. 
Your pet should react accordingly. You could also decide which foods it does not like.


- Keep track of the cleanliness of individual pets' cages and offer an option in the user interface to clean pet cages.

- DNA! In order to give your pets individual character, include as part of each pet's state one or more multipliers for needs 
so that one pet may become hungrier/thirstier/more bored slower/faster than another pet. (Tip: you could create a class to encapsulate this.)