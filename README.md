# Flashcard-o-matic App
Flashcard-o-matic is an app that is intended to allow users to create a series of decks that contain flash cards for any subject that the intended user is planning to study.
## ScreenShots
### Home Screen
![HomeScreen](/screenshots/homescreen.jpg)
The home screen allows for users to:
- View all the available decks that have been created.
- Create a new deck using the create deck button.
- View a particular deck by clicking the view button which will take the user to that deck's Deck screen.
- Study a particular deck by clicking the study button which will take the user to the Study screen.
- Delete a particular deck by clicking the delete button.
### Deck Screen
![DeckScreen](/screenshots/deckscreen.jpg)
The deck screen allows for users to:
- View the deck's name and description.
- Create a new card using the add cards button.
- Edit the current deck information by using the edit button.
- Study the current deck selected by using the study button. 
- A delete button that will delete the current deck.
- Under each card in the deck it contains:
  * shows a question and the answer to the question.
  * has an "Edit" button that takes the user to the Edit Card screen when clicked on.
  * has a "Delete" button that allows that card to be deleted. 
### Card Screen
![CardScreen](/screenshots/cardscreen.jpg)
The Add Card screen allows the user to add new cards to the deck. This screen has the following features:
- Displays a front field and a back field that allows for the user to input a desired question and an answer
- If the user clicks on the "Done" button, the user is taken to the Deck screen.
- If the user clicks on the "Save" button, a new card is created and associated with the relevant deck. Then, the form is cleared and the process for adding a new card is restarted.
## Learning Objectives
This project was designed to test the ability to work with rendering and state management using React.
- Running tests from the command line
- Installing packages with NPM
- Using React functional components and React hooks (i.e. ```useState(), useEffect()```)
- Using React Router and related hooks (i.e. ```useParams(), useHistory(), Link, Route``` etc.)
- Using pure functions and lifting state to optimize computing power
## Technology
### Built with:
- React, JavaScript, HTML, and Bootstrap 4 for styling.
