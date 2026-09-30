# Florin Cards: public files

Public home for the two files the Florin Cards game needs to reach over the internet:

- `privacy.html`: the privacy policy, served by GitHub Pages at
  https://funfetsunk.github.io/florin-cards/privacy.html (the URL given to Google Play).
- `config.json`: live game settings, fetched by the game at start-up from
  https://raw.githubusercontent.com/Funfetsunk/florin-cards/main/config.json.
  Balance values, events and pass seasons pushed here reach players without an app update.
  The game ignores anything that doesn't match the shape of its bundled data.

Privacy questions: open an issue on this repository.
