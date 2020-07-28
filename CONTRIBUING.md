# How to contribute to the Slowcial Media website

All code for this website is open source. Pull requests are welcome. Please [read the README.md]( ./README.md ) to learn how this website is generated. The most important ting for pull requests:

- Edits should be made to `src/`, never to `docs/`
- There is no need to build the website from source, the repository does this through CI

## How to add an app to the featured list

*Non coders: ask a collegue or friend for hel with this.*

1. Fork this repo
1. Open `src/pug/_apps.pug`
1. Add your app under the right section
    - There is a strong preference for `.svg` logos
    - Keep the description short enough that is stays in balance with the other apps
1. Commit your changes and create a pull request