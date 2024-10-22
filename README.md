# Defining-a-Manual-Test-Suite
Block 18 Workshop Pt II: Defining a Manual Test Suite: Puppy Bowl
Here's an outline of a test plan for the "Puppy Bowl" feature requirements:

### Main Page:
#### 1. Displaying All Players:
- **Test Case:** Check that all players are displayed in a formatted list.
- **Steps:** 
  - Open the main page.
  - Verify that all existing players appear in a structured layout.
  - Ensure each player has "See details" and "Remove" buttons.

#### 2. "See Details" Button:
- **Test Case:** Ensure the "See details" button shows the correct player details.
- **Steps:**
  - Click on the "See details" button for a player.
  - Verify the player's name, breed, and team (or "unassigned") are displayed.
  - Check that the larger picture of the player is shown.
  - Test the "Back" button to confirm it returns to the main list.

#### 3. "Remove" Button:
- **Test Case:** Ensure that the "Remove" button removes the player from the roster.
- **Steps:**
  - Click the "Remove" button for a player.
  - Confirm the player is removed from the roster without a page refresh.
  - Refresh the page to confirm the player is still gone.

### Adding Players:
#### 4. Add New Player Form:
- **Test Case:** Ensure that the form correctly adds a new player.
- **Steps:**
  - Enter a player name and breed.
  - Click "Submit" to add the player.
  - Verify that the new player appears in the roster immediately without a page refresh.

### Removing Players:
#### 5. Removing Players:
- **Test Case:** Confirm removing a player works as expected.
- **Steps:**
  - Click "Remove" next to a player.
  - Check that the player disappears from the list without refreshing the page.
  - Ensure the player is permanently removed by refreshing the page.

### Stretch Goals:
#### 6. Show Teammates in Single Player View:
- **Test Case:** Ensure that the teammates of a selected player are displayed.
- **Steps:**
  - Click "See details" for a player.
  - Verify that all players from the same team are shown.

#### 7. Change Team Assignment:
- **Test Case:** Ensure users can change the team assignment via dropdown.
- **Steps:**
  - In the single player view, change the team from the dropdown.
  - Confirm that the team assignment updates immediately on both the single player view and the main roster without refreshing.

#### 8. Add Player with Image URL:
- **Test Case:** Ensure that adding a player with an image URL works.
- **Steps:**
  - Fill out the form with the player's name, breed, and an image URL.
  - Click "Submit."
  - Confirm the new player appears on the roster with their image displayed correctly.

#### Edge Cases:
- Test adding players without filling out required fields (name, breed).
- Test for maximum input length or invalid characters in the player name/breed fields.
- Test removing the last player in the list.
- Test the behavior if no players are in the roster initially.

This framework will help guide testing during development. we can easily convert these into a spreadsheet with columns for feature, test case, steps, expected results, and actual results.
[Click here for spreadsheet!](https://docs.google.com/spreadsheets/d/14xVfQuhxDuLP2c1ZTJdR1ftVXekAxcprt2hBMO0IrVs/edit?usp=sharing)
