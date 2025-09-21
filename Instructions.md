# Instructions

Answer the following questions in the spaces below, then upload this file to Canvas.

Name: Azra Emekci    Per: 4    Date: 3/3/2025

1. For Board and ElevensBoard, which is the superclass and which is the subclass. Explain why and also how you can tell by looking at the starter code.
	The Board class is the superclass and the ElevensBoard is the subclass because the ElevensBoard is an extension of Board, as stated by the keyword "extends" when the ElevensBoard is initialized.

   
2. As discussed previously, all of the instance variables (deck and board) are declared in the Board class. But it is the ElevensBoard class that “knows” the board size, and the ranks, suits, and point values of the cards in the deck. How do the Board instance variables get initialized with the ElevensBoard values? Give the line of code and say where it would be put.
	The Board class has a constructor that takes in arguments for those and the ElevensBoard calls the superclass constructor.



3. Explain why the deal method is in the Board class, but containsJQK is in the ElevensBoard class.
	Deal is in the Board class because it is a general method for dealing cards for any type of card game, not just Elevens, whereas constainJQK is in the ElevensBoard class because it is specific to the game Elevens.


4. Give two advantages of reorganizing the code and using inheritance instead of just using a single class.
	For one, the Board class can now be used for other games as well since it's not just specific for Elevens. Another advantage is that you can override methods instead of rewriting everything if you want to create similar games to Elevens.

