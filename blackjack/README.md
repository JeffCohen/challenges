# Blackjack Simulation

**15 points**

For easiest viewing of these instructions, you may want to view online with a Markdown previewer.

### Preparation ###

1. Copy this entire folder into the top level of your own repository.  Make sure the folder name remains the same.
2. Commit and push to your repository.  Verify that you can see it online.
3. You can continue to commit and push often.
4. When you think you're done, create a file named "GRADE.md" with one line in the file that says "I'm done", a riddle, or an interesting tidbit of computer science trivia. (This is because Git won't push empty files). Then commit and push your changes.


### Instructions

Challenge: Implement a simple version of a Blackjack simulation.

The goal is for the user to reach 21 points, or as close as possible, without going over.

Game Rules:

1. Play starts with the human player on the left side of the screen (top side in
a mobile view).
3. Clicking "Take Another Card" should add another card to the user's hand of cards.
4. If the user reaches exactly 21 points, the user wins and the game is over.
5. If the user goes over 21 points, the user loses and the game is over.
6. If the user clicks "Stand", it now becomes the dealer's turn to take cards.
7. The dealer MUST take cards until the dealer's total is 17 or higher.
8. If the dealer reaches exactly 21 points, the dealer wins and the game is over.
9. If the dealer goes over 21 points, the dealer loses and the game is over.
10. If the dealer reaches 17, 18, 19, or so points, the dealer must stop taking cards.  If the dealer's hand is equal to the value of the user's hand, it's a tie and nobody wins. Otherwise the winner is whoever has more points in their hand. 

Card values are determined as follows:

1. Cards 2 through 9 are worth their face value.
2. 10, Jack, Queen, and King are each worth 10 points.
3. Aces are always worth 11 points.

Please note:

* The `images` subfolder provides all of the card images that you will need.  
* You can choose to write your JS directly in the index.html file or create a separate JS file.
* You may use any HTML/CSS code, including any CSS framework, but you cannot use a JS framework.
* HINT: Note that all of the image filenames follow a specific pattern to make 
it easier for you to programmatically determine the image `src` attribute values.

**Grading Rubric**

* 10 points: The game follows all of the rules above.
* 5 points: Dealer cards are animated with a 2-second pause between each card.
