# Number_Guessing_Game
The user is required to guess a number between 1 and 20, and the game will provide feedback on whether the guess is too high, too low, or correct. The page displays the current score, the highscore, and allows the user to play again.

Here's a breakdown of the HTML and JavaScript code:
    HTML Structure:
        The HTML starts with the <!Doctype HTML> declaration, specifying the document type as HTML5.
        The <meta> tag sets the character encoding to UTF-8.
        The <html> element sets the language attribute to "en" for English.
        The <head> section contains the title "Number Guessing Game" and some CSS styles.
        The <body> section contains the content of the web page, including the game interface.

    CSS Styles:
        The CSS defines various styles for the elements in the game, such as background colors, fonts, and layout.
        The .header, .ruler, and .questionmark classes define styles for the game's header and question mark symbol.
        The .row class defines the layout of the input form and side information.
        The .Button class defines the style for the buttons used in the game.

    JavaScript:
        The JavaScript part of the code handles the game logic.
        Three variables are declared at the top: random (for storing the random number to guess), score (to track the current score), and highscore (to store the highest score achieved).
        The again() function initializes or resets the game when the "Again!" button is clicked. It sets the background color, score, and generates a new random number between 1 and 20.
        The check() function is called when the "Check!" button is clicked. It checks the user's input against the random number and provides feedback based on the comparison. If the guess is correct, it updates the highscore if needed.
        The score is decremented with each guess to reduce the score until the player wins the game.

Overall, this code creates a simple and interactive number guessing game where the player tries to guess the correct number and beat their own high score.
