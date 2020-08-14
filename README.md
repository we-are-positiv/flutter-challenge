# Positiv Flutter Challenge

## Challenge description

Implement a GitHub repository explorer app using Flutter

The app must use the GitHub API ([REST](https://docs.github.com/en/rest) or [GraphQL](https://docs.github.com/en/graphql)) to list the public repositories of the Flutter user: https://github.com/flutter

### Screen 1 (Main Screen)

- The main screen of the app should consist of a list of repositories which belong to the [Flutter user](https://github.com/flutter);
- Each repository should be presented as a card with name, description, creation date, language and number of stars;
- Each card should have a "Save repo" button that will add the repository to a list of saved repositories;
- At the top of the screen, there should be an icon (e.g. a bookmark icon) alongside a count badge that indicates how many repositories have been saved/bookmarked by the user;
- Clicking on the bookmark icon should take the user to Screen 2.

### Screen 2 (Saved Repositories)
- This screen should present a list of saved repositories;
- Each repository should be presented with its name and with a "delete/remove from favorites" icon;
- Clicking on the icon should make the item disappear from the list and also decrease the saved items counter on Screen 1.

Feel free to create an experience that feels the most pleasant to the user.

## Requirements

- Use a state management solution (any package you want).

## Bonus

- Be creative and show us what you've got;
- Write unit tests, widget tests and any other tests you find helpful or important to have.

## Delivery

- **Don't** fork this project. Create a new repository in your account and send us the URL;
- Create a README file with any special instructions or comments that you consider relevant.

## What will be evaluated?

- Readability;
- Maintainability;
- Creativity.

Thanks and good luck! 🍀