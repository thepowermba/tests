# Frontend Test

## 1. Create a simple app with file upload button. When we upload a file, a button should appear saying format file. Clicking on the format file button should show a preview of the file in table format.

>### To do:-
- The file picker should only take .csv files.
- Show a preview to the user of the reformatted data in table format.
- Table should also have headers which are mentioned in the first line of .csv file.
- Remove any special characters mentioned in the .csv file headers.
- Button should only show when above mentioned action is performed.
- Use flexbox and grid exclusively for layouts.	

>### Extra points:-
- Remove repetitive data if two users have same emails. Keep the user whose first name comes first.
- Show repetitive data which is removed in a separate table.
- Add a sort by select element where user can pick sorting based on first name or last name. It should change the view of table data.
- Add a button to download the reformatted data in csv format.

## 2. Create a movies app. An app where you can create watchlist of your favorite movies with genre and whether you have watched that movie or not.

>### To do:-
- Create an input where user can add the movie name they would like to watch.
- Create another input where user can add movie genres as tags.
- Each movie can have more then one genres.
- When user presses enter on genre input, it should show those genres below the the movie name input.
- User can add the same genre more than once and press enter; but that genre shouldn't show it the list again.
- Genres should be case insensitive. Use should not be able to add horror and Horror.
- Create a submit button where user can click to submit there movie.
- All the movies should show in a list where below the form with the following fields:-
	1. Checkbox that shows if movie is watched or not.
	2. Movie name.
	3. Genres.
	4. Delete button.
- Watched or checked movies should move down to the bottom of the list.
- If user unchecks a movie it should move to its original place.
- Add three radio buttons at the top of the list which say Horror, Romance, Comedy and a reset button.
- All the radio buttons should be unchecked by default.
- Selecting any of the radio buttons should show only the movies which are in that genre.
- Clicking on the reset button should show original list.
- Add an input above the list and below the radio buttons where user can search the movies based on their name.
- Use redux the implement the handling of state.
- Show a loader when adding a movie or deleting a movie or searching for a movie. The delay should be 3 seconds. 

>### Extra points:-
- If go to route like /genre=romance, it should redirect me to a new page which should show the loader for 3 seconds and then only movies which have that genre.
- Add an edit button in the movie list. Clicking on the button should turn the movie name into an input tag with the movie name in it and also show a save button. Which user can then edit and save.
- User cannot save an empty movie name.
- Clicking on the delete button should open a small modal which should have two buttons Yes and No. Clicking on No should hide the modal. Clicking on yes should hide the modal and delete that movie from the list.
- When movie is deleted it should show a message at the bottom which should show an undo button. The message should display for 5 seconds and should not disturb user's interaction with rest of the app. Clicking on undo button should add that movie back to it's original position.

>### Note:-
- We know that the actions performed in this app are not async. So we would like you to implement your own async logic. You can use setTimeouts, setIntervals, Promises etc.
- Your design must be mobile first and reponsive.
- When you submit your code let us know which extra points features you have completed.


## Things to keep in mind:-
- Please document, lint and format your code.
- Your code should be modular and re-usable.
- Code should be properly documented and easier to understand.
- Style your buttons and inputs and tables using your own css and not any framework.
- Your design must be mobile first and reponsive.
- When you submit your code let us know which extra points features you have completed.
- Please add your code on github and make a commit with every change so we can review the code with each incremental step.
