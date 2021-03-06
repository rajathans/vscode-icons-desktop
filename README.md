# VSCode Icons Manager
> Currently Work in Progress

This project was born from the necessity of a desktop app that helps you manage **[@dhanishgajjar][dhanish]** custom [vscode icons][icons]

<p align="center">
    <img src="https://user-images.githubusercontent.com/16429579/45490907-9fc88300-b768-11e8-9a4c-96c2e6576c83.png" alt="cover">
</p>


# Run
As we don't actually have a build phase you need to run this app via electron.

#### ⚠️ This app currently works only on macOS

- Clone this repo 
- Install all dependencies via "npm" or "yarn"
- Run via "npm start" or "yarn start"

# Known issues
- After download you need to `cmd + click` on the dock icon to update it.
- If the icon has been downloaded in the past the loading screen and the notification doesn't appear on the screen. (NOTE: This has been temporally fixed by deleting it after download.)

# Contribute
Contributors are always welcome! To ensure that your PR will be merged please follow the code-style

## TODO before release
<br />
<br />

- [ ] App icon
- [ ] Implement hiddenInset titlebar style
- [ ] Implement tests

<br />
<hr />
<br />

- [ ] Better UI / UX
- [ ] Make it universal, right now it works only on macOS systems.

<br />
<hr />
<br />

- [ ] Add local icons
- [ ] Add settings
- [ ] Add an "history panel" or something similar
- [ ] Help menu items that refers to [vscode-icons repo][icons] and this repo
- [ ] Custom "About" panel with credits

<br />
<hr />
<br />

- [ ] Implement build
- [ ] Automatization of icon update... Right now after the app changes the file you need to "cmd+click" on the dock icon or restart to update the icon in the dock.

<br />
<br />
<br />


# Related

- [vscode-icons][icons] is a project by **[@dhanishgajjar][dhanish]**

<br />
<br />
<br />

<p align="center">
  <b>Follow Me on</b>
  <br /> 
  <a href="https://twitter.com/rawnlydev"> Twitter </a> | <a href="https://instagram.com/fede.vitale"> Instagram </a>
</p>


[dhanish]: https://github.com/dhanishgajjar/
[icons]: https://github.com/dhanishgajjar/vscode-icons