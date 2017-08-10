## Contributing

If you want to contribute to a project and add translation to your language, your help is very welcome.

### How to make a pull request

- Create a personal fork of the project on Github.
- Clone the fork on your local machine. Your remote repository on Github is called `origin`.
- Add the original repository as a remote called `upstream`.
- If you created your fork a while ago be sure to pull upstream changes into your local repository.
- Create a new branch to work on! Branch from `master`.
- Add new `values-xx` folder in `translations/src/main/res/` folder, where `xx` is the language code.
- Check language code for your language [here](https://support.google.com/googleplay/android-developer/table/4419860?hl=en).<br>
  For example for German the language code is `de`, so the folder name will be `values-de`.
- Copy all files from the `values` folder to the newly created folder `values-xx` (except the ones with the `_global` suffix).
- Translate strings from English to your language.<br>
  Strings for translations are inside the `<string></string>` tags
  For example:<br>
  English: `<string name="action_select_date">`**Select date**`</string>`<br>
  German: `<string name="action_select_date">`**Datum auswählen**`</string>`<br>
- Follow the code style of the project, including indentation.
- Push your branch to your fork on Github, the remote `origin`.
- From your fork open a pull request in the correct branch. Target the project's `master` branch.
- ...
- Once the pull request is approved and merged you can pull the changes from `upstream` to your local repo and delete your extra branch(es).

And last but not least: Always write your commit messages in the present tense. Your commit message should describe what the commit, when applied, does to the code – not what you did to the code.

## Thanks to translators:

- Alexander Fischer (Deutsch / Deutschland)
- Izar Castorina (Italiano)
- Oleh Tsyupka (Українська)
- Sergio Bartolomé Carrera (Español)
- Robert van der Rhee (Nederlands)
