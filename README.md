# SwiftUI Technical Assessment

## Prerequisites

- Read the **README** fully.
- Review [the PokéAPI v2 documentation](https://pokeapi.co/docs/v2).
- Create the app using the latest production version of Xcode.

## The Main Objectives

Using the [PokéAPI](https://pokeapi.co/docs/v2), create a simple **SwiftUI** list-detail app that does the following:

- Fetches and displays a list of 100 Pokémon using the https://pokeapi.co/api/v2/pokemon?limit=100 endpoint.
- Displays their names as a list in the left sidebar (which collapses in compact mode).
- Allows the user to toggle between sorting the list alphabetically and by id number.
- When selecting a name from the sidebar, the app should use the previously returned pokemon ID URL (ex: https://pokeapi.co/api/v2/pokemon/1) to retrieve additional info and display a detail view on the right side. Please include their name, ID, base experience, and all of their ability names.
- Have working previews for each SwiftUI view.
- Add at least 2 unit tests.
- The application must compile and run.
- Sensibly document your code, and include a readme with instructions and notes.


## Bonus (Optional) Tasks

- Display Pokémon sprite images in the detail view.
- Cache data across app launches for offline use.
- Paginate the list so additional Pokémon can be fetched by the user.
- Add additional sorting or filtering options to the list.
- Add additional unit tests — the more coverage of the app’s functionality, the better.

## Considerations / Recommendations

- This is your opportunity to show what you can bring to our engineering team, and how you approach tasks in your day-to-day work.
- Write clean, reusable, readable code.
- The main objectives shouldn’t take more than 1-2 hours to complete.

## How to Submit your Assessment

- After we acknowledge the receipt of your application, send us a link to a GitHub repository (or other hosted Git repo) with your assessment code in it.
- If you cannot immediately submit your assessment, please let us know when to expect it.

## Evaluation

_The assessment will be evaluated based on the following:_

- Code
	- Quality
	- Structure
	- Readability
  - Testability 
	- Documentation 
- Bonus Tasks
