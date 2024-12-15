# Profile List

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

The source code of this project can be found under the folder `/profile-list`.

## Getting Started

To run the project, you need to run the following command in the profile-list directory of this project:

```
yarn start
```

It will run the app in the development mode. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### Features

This project includes the following features:

1. Left panel contains the profile list and the right panel contains the selected profile name.
2. Clicking a profile should select the profile and will be highlighted in green and the right panel will be updated.
3. Move up, move down, and add (+) icon are always shown. If the selected profile is at the most top of the list, move up will be disabled. Same goes if the selected profile is at the most bottom of the list, move down will be disabled.
4. User has 4 default profiles: Default, Game, Movie and Music. Default profiles have their own icons, can be moved up and down, but cannot be renamed or deleted. Hence delete and rename icon should not be shown on the UI if the selected profile is a default profile.
5. User can choose to add a custom profile by clicking the add (+) icon. Custom profile should be named "New Profile", added to the last of the list and should be automatically selected.
6. If a selected profile is deleted, it should automatically select the profile above the deleted profile.
7. Rename should be trimmed and do not allow just an empty space for the name.
8. Any changes by the user should be saved in the LocalStorage. If no data is stored in the LocalStorage, populate it with the 4 default profiles in the following order: Default, Game, Movie and Music. Selected profile should be "Default".
9. Profile data array would be something like this [{name: 'Default', ...}, {name: 'Game', ...}] but you are given the freedom on what other properties it should have to implement the requirements.
