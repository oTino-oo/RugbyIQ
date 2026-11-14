# Requirements

## Functional Requirements

FR1 - Allow the coach to add a player with a unique ID.
FR2 - Allow the coach to search for a player using their ID or name.
FR3 - Allow the coach to update a player's availability and rating.
FR4 - Allow the coach to remove a player from the squad.
FR5 - Generate a proposed starting XV using registered players.
FR6 - Display the proposed team and show any positions that cannot be filled.
FR7 - Save generated team selections in the selection history.
FR8 - Allow the coach to view previous team selections.
FR9 - Allow the coach to search for a previous selection.
FR10 - Allow the coach to remove a previous selection.

## Non-Functional Requirements

NFR1 - The application should have a simple console menu.
NFR2 - Player information should be protected using encapsulation.
NFR3 - The system should check player information before storing it.
NFR4 - Dynamically allocated memory should be managed correctly.
NFR5 - Each class should have its own responsibility.
NFR6 - Team selection should give the same results when using the same player information.
NFR7 - The application should handle invalid input without crashing.
NFR8 - Header and source files should be kept separate.

## Assignment Requirements

Current idea
Tree:
- To manage registered players.
Linked List:
- To store previous team selections.

## Selection Rules

A rugby union starting team consists of 15 players.

### Forwards (8)

- 1 Loosehead prop
- 1 Hooker
- 1 Tighthead prop
- 2 Locks
- 2 Flankers
- 1 Number eight

### Backs (7)

- 1 Scrum-half
- 1 Fly-half
- 2 Centres
- 2 Wings
- 1 Fullback

### Team Selection Rules

- Only available players can be selected.
- Players must be assigned to the position they are being selected for.
- Players with higher ratings should be selected first.
- If two players have the same rating, the player with the lower ID should be selected first.
- A player cannot be selected more than once.
- If there are not enough available players for a position, the system should show which positions are empty.
